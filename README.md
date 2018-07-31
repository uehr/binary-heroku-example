# binary-heroku-example

Example run binary on heroku

Usage
-----

```shell

# Get this example app
git clone git://github.com/uehr/binary-heroku-example.git
cd binary-heroku-example

# Create a heroku app
heroku create --stack cedar --buildpack https://github.com/uehr/heroku-buildpack-bin.git

# Deploy to heroku
git push heroku master

# Open heroku app url
heroku open
```