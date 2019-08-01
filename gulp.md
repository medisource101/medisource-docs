# GULP

## Prerequisite 
1. NodeJS - https://tecadmin.net/install-latest-nodejs-npm-on-ubuntu/

## Installation

1. **Install gulp globally**
    > npm install -g gulp


## How To Execute Gulp Task

> NOTE: You must be on the directory where your **gulpfile.js** is located 

Command

    gulp [options]

## Options
> Options are optional

| Option | Description |
|--------|-------------|
|`states`|This will minify js & css from API jsRoutes or angular states
|`main`  |This will minify js & css from index/index.volt
|`login` |This will minify js & css from login/index.volt
|none    |Default. Gulp will execute all the options `[states, main, login]`


Example command with option
    
    gulp states
    gulp main
    gulp login

