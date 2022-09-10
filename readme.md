## How to create and deploy service

open: ```https://dashboard.heroku.com/new-app```

create a new app

then pass to Cli:

```heroku stack:set container --app {app-name}```

If your repo is empty just do git push

then connect your heroku app with github 

```https://dashboard.heroku.com/apps/{heroku-app-name}/deploy/github```

select ```Enable Automatic Deploys```

