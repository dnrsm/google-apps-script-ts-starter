# Installation
```
$ npm i
```

# Usage

## clasp
```
# global install
$ npm i @google/clasp -g

# login
$ clasp login

# if cloning a project from gas 
$ clasp clone [scriptId of .clasp.json]

# deploy
$ clasp push

# Open the clasp project
$ clasp open
```

If you don't have Google Apps Script API turned on here, you probably won't be able to log in
https://script.google.com/home/usersettings

## npm-scripts
```
# code format
$ npm run lintfix

# deploy
$ npm run deploy
```