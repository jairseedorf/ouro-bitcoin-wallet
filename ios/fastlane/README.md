fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios beta

```sh
[bundle exec] fastlane ios beta
```

Push a new beta build to TestFlight

### ios browserstack

```sh
[bundle exec] fastlane ios browserstack
```

End to end testing on browserstack

### ios increment

```sh
[bundle exec] fastlane ios increment
```

increment path version

### ios build_ipa

```sh
[bundle exec] fastlane ios build_ipa
```

build ipa

### ios build_e2e

```sh
[bundle exec] fastlane ios build_e2e
```

Build for end to end tests

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
