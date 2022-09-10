## How to create and deploy service

open: ```https://dashboard.heroku.com/new-app```

create a new app

then put to Cli:

```heroku stack:set container --app {app-name}```

If your repo is empty just do git push

then connect your heroku app with github 

```https://dashboard.heroku.com/apps/{heroku-app-name}/deploy/github```

select ```Enable Automatic Deploys```

the put to Cli:

```heroku labs:enable --app=heroku-docker-deploy runtime-new-layer-extract```

the redeploy app

```https://dashboard.heroku.com/apps/{heroku-app-name}/deploy/github```


## other usefull commands

restart heroku build:

```heroku builds:cancel --app {heroku-app-name}```

