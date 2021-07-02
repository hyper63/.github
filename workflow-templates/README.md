<h1 align="center">hyper workflow templates</h1>
<p align="center">A set of Github workflow templates used in repos part of the <a href="https://hyper.io/">hyper</a>  service framework</p>
</p>

---

## Available Workflows

### Tag And Release

Dispatch workflow that, provided a semver compatible version, will bump, commit,
tag, and push changes, back to the source repo, using hyper conventions for
versioning.

This workflow augments the
[hyper-ci-bump](https://github.com/hyper63/hyper-ci-bump) Github Action.
Reference this repo for available options

### Test

Run `./scripts/test.sh` on every push
