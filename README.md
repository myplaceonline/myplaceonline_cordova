# myplaceonline_cordova

```
export ANDROID_SDK_ROOT=$HOME/Android/Sdk/
export JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk/
export PATH=${ANDROID_SDK_ROOT}/emulator/:${ANDROID_SDK_ROOT}/platform-tools/:${ANDROID_SDK_ROOT}/tools/:${JAVA_HOME}/bin/:/work/gradle/gradle-6.9.1/bin:${PATH}
cordova build android
emulator @Pixel_2_API_30
# wait for emulator start and unlock it
cordova emulate android
```

```
adb install platforms/android/app/build/outputs/apk/debug/app-debug.apk
adb logcat
```

https://github.com/apache/cordova-android/issues/1375
https://github.com/apache/cordova-plugin-inappbrowser/issues/918

## Android production build

```
cordova build android --release -- --keystore=../lib/keys/myplaceonline_android_phonegap.keystore '--storePassword=' --alias=myplaceonline_alias '--password=' --packageType=bundle
```

## Resources

* <https://cordova.apache.org/docs/en/latest/guide/cli/index.html>
* <https://cordova.apache.org/plugins/>
