[![pub package](https://img.shields.io/pub/v/zekfad_lints.svg)](https://pub.dev/packages/zekfad_lints)

This package contains a set of lints for [Flutter](https://flutter.dev/) apps, packages, plugins and pure [Dart](https://dart.dev/) apps and packages.

This package is built on top of Flutter's `flutter.yaml` set of lints from
[package:flutter_lints](https://pub.dev/packages/flutter_lints) and Dart's `recommended.yaml` set of lints from
[package:lints](https://pub.dev/packages/lints).

## Usage

1. Depend on this package as a **dev_dependency** by running
  `flutter pub add --dev zekfad_lints`.
2. Create an `analysis_options.yaml` file at the root of the package (alongside
   the `pubspec.yaml` file) and `include: package:zekfad_lints/flutter.yaml` for
   flutter or `include: package:zekfad_lints/dart.yaml` for dart from it.

Example `analysis_options.yaml` file for flutter project:

```yaml
include: package:zekfad_lints/flutter.yaml
```

Example `analysis_options.yaml` file for dart project:

```yaml
include: package:zekfad_lints/dart.yaml
```
