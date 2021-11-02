# Heroku basic commands to deploy a website

# React / Node

## Package.json

Add the following script to the package.json of the node js app:

```
"heroku-postbuild": "NPM_CONFIG_PRODUCTION=false npm install --prefix client && npm run build --prefix client"
```

---

# Heroku

## Log In

```
heroku login
```

## Create a new app

```
heroku create
```

## Deploy:

- You have to push to heroku. So you have to add it as a remote repo. Use the command given by heroku going to the "Deploy" section on the created app

- Once it is added as a remote repo, just do: git push heroku main

## Open the deployed app

```
heroku open
```
