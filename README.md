# moddedBear's Mastodon for Android Fork

## Changes from upstream
- Added an option to hide post stats (i.e. reply counts above one, favorite counts, boost counts).
- Renamed reblogs to boosts
- Changed package name

To build, switch to a "vx.x.x-wellbeing" branch and follow the original build instructions.

Original readme below.

---

# Mastodon for Android
[![Crowdin](https://badges.crowdin.net/mastodon-for-android/localized.svg)](https://crowdin.com/project/mastodon-for-android)

<a href="https://play.google.com/store/apps/details?id=org.joinmastodon.android"><img src="img/google-play-badge.png" height="50"></a>

This is the repository for the official Android app for Mastodon.

Learn more about this app in the [blog post](https://blog.joinmastodon.org/2022/02/official-mastodon-for-android-app-is-coming-soon/).

## Building

As this app is using Java 17 features, you need JDK 17 or newer to build it. Other than that, everything is pretty standard. You can either import the project into Android Studio and build it from there, or run the following command in the project directory:

```
./gradlew assembleRelease
```

## License

This project is released under the [GPL-3 License](./LICENSE).