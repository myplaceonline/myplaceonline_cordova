# myplaceonline_cordova

```
export ANDROID_SDK_ROOT=$HOME/Android/Sdk/
export JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-1.8.0.302.b08-2.fc34.x86_64/
export PATH=${ANDROID_SDK_ROOT}/emulator/:${ANDROID_SDK_ROOT}/platform-tools/:${ANDROID_SDK_ROOT}/tools/:${JAVA_HOME}/bin/:/work/gradle/gradle-6.9.1/bin:${PATH}
cordova build android
emulator @Pixel_2_API_30
# wait for emulator start and unlock it
cordova emulate android
```

## Resources

* <https://cordova.apache.org/docs/en/latest/guide/cli/index.html>
* <https://cordova.apache.org/plugins/>
