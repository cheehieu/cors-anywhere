Adapted from [Heroku Getting Started](https://devcenter.heroku.com/articles/getting-started-with-nodejs?singlepage=true)

```
# Create app
heroku create nifty-cors

# Deploy code
npm install
git push heroku master

# View logs on Papertrail addon
heroku addons:create papertrail
heroku addons:open papertrail

# Set whitelist and rate limit as config vars
heroku config:set CORSANYWHERE_WHITELIST=https://cheehieu.github.io,http://cheehieu.github.io,https://niftyhedgehog.com,http://niftyhedgehog.com
```

