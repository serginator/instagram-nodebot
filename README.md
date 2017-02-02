# Instagram nodebot

This is a bot for instaliking stuff

## contribute

Make a fork of the repo and clone your fork

`git clone git@github.com:<your-username>/instagram-nodebot`

Install dependencies

`npm install`

Make your changes and open a pull request to main repo.

Try to follow `cz-conventional-changelog` guides

## configure file

Edit `src/config.js` file:

```
module.exports = {
  access_token: 'HEREYOURTOKEN'
};
```

## configure list tags to like

Edit `src/helpers/strings.js` with the tags you want to instalike
```
module.exports = [
    'cat',
    'kitty',
    'instacat',
    'catsofinstagram'
]
```

## running the bot

`npm start`
