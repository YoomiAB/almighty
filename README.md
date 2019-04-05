# almighty
You cannot spell ALMIGHTY without git

# General Guidelines

This is a repository containing ...

# Maintainer/Contributor Guidelines

- [Contributors Guide](CONTRIBUTORS.md)
- [Maintainers Guide](MAINTAINERS.md)

For documentation guidelines, visit the [documentation repository](https://github.com/YoomiAB/almighty/blob/master/CONTRIBUTING.md).

## Templates

The `template/` directory contains templates for use in creating new
repositories, including:

- a `.coveralls.yml` file with common settings.
- a `.gitattributes` file with common settings.
- a `.gitignore` file with common exclusions.
- a `.travis.yml` template with recommended configuration for new components.
- a `CHANGELOG.md` template with library changelog.
- a `composer.json` with a basic package structure.
- a `LICENSE.md` template.
- a `mkdocs.yml` file with MkDocs configuration.
- a `phpcs.xml` file with zend coding standard configuration.
- a `phpunit.xml.dist` file with PHPUnit configuration.
- a `README.md` template for new components with basic structure.
- a `docs/` directory with support templates:
  - `CODE_OF_CONDUCT.md` with the Code Manifesto.
  - `CONTRIBUTING.md` with instructions on how to contribute.
  - `ISSUE_TEMPLATE.md` for new issues.
  - `PULL_REQUEST_TEMPLATE.md` for new pull requests.
  - `SUPPORT.md` with instructions on how to get support for the package.
- a `docs/book/` directory with documentation template.
- a `src/` directory with `ConfigProvider` template.
- a `test/` directory with `ConfigProviderTest` test case.

Templates all use the same placeholders, which can be replaced en masse:

- `{year}` is the year of first publication, or a range of years from first
  publication until most recent update.
- `{org}` refers to the github organization under which the package will live.
- `{repo}` is the name of the repository.
- `{category}` should be one of `expressive`, `components`, or `apigility`.
- `{namespace}` should be the top-most namespace unique to the repository.
- `{namespace-test}` should be the namespace used for unit tests in the repository.
