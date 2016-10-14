__Q: BABEL TransformError__

A: `rm node_modules/react-deep-force-update/.babelrc`

---

__Q: [Android] FAILURE: Build failed with an exception.__

A: Try downgrading your Gradle version to _1.2.3_ in `android/build.gradle`.

---

__Q: [Android] Unable to download JS bundle__

A: `adb reverse tcp:8081 tcp:8081`

---

__Q: [Android] UnsupportedMethodException__

```
Unsupported method: AndroidProject.getPluginGeneration().
The version of Gradle you connect to does not support that method.
To resolve the problem you can change/upgrade the target version of Gradle you connect to.
Alternatively, you can ignore this exception and read other information
```

A: disabled `Instant Run`
