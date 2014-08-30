middleman-hamlsasscoffeeblog
============================

A [Middleman](http://middlemanapp.com/) blog template scaffold  using [Haml](http://haml.info/), [Sass/Scss](http://sass-lang.com/), [Coffeescript](http://coffeescript.org/), and [Bower](http://bower.io/).


Install as a middleman template
-------------------------------

    mkdir -p ~/.middleman/
    git clone https://github.com/CodyReichert/middleman-hamlsasscoffeeblog.git ~/.middleman/middleman-hamlsasscoffeeblog
    middleman init project_name --template=middleman-hamlsasscoffeeblog
    cd project_name
    bower install
    bundle exec middleman server

Install for single project
--------------------------

    git clone https://github.com/CodyReichert/middleman-hamlsasscoffeeblog.git
    cd middleman-hamlsasscoffeeblog
    bower install
    bundle exec middleman server


Other
-----

Activate LiveReload

  config.rb line 79:

    activate :livereload
