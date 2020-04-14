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
