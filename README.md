UPDATE -:

I haven't had the time, to work on this sadly. But someone created a fork which I strongly recommend you use over this as it is much more updated.

https://github.com/luismaia/rails4-bootstrap-devise-cancan-omniauth

Start Up Rails 4 app with Devise, Omniauth, cancan and twitter bootstrap in mysql

1) Make changes to development.rb to add correct settings for email

2) Make changes to devise.rb to add config email, and also external service app_id, and secret key (i.e. - facebook)

3) Rake db:create, db:migrate

4) Rake db:seeds to load first user (admin)

5) Run rails server

6) Have fun!

