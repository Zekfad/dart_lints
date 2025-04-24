[![pub package](https://img.shields.io/pub/v/zekfad_lints.svg)](https://pub.dev/packages/zekfad_lints)

This package contains a set of lints for [Flutter](https://flutter.dev/) and 
[Dart](https://dart.dev/) apps, packages, plugins.

This package is built on top of Flutter's `flutter.yaml` set of lints from
[package:flutter_lints](https://pub.dev/packages/flutter_lints) and Dart's
`recommended.yaml` set of lints from [package:lints](https://pub.dev/packages/lints).

## Usage

1. Depend on this package as a **dev_dependency** by running
  `flutter pub add --dev zekfad_lints`.
2. Create `analysis_options.yaml` file at the root of the package (alongside
  the `pubspec.yaml` file) and include desired config.

## Configs

Drop-in replacements for Flutter's or Dart's default config (preference is given
to the usage of inferred types where it's possible):

* `package:zekfad_lints/recommended.yaml` - Same as 
  `package:zekfad_lints/untyped/dart.yaml`.
* `package:zekfad_lints/flutter.yaml` - Same as 
  `package:zekfad_lints/untyped/flutter.yaml`.

You may use additional configs for fine tuning to your preference:

* `package:zekfad_lints/base/dart.yaml` - Base config for **Dart** projects.
* `package:zekfad_lints/typed/dart.yaml` - Config for **Dart** projects with
  strict requirement for **always specifying types**.
* `package:zekfad_lints/untyped/dart.yaml` - Config for **Dart** projects with
  strict requirement for **omitting unnecessary types**

* `package:zekfad_lints/base/flutter.yaml` - Base config for **Flutter** projects.
* `package:zekfad_lints/typed/flutter.yaml` - Config for **Flutter** projects with
  strict requirement for **always specifying types**.
* `package:zekfad_lints/untyped/flutter.yaml` - Config for **Flutter** projects
  with strict requirement for **omitting unnecessary types**.

* `package:zekfad_lints/lib.yaml` - Config with some rules reverted to core
  lints, useful for public for libraries.
