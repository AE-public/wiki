# Android APK installation for OFT-XXW01

Here is the process to install apk file to Android in Windows environment.  
1. Please download Oracle JDK from [here](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)  
![jdk.jpg](https://github.com/Avalue-AE/wiki/blob/master/images/Android-APK-installation-for-OFT-PC/jdk.jpg?raw=true)  

2. Please download Android SDK from [here](http://developer.android.com/sdk/index.html#downloads) and install it.
![android_sdk.jpg](https://github.com/Avalue-AE/wiki/blob/master/images/Android-APK-installation-for-OFT-PC/android_sdk.jpg?raw=true)  
  
3. Once you finish Android SDK installation, it will run Android SDK manager automatically. Install packages in Android SDK manager.  
![android_sdk_tools_setup_complete.jpg](https://github.com/Avalue-AE/wiki/blob/master/images/Android-APK-installation-for-OFT-PC/android_sdk_tools_setup_complete.jpg?raw=true)
![android_sdk_manager.jpg](https://github.com/Avalue-AE/wiki/blob/master/images/Android-APK-installation-for-OFT-PC/android_sdk_manager.jpg?raw=true)  
![android_sdk_manager_2.jpg](https://github.com/Avalue-AE/wiki/blob/master/images/Android-APK-installation-for-OFT-PC/android_sdk_manager_2.jpg?raw=true)  
![android_sdk_manager_3.jpg](https://github.com/Avalue-AE/wiki/blob/master/images/Android-APK-installation-for-OFT-PC/android_sdk_manager_3.jpg?raw=true)  
  
Note: If you faced difficulty fetching package from google, check the box below.  
![android_sdk_manager-1.jpg](https://github.com/Avalue-AE/wiki/blob/master/images/Android-APK-installation-for-OFT-PC/android_sdk_manager-1.jpg?raw=true)  
![android_sdk_manager-2.jpg](https://github.com/Avalue-AE/wiki/blob/master/images/Android-APK-installation-for-OFT-PC/android_sdk_manager-2.jpg?raw=true)  
  
4. Please refer to this [link](https://01.org/zh/android-ia/downloads/intel-platform-flash-tool-lite?langredirect=1) to install **Intel® Android USB Drivers**
5. Now we have to run adb.exe to connect with Android. Normally you will find it in C:\Program Fils x86\Android\android-sdk\platform-tools.  
6. You will have to put apk file in platform-tools folder.  Download Android file manager from [無連結]() and place it in the same folder of adb.exe  
7. Please remember to enable Android developer mode by click "Setting=>About tablet => Build number" several times in Android   
8. Please enable USB debug mode by click "Setting=>Developer options=>USB debugging"  
9. Run command below in command prompt  
```
adb install xxx.apk
```
![adb_install.jpg](https://github.com/Avalue-AE/wiki/blob/master/images/Android-APK-installation-for-OFT-PC/adb_install.jpg?raw=true)  

10. Once you finish Android file manager installation, you can install any apk file by USB disk on OFT-XXW01.  