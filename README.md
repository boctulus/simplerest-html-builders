> **Legacy package identity.** This repository retains the v1.0.0 tag. For new SimpleRest projects use [simplerest-bootstrap-html](https://github.com/boctulus/simplerest-bootstrap-html). The successor repositories are available on GitHub without version tags and are not registered on Packagist.

# SimpleRest HTML Builders

Composer package containing the Bootstrap 5 `Bt5Form` and AdminLTE `AdminLte` HTML builders.

```bash
composer require boctulus/simplerest-html-builders
```

The package requires SimpleRest and uses the core `Html`, `Strings`, and `Arrays` helpers. It has no copied frontend assets.

The package exposes `Boctulus\Simplerest\HtmlBuilders\Bt5Form` and `Boctulus\Simplerest\HtmlBuilders\AdminLte`. SimpleRest 3.x keeps the former core FQCNs as Composer compatibility aliases when this package is installed. Code that checks the reflected class name or stores serialized class names can observe the namespace move.

Run the package contract tests with:

```bash
composer test
```
