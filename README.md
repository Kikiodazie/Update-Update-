
# Update-Update

DESCRIPTION

Update! Update!!!: A news App with an Authentication system to (create, login and logout users).

View it Deployed to Heroku http://updatebykiki.herokuapp.com/

I built this to Propely undestand authentication,authorization(Defining roles) and deploying to the cloud with Heroku.
Using few ruby "Gems"

TABLE OF CONTENTS

1. Getting Started
2. Cloning this Repo
3. Authentication
4. Authorization
5. Version Control with Git
6. Deploying to Heroku.

NB: This README.md file will be generalized and appropraite links will be provided. 



GETTING STARTED

  Rails is popularly known for building web applications, If you aren't familar with rails yet check this out http://guides.rubyonrails.org/getting_started.html to get started or else let's get on with it.
  
  ruby version ~'2.5.5'
  
  rails Version ~> 5.2.3'
  
  
CLONING THIS REPO

In other to clone this repo and get started locally, check out this github guide https://help.github.com/en/articles/cloning-a-repository

AUTHENTICATION

•	The authentication system is made up of sign up, log in, log out functionality.
•	The password_digest column and has_secure_password method are provided by bcrypt to store passwords securely.
•	A session begins when a users logs in, and ends when a user logs out.
•	The current_user method allow us to access the current user; require_user redirects to the root of the app if there is no such user.
•	Before actions act as filters. They call methods before executing controller actions.


AUTHORIZATION

•	The role column in the User model specifies a users’ role
•	A method like def admin? and def editor? is created for business logic
•	The require_editor and require_adminmethods redirect to () if the current user is not an editor or admin.
•	The before action acts a filter, calling require_editor or require_admin before excuting controller actions.
•	The current_user method can be used in the views to display links based on the signed in user’s role.

VERSION CONTROL WITH GIT

Put your app under version control with Git. Then push it up to GitHub. Check out the instructions here:https://www.codecademy.com/articles/push-to-github

DEPLOYING APP TO HEROKU

Deploy your app to Heroku. Check out the instructions here: https://www.codecademy.com/articles/deploy-rails-to-heroku. if you are using windows OS https://devcenter.heroku.com/articles/getting-started-with-jruby


I hope this was very helpful.


