# Helm in Heroku

Add the helm binary to Heroku using the script provided by Helm here:

https://helm.sh/docs/intro/install/#from-script

# Add

```
heroku buildpacks:add https://github.com/bigbinary/heroku-buildpack-helm
```

# Remove
```
heroku buildpacks:remove https://github.com/bigbinary/heroku-buildpack-helm
```

