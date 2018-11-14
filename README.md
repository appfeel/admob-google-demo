This is a demo project for [Cordova and Phonegap AdMob plugin](https://github.com/appfeel/admob-google-cordova).

# Instructions:

- [Download zip](https://github.com/appfeel/admob-google-demo.git/archive/master.zip) project or clone it via git CLI:
```
git clone https://github.com/appfeel/admob-google-demo.git AdmobAdsTest
```

- Add cordova-admob plugin to the project:
````
cd AdmobAdsTest
cordova plugin add cordova-admob
```

- Add platforms to the project:
```
cordova platform add ios android
```

- Emulate the application:
````
cordova emulate android
cordova emulate ios
````