# ALMIGHTY
You cannot spell ALMIGHTY without git

# General Guidelines

This is a repository containing ...

We use git flow for out workflows - main branches are
- master
- hotfix
- develop
- feature

Branch naming shall follow standard: changeType/changeNo/shortName
- bug/001/menu_issue
- feat/001/registration_confirm_email

Example commit message template can be found in [.gitmessage.txt](.gitmessage.txt)

Remember to 
- pull frequently (never less than daily)
- pull often - IT IS SAFE! 
- pull first thing in the morning 
- pull BEFORE you push
- pull before you go offline
- commit early and Commit often 
- not pull with untracked changes

# Maintainer/Contributor Guidelines

- [Contributors Guide](CONTRIBUTORS.md)
- [Maintainers Guide](MAINTAINERS.md)

For documentation guidelines, visit the [documentation repository](https://github.com/YoomiAB/almighty/blob/master/CONTRIBUTING.md).

## Templates

The `template/` directory contains templates for use in creating new
repositories, including:

- a `.gitattributes` file with common settings.
- a `.gitignore` file with common exclusions.
- a `LICENSE.md` template.
- a `phpcs.xml` file with coding standard configuration.
- a `phpunit.xml.dist` file with PHPUnit configuration.

Templates all use the same placeholders, which can be replaced en masse:

- `{year}` is the year of first publication, or a range of years from first
  publication until most recent update.
- `{org}` refers to the github organization under which the package will live.
- `{repo}` is the name of the repository.

## More info
Example: https://github.com/zendframework/maintainers
