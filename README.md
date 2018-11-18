# Jobbo

Meet Jobo A bot built on botpress - goal is to create a recruiting and job platform, without the bias that comes with the recruiting process.

[Admin back end](https://jobo.herokuapp.com)

[Chat bot](https://jobo.herokuapp.com/lite/?m=platform-webchat&v=fullscreen) 
Demo password: hello123

#Todo 

- [ ] Add new content for the bot
- [ ] Implement flow for the bot
- [ ] Setup new skills


# Getting Started with this Template

# Clone this repo
```git clone https://github.com/Mosh-Media/Jobo.git```

# using npm
```npm install```

# using yarn
```yarn install```

# Heroku Deployment
```git push heroku master```


#Configure app password 
```heroku config:set BOTPRESS_PASSWORD=hello123```

# Get a free Postgres database
```heroku addons:create heroku-postgresql```

# Tell Botpress to use Postgres
```heroku config:set DATABASE=postgres```

# Useful Links

[Admin back end](https://localhost:3000/)

[Chat bot](https://localhost:3000/lite/?m=platform-webchat&v=fullscreen)

[Botpress getting started](https://botpress.io/getting-started)