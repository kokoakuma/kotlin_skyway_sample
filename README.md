# Summary
In this repository, I am trying to rewrite the p2p videochat [sample](https://github.com/skyway/skyway-android-sdk) of SkyWay in Kotlin for my self study.

## Environment
- Windows 10
- Android Studio Electric Eel

## Issues
#### Using flatDir in build.gradle caused exception.
Template project generated `repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)` as default setting. We have to change this when defining repository setting in build.gradle.

#### Using flatDir caused warning
It might be better to use `sourceSet`.

#### getFragmentManager is deprecated
Use getSupportFragmentManager instead.

