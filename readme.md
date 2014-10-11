Herring Cove
============

first of all, this is a fork of [this repo](https://github.com/spf13/herring-cove)

I added 2 simple things to this theme Hugo theme.

1. Profile picture parameter.
2. Links in the menus are genereted through params in the config

Below an example of the yaml config
```yaml
params:
  ProfilePicture: "https://avatars0.githubusercontent.com/u/3998327?v=2&s=460"
  links:
    Home : "/"
    Blog: "/blog/"
    About: "/about/"
```

