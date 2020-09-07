# Android Simple Code Library

This library simplifies code that is a must-have but annoying to write down.

### Download

Add it in your root build.gradle at repositories

```
allprojects {
    repositories {
        ...
        maven { url "https://jitpack.io" }
        ...
    }
}
```

Add it in your app build.gradle at dependencies

```
dependencies {
    implementation 'com.github.nks0614:DGSW_Project:1.1.1'
}
```

### Use

Intent Activity Code

```kotlin
simIntent(MainActivity::class.java) //if you back, app finish

simIntentNoFinish(MainActivity::class.java) //if you back, go first stack Activity
```

Toast Activity Code

```kotlin
simToastShort("TEXT") // duration is Toast.LENGTH_SHORT

simToastLong("TEXT") // duration is Toast.LENGTH_LONG
```

### P.s
This is Just Study and School Project.
If you want to use this library, you can use it.
But quality and stability can't be guaranteed.

Thank you
