# GettingStartedRails
A repository of tutorial code to get started learning Rails for the ACM eSports Matching project.
* [http://guides.rubyonrails.org/getting_started.html](http://guides.rubyonrails.org/getting_started.html) is the tutorial for the `blog` app in this repository
* [https://www.railstutorial.org/book/beginning](https://www.railstutorial.org/book/beginning) is the tutorial for `hello_app`

## Dependencies
* Ruby (version 2.2.2 or higher)
* RubyGems package manager
* Rails gem
* SQLite3

### Other Notes
* Deploying to heroku seems relatively easy from the railstutorial book. Remember that bin/{rails,rake,bundle} have their ruby version in the #!/ line ... heroku uses a version different from 2.3
* heroku also uses postgresql instead of sqlite3 ... so the Gemfile needs to be edited to reflect that
* run database migrations on heroku as well with `heroku run rake db:migrate`
