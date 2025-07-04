# Contributing

[code-of-conduct]: CODE_OF_CONDUCT.md

Hi there! We're thrilled that you'd like to contribute to GitVision. Your help is essential for keeping this Eurovision-themed workshop great.

Contributions to this project are [released](https://help.github.com/articles/github-terms-of-service/#6-contributions-under-repository-license) to the public under the [project's open source license](LICENSE.md).

Please note that this project is released with a [Contributor Code of Conduct][code-of-conduct]. By participating in this project you agree to abide by its terms.

## Prerequisites for running and testing code

These are one time installations required to be able to test your changes locally as part of the pull request (PR) submission process.

1. Install Flutter [through download](https://flutter.dev/docs/get-started/install) | [through package manager](https://flutter.dev/docs/get-started/install)
2. Set up API tokens in `gitvision/lib/config/api_tokens.dart` (copy from example file)
3. Run the workshop setup: `cd gitvision && ./workshop-start.sh`

## Eurovision Content Guidelines

When contributing Eurovision-related content, please ensure:

- **Accurate Information**: Verify song titles, artists, years, and countries are correct
- **Historical Context**: Handle country name changes appropriately (e.g., Yugoslavia → Serbia)

## Submitting a pull request

1. [Fork][fork] and clone the repository
2. Set up the development environment (see prerequisites above)
3. Create a feature branch: `git checkout -b feature/your-feature-name`
4. Make your changes and test the workshop flow end-to-end
5. Ensure `flutter analyze` passes with no issues
6. Push to your fork and [submit a pull request][pr]
7. Pat yourself on the back and wait for your pull request to be reviewed and merged

Here are a few things you can do that will increase the likelihood of your pull request being accepted:

- Keep your change as focused as possible. If there are multiple changes you would like to make that are not dependent upon each other, consider submitting them as separate pull requests.
- Write a [good commit message](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html).
- Test your changes with the full 120-minute workshop flow.
- If adding Eurovision content, verify accuracy.

## Resources

- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [Using Pull Requests](https://help.github.com/articles/about-pull-requests/)
- [GitHub Help](https://help.github.com)
- [Eurovision Official Site](https://eurovision.tv) for accurate song information
- [Flutter Documentation](https://flutter.dev) for technical guidance