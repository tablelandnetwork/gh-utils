# gh-utils

> Github development utilities for Tableland

## Milestones

The `create-milestones` script will sync all seasonal milestones in a given repo.

### Setup

```
brew install gh
gh login
gh extension install valeriobelli/gh-milestone
```

### Usage

```
./sync-milestones [path to local repo]
```

For example, assuming you have the `go-tableland` repo next to this repo on your machine:

```
./sync-milestones ../go-tableland
```

This will sync all seasonal milestones in the `go-tableland` repo.
