# Phaser Capacitor Starter

![Phaser avatar studying](./src/assets/img/study.png)

Minimal starter project for Phaser with Capacitor capabilites.

## Install
- Clone this repository git clone https://github.com/Alvaro237/phaser-capacitor-starter.git
- `cd phaser-capacitor-starter`
- `npm install`

## Development
- `npm start`
- Open `http://localhost:8080`

## Build
- `npm run build`
- All game files will be in `/dist`

## Android or iOS build
- `npm run build` al least once
- `npx cap init`
- `npx cap add android | ios` more info about Capacitor https://capacitor.ionicframework.com/docs/
- `npx cap copy android | ios`
- `npx cap open android | ios`
- Compile with Android Studio or Xcode

## Shortcut
- `npm run capacitor-build` will make `npx cap copy android` and `npx cap open android` if you want to target iOS you have to change it.


