# Ruby on Rails Tutorial: sample application

This is the sample application for
the [*Ruby on Rails Tutorial*](http://railstutorial.org/)
by [Michael Hartl](http://michaelhartl.com/).

http://ruby.railstutorial.org/chapters/static-pages#top

    rails new sample_app --skip-test-unit --skip-bundle

    subl .gitignore Gemfile

    rails generate controller StaticPages home help --no-test-framework
    ## rails generate v.s. rails destroy ...
    ## rake db:migrate v.s. rake db:rollback v.s.  rake db:migrate VERSION=0
 
    rails generate integration_test static_pages
    ## Capybara::DSL
    ## bundle exec rspec spec/requests/static_pages_spec.rb
    ## the cycle of Red, Green, Refactor

    ## ch4. Rails-flavored Ruby
    ## helpers defined in ApplicationHelpers module
    ## are automatically available in views

    ## ch5. page design and named routes
    ## rails generate controller Users new --no-test-framework
    ## rails generate integration_test user_pages
    ## bundle exec rspec spec

    ## ch6. modeling users
    ## rails generate controller Users new --no-test-framework
    ## rails generate model User name:string email:string
    ## bundle exec rake db:migrate
    ## rails console # User.create, find, ...
