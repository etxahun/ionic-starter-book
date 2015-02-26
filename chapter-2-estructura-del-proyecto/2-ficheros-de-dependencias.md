## package.json
Fichero de dependencias auxiliares (Grunt Tasks, Cordova Plugins...)

```javascript
{
 "name": "PruebaCordova",
 "version": "0.0.1",
 "private": true,
 "dependencies": {},
 "devDependencies": {
   "grunt": "~0.4.1",
   "grunt-autoprefixer": "~0.4.0",
   "grunt-wiredep": "^1.7.0",
   "ionic": "^1.2.7"
 },
 "engines": {
   "node": ">=0.10.0"
 },
 "scripts": {
   "test": "grunt test"
 },
 "cordovaPlugins": [
   "https://github.com/driftyco/ionic-plugins-keyboard.git",
   "org.apache.cordova.splashscreen",
   "org.apache.cordova.network-information",
   "org.apache.cordova.inappbrowser",
   "com.ionic.keyboard"
 ]
}
```

## bower.json
Fichero de dependencias JavaScript

```javascript
{
 "name": "PruebaCordova",
 "version": "0.0.1",
 "dependencies": {
   "ionic": "v1.0.0-beta.13",
   "underscore": "~1.7.0",
   "ionicons": "~2.0.1",
   "angular-omni-bar": "https://github.com/isteven/angular-omni-bar.git#master",
   "ngCordova": "~0.1.11-alpha"
 },
 "devDependencies": {
   "angular-mocks": "~1.2.17",
   "angular-scenario": "~1.2.17"
 }
}
```
