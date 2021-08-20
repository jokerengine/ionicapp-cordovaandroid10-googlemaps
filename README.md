# ionicapp-cordovaandroid10-googlemaps
Github Repo for testing a bug in the google maps plugin provided for cordova-android-10/ionic

# installation
To run the application you'll need the newest version of the ionic-cli, cordova-cli and android studio on your computer

Clone this project from git and run the following commands: 
```
npm ci
```

```
ionic cordova platform rm android
ionic cordova platform add android@10.1.0
```

You can now plug in your android device to the computer and then run
```
ionic cordova run android --device
```


