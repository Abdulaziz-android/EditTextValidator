# EditTextValidator
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
	        implementation 'com.github.Abdulaziz-android:EditTextValidator:1.0'
	}
Share this release:

TweetLink
That's it! The first time you request a project JitPack checks out the code, builds it and serves the build artifacts (jar, aar).

If the project doesn't have any GitHub Releases you can use the short commit hash or 'master-SNAPSHOT' as the version.
![tenor-google](https://user-images.githubusercontent.com/66155702/143531958-acc81084-1ac4-409a-b452-98f69cbb8678.gif)

