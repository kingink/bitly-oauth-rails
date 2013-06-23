# Bitly Oauth Rails Example


## Setup on bitly

Go to http://bitly.com/a/oauth_apps and follow the steps to register a new application.

Make sure to use your Client ID and Client Secret in index.html.erb and welcome_controller.rb.


## The files
This really consist of only three files:

[/app/views/welcome/index.html.erb](https://github.com/kingink/bitly-oauth-rails/blob/master/app/views/welcome/index.html.erb) - Simple link that starts the authentication process.  This will take the user to a bitly login page.

[/app/controllers/welcome_controller.rb](https://github.com/kingink/bitly-oauth-rails/blob/master/app/controllers/welcome_controller.rb) - This is were the meat is.  After the user logs in they will be redirected back here for more of the oauth process and to get the user access token.

[/app/views/welcome/oauth.html.erb](https://github.com/kingink/bitly-oauth-rails/blob/master/app/views/welcome/oauth.html.erb) - Access_token and Login will show on this page.


##Links

[bitly Developer Website](http://dev.bitly.com/)

[More on bitly Authentication](http://dev.bitly.com/authentication.html)
