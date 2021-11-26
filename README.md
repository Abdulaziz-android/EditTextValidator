# EditTextValidator

![mygif](https://user-images.githubusercontent.com/66155702/143535214-b67ce27c-a794-4fd8-b086-bafdee66e841.gif)

How to
To get a Git project into your build:

Step 1. Add the JitPack repository to your build file

gradle
maven
sbt
leiningen
Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.Abdulaziz-android:EditTextValidator:1.2'
	}
