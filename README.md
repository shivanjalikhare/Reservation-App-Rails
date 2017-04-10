Reservation
Ruby on Rails version 5.0.2 04/10/2017

-deploy an app to show some powers of rails.

-generating an application is rapid using "scaffold generators", which create large amount of functionality automatically.

-used heroku as a web application deployment model to run and scale applications in a similar manner across all the 
 languages

-run by giving command -
                   $ rails server -b $IP -p $PORT           #use 'rails server' if running locally

-Heroku app starts with a blank repository – it has no branches and no code. So the first time we deploy, we’ll need to specify a remote branch to push to. 

-The first push is done by giving command:
                   $ git push heroku master

-This will push your code to the heroku remote, created earlier.Use this whenever you want to deploy the latest code committed in Git to Heroku.

-During the start of your first build, Initializing repository will be displayed while your app’s repository is created on Heroku.

-On subsequent builds, Fetching repository will be displayed while your app’s repository is fetched and prepared to accept your push.

-Branches pushed to Heroku other than master will be ignored by this command.

-If you’re working out of another branch locally, you can either merge to master before pushing, or specify that you want to push your local branch to a remote master. 

-To push a branch other than master, use this syntax:
                   $ git push heroku yourbranch:master

email: shivanjali.khare@gmail.com