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
 
  
