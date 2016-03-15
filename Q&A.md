__Q: BABEL TransformError__

A: `rm node_modules/react-deep-force-update/.babelrc`

__Q: [Android] FAILURE: Build failed with an exception.__

A: `my-project/android/build.gradle` (version <= 1.2.3)

```
// Top-level build file where you can add configuration options common to all sub-projects/modules.

buildscript {
    repositories {
        jcenter()
    }
    dependencies {
        classpath 'com.android.tools.build:gradle:1.2.3'

        // NOTE: Do not place your application dependencies here; they belong
        // in the individual module build.gradle files
    }
}

allprojects {
    repositories {
        mavenLocal()
        jcenter()
    }
}
```

__Q: [Android] Unable to download JS bundle__

A: `adb reverse tcp:8081 tcp:8081`
