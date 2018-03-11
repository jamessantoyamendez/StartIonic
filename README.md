# Ionic Project

## 1. Description

This mini-workshop covers all the core concepts and technical knowledge required to 

confidently create a Ionic project. We'll cover different topics ranging from: Creation of Ionic application, Splash Screen, Build app, etc.

## 2. Environment Setup

Steps | Install             | Version           |
:----------:|-------------------|--------------------|
1           | **sudo apt-get install nodejs**           | 8.10.0    |
2           | **npm install -g @angular/cli**              | 5.6.0    |
3           | **npm install -g ionic cordova** | 1.6.1        |
4           | **npm install -g ionic**    | 8.0.0        |
5           | **npm install -g typescript**  | 3.19.1    |
6           | **sudo apt-get install npm**           | 2.4.1    |

## Verify Installation:
- **cordova -v**
- **ionic -v**
- **node -v**
- **ng -v**
- **tsc -v -> typescript**


## Add platform to build app
- **ionic cordova platform add ios**
- **ionic cordova platform add android**

**ionic cordova build ios** -> Build (prepare + compile) an Ionic project for a given platform
**ionic cordova emulate ios** -> Emulate an Ionic project on a simulator or emulator

- **ionic start helloWorld blank** -> Create app ionic
- **cd helloWorld** 

- **ionic serve** -> run project

## 3. Resources

- [Commands cli Ionic](https://ionicframework.com/docs/cli/commands.html)
- [Installation](https://ionicframework.com/docs/intro/installation/)
- [Concepts](https://ionicframework.com/docs/intro/concepts/)

