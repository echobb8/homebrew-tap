# Homebrew Tap for Strata Apex

Native Apple Silicon Metal 4 LLM & continuous-batching swarm inference engine.

## Install

```zsh
brew install echobb8/tap/strata-apex
```

Or tap first:

```zsh
brew tap echobb8/tap
brew install strata-apex
```

## Quickstart

```zsh
strata-apex doctor
strata-apex pull inkling-2-mini
strata-apex serve inkling-2-mini --max-batch 8 --max-seq-len 16384
```

See [echobb8/strata-apex](https://github.com/echobb8/strata-apex) for full documentation.
