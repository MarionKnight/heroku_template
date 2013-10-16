This is copied from the doodle_poodles app. It needs one more pass to 
create the minimum files needed for pushing applications from DBC local 
to heroku. For now, the steps we needed in creating the heroku app are:

rake db:create_migration
rake db:migrate
heroku login
git add -p
git commit -m "whatever comment"
git push heroku branch:master


