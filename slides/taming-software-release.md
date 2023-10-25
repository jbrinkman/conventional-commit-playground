# Conventional Commits

* Lightweight convention
* Provides an easy set of rules
* Describe the features, fixes, and breaking changes made.

---
# Conventional Commits

* Structured as follows:

``` markdown
<type>[optional scope]: <description>
```

* `<type>`: fix, feat, docs, style, refactor, test, chore, ci, perf, build, or revert
* `<scope>`: Provides context of area of code change
* `<description>`: A description of the change

---
# Conventional Commits

## Why?

* Provides a consistent way to communicate about changes
* Allows for automatic changelog generation
* Allows for automatic versioning and release notes generation

[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

---
# Commitlint

* Commitlint checks if commit messages meet the conventional commit format
* You control formatting rules

example:
``` bash
❯ echo "foo: some message" | commitlint

⧗   input: foo: bar
✖   type must be one of [build, chore, ci, docs, feat, fix, perf, refactor, revert, style, test] [type-enum]

✖   found 1 problems, 0 warnings
ⓘ   Get help: https://github.com/conventional-changelog/commitlint/#what-is-commitlint
```

[Commitlint](https://commitlint.js.org/#/)
---
# Git Hooks

* Scripts that run before or after certain git commands
* Can be used to run tests before pushing to remote
* Can be used to enforce code style
* Can be used to enforce commit message conventions

---
# Git Hooks

## Problematic

* Git hooks are stored in `.git/hooks`
* They are not version controlled
* Not portable across team members

[Git Hooks](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks)
---
# Husky

* Allows you to store git hooks in your repository
* Supports all client-side git hooks

[Husky](https://typicode.github.io/husky/)
---

# Semantic Versioning

* A standard for versioning software
* Provides a way to communicate the impact of changes

[Major].[Minor].[Patch] => [Breaking].[Feature].[Fix]

[SemVer](https://semver.org/)

---
# Semantic Release

* A tool that automates the release process
* Determines the next version number based on commit messages
* Generates changelogs
* Publishes releases to GitHub, npm, etc.

[Semantic Release](https://semantic-release.gitbook.io/semantic-release/)

---
# GitHub Actions

* Automate workflows
* Can be used to run tests, build, and deploy
* Can be used to run semantic release
* Triggered by events such as push, pull request, etc.

[GitHub Actions](https://github.com/features/actions)
