# Change Management Discovery: [Semantic Release](https://github.com/semantic-release/semantic-release)

## Why ?

Currently we have a lot of inconsistencies in versioning, releasing and managing changelogs across applications and libraries. Partly there is no reasonable versioning in place and changelogs hardly exist, mostly being manually created and managed.

## Setup

Follow the [guide](https://github.com/semantic-release/semantic-release/blob/master/docs/usage/getting-started.md#getting-started). for initial setup.

## Usage

### Using Conventional Commits

- Create a new branch, apply your changes and commit using [conventional commit](https://intuit.github.io/auto/docs/generated/conventional-commits). Using [commitizen](https://github.com/commitizen/cz-cli) is highly recommended!

- Push your branch to the remote and open a merge/pull request.

- if your branch contains any commit messages that make a version bump reasonable (feat, fix, breaking change)
