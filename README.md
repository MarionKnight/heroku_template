##This is a template with the minimum files needed for pushing applications 
from DBC local to heroku. To create the heroku app:

`rake db:create_migration`

`rake db:migrate`

`heroku login`

`git add -p`

`git commit -m "whatever comment"`

`git push heroku branch:master`


