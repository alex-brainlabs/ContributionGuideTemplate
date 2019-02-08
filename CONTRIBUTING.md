# How to contribute

## Github workflow

- Explain how to get a local copy of the project - most likely create your own fork of the repo to make changes
- Git workflow - detail process for pull requests, branch names etc.

Example:
> To make changes to the code:
> 1. Create your own fork of this repository 
> 2. Do your changes in the fork. 
> 3. For a feature, do your work on a branch called `feature/{feature-name}` and make a pull request into `master`.

## Testing

- Explain whether tests are necessary (most likely yes, except for very small changes e.g. fixing typos)
- Explain how to run the tests
- For libraries, always compulsory for new features
- For large projects, up to discretion of project owner
- Explain whether or not there are automated tests when pull requests are submitted

Example:
> All new features must be submitted with appropriate tests (see current `tests/` directory for examples). You can run all the current tests using the command `make test-all`. Travis will automatically run the test suite whenever a pull request is submitted.

## Code reviews

- Explain review process including who reviews it and how the request gets accepted (passes automated tests and passes review by project owner)
- If automated tests running (as above), mention that they need to pass

Example:
> After you have submitted a pull request, it must be reviewed by one of the project maintainers before it can be merged. Travis must also pass all automated tests.

## How to report a bug

- For security issues, do not submit an issue - email instead (provide email address)
- For other bugs, most likely submit an issue on repo
- Explain any other bug reporting systems (filing bug reports etc.)

Example:
> If you find a security vulnerability, do NOT open an issue. Email XXXX instead.
> For any other bugs, open an issue and provide details.

## Conventions (optional)

If you have specific conventions for the following, mention them here. Optional because these things are likely to be covered by project READMEs or style guides for specific languages.
- Code style
- Commit message conventions
- Labelling conventions for issues

Example:
> Write commit messages using the imperative case, e.g. `fix bug` rather than `fixed bug` or `fixes bug`.
