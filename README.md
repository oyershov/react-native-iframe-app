# React Native iFrame App
## Make any website a mobile native app
   
React native (RN) application to build ios / android app using an existing website.
This app uses [expo](https://docs.expo.io/)
   
Example:
   
<img src="example/S2.png?raw=true" width="250" alt="S2 website">
   
## Install dependencies

```bash
$ yarn install
```

## Run in developement mode

```bash
$ yarn start
```
This command starts RN project using Metro bundler and allows to choose on which simulator app should run.   
   
OR run app using different specified simulator:   

```bash
$ yarn run ios
$ yarn run android
$ yarn run web
```

## Fix problems in the code

Use [eslint](https://eslint.org/) to fix code   

```bash
$ yarn run lint
```
   
## Fix code formatting

Use [prettier](https://prettier.io/docs/en/index.html) to polish the code formatting   

```bash
$ yarn run prettier:write
```
   
# Build and publish
   
## Build
    
Follow this [build guide](https://docs.expo.io/distribution/building-standalone-apps/)

Run   
```bash
$ expo build:ios
```
or   
```bash
$ expo build:android
```
and _follow instructions in the terminal._   
   
**Please note**   
There are two types you can build standalone apps.   
`archive` -  if you want to publish your app to the store or distribute it with tools like TestFlight.   
**Requires developers account**    
   
`simulator` - simulator build   
   
[Read for details](https://docs.expo.io/distribution/building-standalone-apps/#if-you-choose-to-build-for-ios)      
   
**Please note x2**   
```bash
$ expo build
```
   
Without specifying platform expo automatically publishes your app (with `expo publish`).   
[Read for details](https://docs.expo.io/distribution/building-standalone-apps/#3-start-the-build)   
   
## Publish
Read the [guide](https://docs.expo.io/distribution/building-standalone-apps/#6-submit-it-to-the-appropriate-store)   
   