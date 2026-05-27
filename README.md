# margus/homebrew-tap

Homebrew formulas for [margus](https://github.com/margus)' tools.

## Install

```sh
brew tap margus/tap
brew install bb       # bitbucket-cli
```

Or in one shot:

```sh
brew install margus/tap/bb
```

## What's in here

| Formula | Description | Source |
|---|---|---|
| `bb` | Bitbucket Cloud REST API CLI | [margus/bitbucket-cli](https://github.com/margus/bitbucket-cli) |

## How it's maintained

Formulas are auto-published by [goreleaser](https://goreleaser.com) on
each release of the upstream tool. See the upstream repo's
`.goreleaser.yaml` for the formula template.

Manual edits to `Formula/*.rb` will be overwritten on the next release.
