Android Maven Eclipse Starter Project
=============
This project should be able to act as a springboard for your android projects that require:

* Android
* Maven 
* Eclipse
* [Spring Android](http://projects.spring.io/spring-android/)

## Needed Eclipse Plugins
* [Android SDK + ADT Plugin](http://developer.android.com/sdk/index.html)
* [m2e](http://www.eclipse.org/m2e/download/)
* [m2e-android](https://github.com/rgladwell/m2e-android) ([Eclipse Marketplace](http://marketplace.eclipse.org/content/android-configurator-m2e#.UxoO1PldUrU) or [Update Site](http://rgladwell.github.com/m2e-android/updates/))

## Reference:
* [A Setup Guide](http://www.karlmonaghan.com/2013/03/28/eclipse-adt-maven-m2e-android-connector-setup/)
* [The Android Maven Plugin](https://code.google.com/p/maven-android-plugin/wiki/GettingStarted)

```sh
$ mvn clean package android:deploy android:run
```