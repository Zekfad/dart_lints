## 2.0.0

> For linter [1.30.0](https://pub.dev/packages/linter/changelog#1300)

> Requires Dart 3.0

* **BREAKING**: Changed files structure:

  This change makes it easier to setup new project, giving preference to omit
  unnecessary types where possible.

  * Base lints now in `base` folder.
  * `recommended.yaml` points to `untyped/dart.yaml`.
  * `flutter.yaml` points to `untyped/flutter.yaml`.

* Enabled `deprecated_member_use_from_same_package`
* Removed no longer available `invariant_booleans`
* Enabled `implicit_reopen` (experimental)
* Enabled `invalid_case_patterns` (experimental)
* Enabled `no_self_assignments`
* Enabled `no_wildcard_variable_uses`
* Enabled `prefer_void_to_null`
* Enabled `unsafe_html`
* Enabled `annotate_redeclares` (experimental)
* Removed deprecated `avoid_returning_null`
* Removed no longer available `enable_null_safety`
* **BREAKING**: Enabled `file_names`
* Enabled `matching_super_parameters`
* Disabled `no_leading_underscores_for_library_prefixes`
* Enabled `no_literal_bool_comparisons`
* Enabled `unnecessary_breaks`

## 1.2.0

> For linter [1.30.0](https://pub.dev/packages/linter/changelog#1300)

* Linter 1.27.0
  * Enabled `use_string_in_part_of_directives`
* Linter 1.28.0
  * Enabled `unreachable_from_main` (experimental)
* Linter 1.29.0
  * Enabled `dangling_library_doc_comments`
  * Enabled `collection_methods_unrelated_type`
  * Enabled `unnecessary_library_directive`
* Linter 1.30.0
  * Enabled `enable_null_safety`
  * Enabled `library_annotations`
## 1.1.0

> For linter [1.26.0](https://pub.dev/packages/linter/changelog#1260)

* Add `typed` and `untyped` configs

## 1.0.0

> For linter [1.26.0](https://pub.dev/packages/linter/changelog#1260)

* Initial release
