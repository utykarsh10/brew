# Contributing to Homebrew

First time contributing to Homebrew? Read our [Code of Conduct](https://github.com/Homebrew/.github/blob/HEAD/CODE_OF_CONDUCT.md#code-of-conduct) and review [How To Open a Homebrew Pull Request](https://docs.brew.sh/How-To-Open-a-Homebrew-Pull-Request).

We explicitly welcome contributions from people who have never contributed to open-source before: we were all beginners once! We can help build on a partially working pull request with the aim of getting it merged. We are also actively seeking to diversify our contributors and especially welcome contributions from women from all backgrounds and people of colour.

A good starting point for contributing is running brew audit --strict with some of the packages you use (e.g. brew audit --strict wget if you use wget) and then read through the warnings, try to fix them until brew audit --strict shows no results and submit a pull request. If no formulae you use have warnings you can run brew audit --strict without arguments to have it run on all packages and pick one.

Alternatively, for something more substantial, check out one of the issues labeled help wanted in Homebrew/brew or Homebrew/homebrew-core.

Good luck!

### Report a bug

* Run `brew update` (twice).
* Run and read `brew doctor`.
* Read the [Troubleshooting checklist](https://docs.brew.sh/Troubleshooting).
* Open an issue on the formula's repository or on Homebrew/brew if it's not a formula-specific issue.

### Propose a feature

* Open an issue with a detailed description of your proposed feature, the motivation for it and alternatives considered. Please note we may close this issue or ask you to create a pull-request if this is not something we see as sufficiently high priority.

Thanks!
