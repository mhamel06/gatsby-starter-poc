# Readme
This poc uses Gatsby themes to setup a lot of the boilerplate code
required to have a data driven, PWA, offline compatible, and React based
app. 

The theme source is located here: https://github.com/mhamel06/gatsby-theme-poc

All theme configs and files can be overridden by creating a duplicate file as seen
here: (theme-test/src/@mhamel06/gatsby-theme-events/theme.js)[theme-test/src/@mhamel06/gatsby-theme-events/theme.js]

## Install Gatsby
https://www.gatsbyjs.org/tutorial/part-zero/#using-the-gatsby-cli
```sh
npm install -g gatsby-cli
```

## Setup Starter App
```sh
# swap poc-test with project name 
gatsby new poc-test https://github.com/mhamel06/gatsby-starter-poc
cd poc-test
gatsby develop

```

## Build For Prod and Test  
```sh
gatsby build
gatsby serve

```

## Deploy to Zeit 
https://zeit.co/
```sh
gatsby build
cd public
now # Zeit cli tool
```

## Add data to data folder 

## Modify Theme

## Edit theme configs 
- 
