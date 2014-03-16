##How To Re-create

* Create app on github with callback http://SERVER:PORT/auth/github/callback
* Add github app client id key to line 206 of /spec/models/user_spec.rb
* Add the following to config/environment.rb 
** ENV['SECRET_TOKEN']="xx"
** ENV['GITHUB_KEY']="" from github app page
** ENV['GITHUB_SECRET']="" from github app page
