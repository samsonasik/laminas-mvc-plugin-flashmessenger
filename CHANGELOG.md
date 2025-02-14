# Changelog

All notable changes to this project will be documented in this file, in reverse chronological order by release.

## 1.3.0 - TBD

### Added

- Nothing.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

## 1.2.0 - 2019-10-19

### Added

- [zendframework/zend-mvc-plugin-flashmessenger#24](https://github.com/zendframework/zend-mvc-plugin-flashmessenger/pull/24) adds support for PHP 7.3.

- [zendframework/zend-mvc-plugin-flashmessenger#22](https://github.com/zendframework/zend-mvc-plugin-flashmessenger/pull/22) adds `Laminas\Mvc\Plugin\FlashMessenger\View\HelperTrait`,
  which can be used to provide IDE autocompletion for view helpers
  provided by laminas-mvc-plugin-flashmessenger. See
  https://docs.laminas.dev/laminas-mvc-plugin-flashmessenger/view-helper/#ide-auto-completion-in-templates
  for more information.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- [zendframework/zend-mvc-plugin-flashmessenger#24](https://github.com/zendframework/zend-mvc-plugin-flashmessenger/pull/24) removes support for laminas-stdlib v2 releases.

### Fixed

- Nothing.

## 1.1.0 - 2018-04-30

### Added

- [zendframework/zend-mvc-plugin-flashmessenger#10](https://github.com/zendframework/zend-mvc-plugin-flashmessenger/pull/10) ports the flashMessenger view helper from laminas-view to this package, under the
  class name `Laminas\Mvc\Plugin\FlashMessenger\View\Helper\FlashMessenger`, and using the helper name
  `flashMessenger()`.

- [zendframework/zend-mvc-plugin-flashmessenger#19](https://github.com/zendframework/zend-mvc-plugin-flashmessenger/pull/19) adds support for PHP 7.1 and 7.2.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- [zendframework/zend-mvc-plugin-flashmessenger#19](https://github.com/zendframework/zend-mvc-plugin-flashmessenger/pull/19) removes support for HHVM.

### Fixed

- Nothing.

## 1.0.0 - 2016-05-31

First stable release.

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [zendframework/zend-mvc-plugin-flashmessenger#2](https://github.com/zendframework/zend-mvc-plugin-flashmessenger/pull/2)
  updates the minimum PHP version to 5.6.
- [zendframework/zend-mvc-plugin-flashmessenger#2](https://github.com/zendframework/zend-mvc-plugin-flashmessenger/pull/2)
  pins the component to laminas-mvc 3.0 stable, and marks v2 releases as conflicts.

## 0.1.0 - 2016-03-28

First (stable) release.

This component replaces the `FlashMessenger` (aka `flashMessenger()`) plugin from
laminas-mvc, for use with upcoming v3 of that component. Once that stable release
is made, we will issue a 1.0.0 release removing the `dev-develop as 3.0.0`
laminas-mvc constraint.

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.
