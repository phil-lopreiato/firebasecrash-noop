# Firebase Crash Noop
![](https://jitpack.io/v/phil-lopreiato/firebasecrash-noop.svg)

A simple immitation `FirebaseCrash` file that does nothing, allowing you to only compile the real library into release builds.

Add the JitPack maven reopository:
```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```

Add the library:
```
dependencies {
	        debugCompile 'com.github.phil-lopreiato:firebasecrash-noop:v0.1'
}
```
