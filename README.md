# Run arbitrary commands within the containerised build runner.

This repo is WIP, but it is created to solve [composer#67](https://github.com/php-actions/composer/issues/67)

The plan is to create a test runner in the same way that phpunit/phpstan/behat are running, but allow the developer to state a command to run within the test runner itself, allowing the command to be ran within the container, respecting PHP versions, etc.
