omniauth-venmo--twitter--facebook-sample-application
====================================================

devise and omniauth integration sample application

In devise.rb configure below lines with your app id and app secret.

require "omniauth-facebook"
config.omniauth :facebook, "APP_ID", "APP_SECRET", :client_options => {:ssl => {:verify => false}}

require "omniauth-twitter"
config.omniauth :twitter, "APP_ID", "APP_SECRET", :client_options => {:ssl => {:verify => false}}

require "omniauth-venmo"
config.omniauth :venmo, 'APP_ID', 'APP_SECRET',{:client_options => {:ssl => {:verify => false}}}
