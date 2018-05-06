# README

This README would normally document whatever steps are necessary to get the
application up and running.


Here are the details to start Application

Setup db and run bundle install

After commands to execute 
open rails console using 
rails c

After commonds
user = User.create(:name => "Sam")
Shortener::ShortenedUrl.generate("https://www.youtube.com/", owner: user, custom_key: "abc")
* Use any url you want in the command I have used Youtube.com


Now run the rails server 
got to url
http://localhost:3000/users/1


here you will find the shortend url of your website