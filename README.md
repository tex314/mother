## Clone repository

    $ git clone git@github.com:tex314/mother.git
    $ cd mother

## Install bundler

    $ gem install bundler

## Install rubygems

    $ bundle install

## Configuration settings

    $ cp config.rb.example config.rb
    $ vi config.rb

## Launch the server

    $ middleman server
    == The Middleman is loading
    == The Middleman is standing watch at http://0.0.0.0:4567

## Check the local site

    $ open http://0.0.0.0:4567 

## Add a page

    $ emacs source/2013-04-01.html.markdown
            
## Deploy page

    $ middleman deploy

## Check the site

    $ open http://mother.okzk.org/
