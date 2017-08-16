# ssh-buildpack
Heroku Buildpack for setting up the ssh environment

Config file
```bash
```

Setup
```bash
heroku config:set SSH_KEY="`cat id_rsa`"
heroku config:set SSH_CONFIG="`cat config`"
heroku buildpacks:add -i 1 https://github.com/renan-ti/ssh-buildpack.git 

```
