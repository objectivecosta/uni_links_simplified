## [0.6.0] - 2022-01-06

* Updated to depend on plugin_platform_interface 2.1.0.
* Updated plugin platform interface to use a non`-const` token. This is marked as a breaking change because it can cause an assertion failure if implementations use `implements` rather than `extends`, but hopefully there aren't any of those.

## [0.5.0] - 2020-12-28

**Breaking changes**  
Due to the migration to null safety, some APIs have changed. These changes mainly involve functions changing into getters, and types becoming explicitly nullable.  
The changes to the example package are a good example of how to upgrade to this version.
* Support null safety.
* Migrate to the federated plugin architecture, paving the way for Web support in the future.

## [0.4.0] - 2020-05-10

* Reduce iOS compiler warnings #42 (@ened)
* Fix UniLinks Plugin for Flutter 1.12.13 #55 (@markathomas)

## [0.2.1] - 2019-09-30

* Updated iOS example project project files.
* Added NS_NONNULL macro to iOS plugin header to reduce compiler warnings.

## [0.2.0] - 2019-03-10

**Breaking change**
  Migrate from the deprecated original Android Support Library to AndroidX. This shouldn't result in any functional changes, but it requires any Android apps using this plugin to [also migrate](https://developer.android.com/jetpack/androidx/migrate) if they're using the original support library.

* [Android] Update to AndroidX. (@bbedward)


## [0.1.4] - 2018-10-16

* [Android] Don't process links when launched in background. (@wkornewald)


## [0.1.3] - 2018-09-08

* No code changes.
* Added section in the README about Swift-enabled apps.
* Added section in the README about tooling for invoking links from the cli.


## [0.1.2] - 2018-07-30

* Fixed lost initialLink on iOS launch via Universal Link. (@wkornewald)


## [0.1.1] - 2018-05-31

* No code changes. Pushed to pub.dartlang.org with an untracked file that had to
  be manually removed.


## [0.1.0] - 2018-05-31

* Initial release.
