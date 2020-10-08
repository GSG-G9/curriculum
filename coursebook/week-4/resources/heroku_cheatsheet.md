# Heroku Cheatsheet :sparkles:
A helpful list of steps to help you deploy, set up a database (if needed), enable automatic deploys from master, and troubleshoot issues.

### Deployment Steps
- [ ] Get Heroku account (if you don't have one)
- [ ] [Download and install Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli#download-and-install)
- [ ] In the command line: `heroku login`
- [ ] Create new app using `heroku create <app-name>`
  
#### If you have a database
- [ ] Create database using `heroku addons:create heroku-postgresql:hobby-dev`
- [ ] After running this, Heroku will create a DATABASE_URL variable, which you can find in your Heroku app settings under 'Config Variables'
- [ ] Create a config.env file in your local repo using the Heroku DATABASE_URL (make sure that this is in your `.gitignore` file, because you don't want to push it to GitHub)
- [ ] Make sure that your `db_connection.js` files references this correctly (i.e. `const params = url.parse(process.env.DATABASE_URL);`, not DB_URL)
- [ ] Run `node database/db_build.js` to create your database locally (or whatever command you use to create your database)
- [ ] Connect directly to Heroku database using `heroku pg:psql`
- [ ] To see if your tables are there, run `\dt`

### Enabling automatic deploys from master

- [ ] Find your project on the Heroku webstie
- [ ] Go to deploy > deployment method > switch it from 'Hekou Git' to 'GitHub (connect to github)'
- [ ] Choose your repo, and then 
- [ ] Choose enable automatic deploys, it will update every time you push to master

### Troubleshooting Checklist
- [ ] Dynamic port binding - have you used `process.env.PORT || XXXX` rather than  a set port number?
- [ ] Specified node version in `package.json`? e.g:

    ```json
    "engines": {
        "node": "8.6.0"
    },
    ```
- [ ] Included a start script in your `package.json`? (Otherwise Heroku will look for `./index.js`)
- [ ] Have you remembered to add your environment variables into Heroku itself?
- [ ] Have you run your db build script if deploying for the first time / altered your db? e.g. `heroku run "node ./database/dbBuild.js"`
- [ ] Have you used capital letters in any of your folder names?
- [ ] Have you tried running `heroku logs` to check for errors?
