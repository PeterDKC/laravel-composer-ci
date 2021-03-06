# Laravel Composer ci

Snippets to quickly stand up PHPUnit Tests, PHPMD, and php-cs-fixer for local development + CI/CD in a Laravel project.

## Usage

This is basically a copy-paste dump for files and snippets.

1. Make sure you've installed the latest stable versions of the 3 composer packages listed in `composer.json`
2. Add the `scripts` section contents to your existing `scripts` in `composer.json`
3. Copy paste the following files into your repo at root level and adjust / tweak as needed:
  - `.php_cs.dist`
  - `phpmd.xml`
  - `phpunit.xml`

## Readme contents

Feel free to copy paste the contents of `README_SAMPLE.md` Following are said contents in readable form.

## Unit tests, code coverage, and more

### Continuous Integration

You can quickly run all of the same tests Gitlab CI runs using `composer ci`.

### PHPUnit Tests

You can run the project's PHPUnit test suite using `composer test`.

### Code Coverage

You can generate a code coverage report using `composer coverage`.

### Code Style Fixer

You can run `composer cs-fix` to fix code style issues, or simply `composer cs` for a dry run.

### Mess Detector

You can sniff out code smells using PHP Mess Detector by running `composer phpmd`.

### CI

For unit test coverage (I've only tested this in Gitlab), use `composer test-ci` to generate code coverage metrics for the test stage. Use the cs-fixer and phpmd commands as outlined above.
