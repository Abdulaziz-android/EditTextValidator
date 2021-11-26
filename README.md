# EditTextValidator
How to
To get a Git project into your build:

![mygif](https://user-images.githubusercontent.com/66155702/143535040-9a383c16-957b-4e07-a15e-b8e8b85b2a1c.gif)


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
	        implementation 'com.github.Abdulaziz-android:EditTextValidator:1.0'
	}

