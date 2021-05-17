# Setting up manually:
1. Go to personal dashboard of Heroku
2. Click new -> create new app
3. Give app a name. Hit deploy. 
4. Select the app (usually opens up automatically)
5. Select the Deploy tag. 
6. Clone this repo should be cloned and install Heroku CLI and sign in  https://devcenter.heroku.com/articles/heroku-cli
7. cd to cloned folder. 
8. change to heroku branch with the command  `heroku git:remote -a <Your App Name Here>`
9. Push to Heroku `git push heroku master` (Default branch name is master)
10. Let the cli upload it and build. If any issues check it through overview tab of the dashboard (web dashboard of your heroku app)
11. After compilation and deployment is finished, go to settings tab.
12. Go to Config Vars seciton and hit the Reveal config Vars.
13. As Keys add LOGIN and PASSWORD. Give values your prefer. 
14. Hit the Open App in your dashboard. 
15. It will ask for LOGIN and PASSWORD. Then it will show a message 'bandwidth-hero-proxy'
16. Copy the URL in browser. This will be needed to next step. 
17. Add extension to your browser. Configure extension and paste the url under 'URL'. All set.


# Troubleshoot:
If this doen't work update sharp and node engine versions in package.json.
right now they are:
`"node": "^15.4.0"
"sharp": "^0.28.1"`
Change to a compatible (or current version) and do a npm install. `add` and `push`. 


All thanks to Bandwidth Hero team. Refer their official docs here: https://github.com/ayastreb/bandwidth-hero-proxy 
