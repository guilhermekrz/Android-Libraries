# Android-Libraries
[Check for dependencies new versions](https://nullpointer.wtf/tools/keeping-your-dependencies-up-to-date/)

## Where to find
* [Android-Arsenal](http://android-arsenal.com/)
* [CommonsWare](https://github.com/commonsguy?tab=repositories)
* [Square](https://github.com/square)
* [Android Performance](https://github.com/Juude/awesome-android-performance)
* [Material-Animations](https://github.com/lgvalle/Material-Animations)
* [Feature Graphic Generator](http://www.norio.be/android-feature-graphic-generator/)

## [Plugins](https://www.reddit.com/r/androiddev/comments/3ktqyb/what_are_some_of_your_musthave_plugins_for/)
* [Configuring Android Studio](https://medium.com/@dmytrodanylyk/configuring-android-studio-4aa4f54f1153#.wg1ssmq4i)
* [Automatic save Android Studio settings](https://github.com/develar/settings-repository)
* Do you use Eclipse? No problem, you can find useful info [here](https://developer.android.com/sdk/index.html)
* [CodeGlance](https://plugins.jetbrains.com/plugin/7275?pr=) - Embeds a code minimap similar to the one found in Sublime into the editor pane
* [Folding](https://github.com/dmytrodanylyk/folding-plugin) - It can display your files as a group of different folders in project structure view
* [Genymotion](https://www.genymotion.com/#!/) - Android emulator
* [KeyPromoter](https://plugins.jetbrains.com/plugin/1003) - Shows to user how easy he can make same action using only keyboard(menus and toolbar button mouse clicks initiates shortcut display) 

## Tutorials
* [Build a Material Design App with the Android Design Support Library](http://www.code-labs.io/codelabs/material-design-style/index.html#0)
* [Mastering the Coordinator Layout](http://saulmm.github.io/mastering-coordinator/)
* 

## Submit to Play Store
* [AppScreenshotMaker](http://appscreenshotmaker.com/)

### Android
```
compile 'com.android.support:appcompat-v7:22.2.0'
compile 'com.android.support:support-v4:22.2.0'
compile 'com.android.support:design:22.2.0'
compile 'com.android.support:recyclerview-v7:22.2.0'
```

### Camera
* [CWAC-Camera](https://github.com/commonsguy/cwac-camera) - Deprecated (use cwac-camera2 instead - but it is still missing some features)

### Crashes
* [Crashlytics]()
```
//noinspection GradleDynamicVersion
compile 'com.crashlytics.android:crashlytics:1.+'
```

### Database
* [ORMLite](http://ormlite.com/javadoc/ormlite-core/doc-files/ormlite_1.html#Downloading) - Currently we need to use the snapshot version, there is no Gradle version with the correct Loaderv4

### Debug
* [LeakCanary]()
```
debugCompile 'com.squareup.leakcanary:leakcanary-android:1.3.1'
releaseCompile 'com.squareup.leakcanary:leakcanary-android-no-op:1.3.1'
```
* [LayoutCast](https://github.com/mmin18/LayoutCast) - Cast android code and resource changes to the running application through ADB.

### Donations
* [Donations](https://github.com/sufficientlysecure/donations)
```
compile 'org.sufficientlysecure:donations:2.3'
```

### Form validator
* [Saripaar](https://github.com/ragunathjawahar/android-saripaar)

### Images
* [Universal-Image-Loader](https://github.com/nostra13/Android-Universal-Image-Loader)
```
compile 'com.nostra13.universalimageloader:universal-image-loader:1.9.4'
```
* [CircleImageView]()
```
compile 'de.hdodenhof:circleimageview:1.3.0'
```

### JSON
* [Jackson](https://github.com/FasterXML/jackson)
* [GSON](https://github.com/google/gson) - Seems heavier and slower than Jackson

### Network
* [OKHTTP](compile 'com.squareup.okhttp:okhttp:2.4.0') - If included, Retrofit uses it automatically. It seems faster than other alternatives.
* [Retrofit](http://square.github.io/retrofit/)
```
compile 'com.squareup.retrofit:retrofit:1.9.0'
```
* [Volley](http://arnab.ch/blog/2013/08/asynchronous-http-requests-in-android-using-volley/)
```
compile 'com.mcxiaoke.volley:library:1.0.+'
```
* [Reactive Network](https://github.com/pwittchen/ReactiveNetwork) - Detect when network state changes using RXAndroid

### Time
* [JodaTime]()
```
compile 'joda-time:joda-time:2.8.1'
```
* [PrettyTime](http://www.ocpsoft.org/prettytime/)
```
compile 'org.ocpsoft.prettytime:prettytime:3.2.5.Final'
```

### Utils
* [ButterKnife](http://jakewharton.github.io/butterknife/)
```
compile 'com.jakewharton:butterknife:6.1.0'
```
* [Dagger 2](http://google.github.io/dagger/) - Try to use it!
* [EventBus]()
```
compile 'de.greenrobot:eventbus:2.4.0'
```
* [MaterialShowcaseView]() - First use overlays
```
compile 'com.github.deano2390:MaterialShowcaseView:1.0.2'
```
* [RXAndroid]()
```
compile 'io.reactivex:rxandroid:1.0.0'
```

### Views
* [Auto scale text view](https://stackoverflow.com/questions/5033012/auto-scale-textview-text-to-fit-within-bounds)
* [CWAC-Merge](https://github.com/commonsguy/cwac-merge) - Combining rows (Static + Dynamic)
* [PagerSlidingTabStrip](https://github.com/astuetz/PagerSlidingTabStrip)
```
compile 'com.astuetz:pagerslidingtabstrip:1.0.1'
```
* [RoundedImageView]()
```
compile 'com.makeramen:roundedimageview:1.3.0'
```
