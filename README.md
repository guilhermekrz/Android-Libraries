# Android-Libraries

## Where to find
* [Android-Arsenal](http://android-arsenal.com/)
* [CommonsWare](https://github.com/commonsguy?tab=repositories)
* [Square](https://github.com/square)

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

### Donations
* [Donations](https://github.com/sufficientlysecure/donations)
```
compile 'org.sufficientlysecure:donations:2.3'
```

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
* [PagerSlidingTabStrip](https://github.com/astuetz/PagerSlidingTabStrip)
```
compile 'com.astuetz:pagerslidingtabstrip:1.0.1'
```
* [RoundedImageView]()
```
compile 'com.makeramen:roundedimageview:1.3.0'
```
