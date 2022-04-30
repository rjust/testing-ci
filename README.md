# Testing and CI
This repository provides example source code and tests for the CSE 403 lecture
on Testing and CI. This repository demonstrates testing best practices, build
system configuration, and CI integration with GitHub Actions.

## Testing
Run 'ant test' to run all test cases.

## Coverage
Run 'ant coverage' to compute the coverage results. After completion, you can
view the html coverage report: reports/index.html

## GH Actions
Setting up GH Actions is straightforward in most cases. Navigating to *Actions*
and choosing one of the existing *workflows* is sufficient for many
applications. The initial configuration file (*ant.yml*) in this repository was
directly imported from the default Java with Ant workflow.
