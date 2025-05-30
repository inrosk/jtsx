<!-- markdownlint-disable MD001 MD013 -->

# Changelog

## Master

* Apply JSX comment logic to `comment-line` function.

## 0.6.0 (2025-03-08)

* Add jsdoc language to jtsx-install-treesit-language function.
* Add delete jsx attribute feature. 

## 0.5.1 (2024-07-15)

* Fix folding for js nested in jsx.

## 0.5.0 (2024-05-03)

* Add command to toggle the orientation of JSX attributes.

## 0.4.2 (2024-04-18)

* Add Eask as project management tool.
* Code folding fixes and enhancements (@ramblehead).
* Enhancements on JSX comment functionality.

## 0.4.1 (2024-03-15)

* Fix electric closing tag not working for jsx root element.
* Add `jtsx-typescript-mode` based on `typescript-ts-mode` for pure `TS` files.
* Fix wrong cursor position after wrapping.

## 0.4.0 (2024-03-01)

* Add automatic name synchronization of JSX element tags.

## 0.3.5 (2024-02-10)

* Fix font lock issue due to a breaking change in treesit grammars.

## 0.3.4 (2024-02-08)

* Add unwrap and delete features.
* Fix jsx electric newline having side effects in none jtsx buffers.

## 0.3.3 (2024-01-04)

* Activate support for shift key when jumping.
* Add support for wrapping a text selection (e.g. wrap some word of a text node with a `strong` element).
* Make cursor position more consistent after renaming an element.
* Add electric new line support for empty inline elements.

## 0.3.2 (2023-12-18)

* Moving an inline jsx element is now supported.

## 0.3.1 (2023-12-11)

* Fix JSX attribute coloration issue in jtsx-jsx-mode.
* Wrapping an inline jsx element is now supported.
* Fix wrapping jsx nested into a jsx element attribute.
* Fix commenting jsx nested into a jsx element attribute.

## 0.3.0 (2023-12-04)

* Now available on Melpa.
* Set maximum level of syntax highlighting provided by `js-ts-mode` and `tsx-ts-mode` by default. Can be disabled with `jtsx-enable-all-syntax-highlighting-features` custom variable.

## 0.2.1 (2023-11-21)

* Remame `jsx-mode` to `jtsx-jsx-mode` and `tsx-mode` to `jtsx-tsx-mode`. Keep `jsx-mode` and `tsx-mode` for backward compatibility but mark them as obsolete.
