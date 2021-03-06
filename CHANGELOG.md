# Changelog - LabelledSpinner

[![Releases](https://img.shields.io/badge/LabelledSpinner-releases-blue.svg)](https://github.com/FarbodSalamat-Zadeh/LabelledSpinner/releases)
[![Tags](https://img.shields.io/badge/LabelledSpinner-tags-FF69B4.svg)](https://github.com/FarbodSalamat-Zadeh/LabelledSpinner/tags)

## 1.1.5
_30th Jan '16_
- Include update to Android build tools (23.0.2)
- Fix `LabelledSpinner` constructor calls (where there were calls to the View constructor for API 21+)

## 1.1.4
_17th Jan '16_
- Add optional error text for when the first item (e.g. a prompt text)of the `LabelledSpinner` is selected

## v1.1.3
_10th Jan '16_
- Travis CI integration
- Change library used to upload to Bintray

## v1.1.2
_5th Jan '16_
- The items displayed can be set using an XML attribute. Also, `setItemsArray` can now have a `CharSequence[]` as the argument.
- `LabelledSpinner` has new constructors (including one for API 21+)
- Refactoring of `LabelledSpinner` (including the use of `List` instead of `ArrayList`)
- Optimised imports

## v1.1
_28th Dec '15_
- Cleared up lots of minor issues.

## Initial release (v1.0)
_24th Dec '15_
- Initial release of the library, transferred originally from a number of files on GitHub Gist.
