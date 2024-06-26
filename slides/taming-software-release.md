---
theme:
  path: ./theme.yml
---
![alt text](title-generic.png "Title")

<!-- end_slide -->

![Joe Brinkman About](about.png "About Me : Joe Brinkman")

<!-- end_slide -->
About Improving
---
<!-- column_layout: [4, 2] -->
<!-- column: 0 -->
## Improving is Hiring!

* **Account Executive**
* **React Developers**
* **Mobile Developers**
* **Automation Test Engineer**
* **Full Stack Developers**
* **Cloud Engineers**

See additional open positions at https://improving.com/careers/open-positions

<!-- column: 1 -->
## Chance to Win!
![Attendee Raffle](QRCode-cledevops.png)

<!-- reset_layout -->
<!-- end_slide -->

Conventional Commits
---

* Lightweight convention
* Provides an easy set of rules
* Describe the features, fixes, and breaking changes made.

<!-- end_slide -->
Conventional Commits
---

* Structured as follows:

``` markdown
<type>[optional scope]: <description>
```
<!-- pause -->
* `<type>`: fix, feat, docs, style, refactor, test, chore, ci, perf, build, or revert
* `<scope>`: Provides context of area of code change
* `<description>`: A description of the change

<!-- end_slide -->
Conventional Commits
---

## Why?

* Provides a consistent way to communicate about changes
* Allows for automatic changelog generation
* Allows for automatic versioning and release notes generation

[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

<!-- end_slide -->
Commitlint
---

* Commitlint checks if commit messages meet the conventional commit format
* You control formatting rules

<!-- pause -->
example:
``` bash
❯ echo "foo: some message" | commitlint

⧗   input: foo: bar
✖   type must be one of 
      [build, chore, ci, docs, feat, fix, ...] [type-enum]

✖   found 1 problems, 0 warnings
```

[Commitlint](https://commitlint.js.org/)
<!-- end_slide -->
Git Hooks
---

* Scripts that run before or after certain git commands
* Can be used to run tests before pushing to remote
* Can be used to enforce code style
* Can be used to enforce commit message conventions

<!-- end_slide -->
Git Hooks
---

## Problematic

* Git hooks are stored in `.git/hooks`
* They are not version controlled
* Not portable across team members

[Git Hooks](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks)
<!-- end_slide -->
Husky
---

* Allows you to store git hooks in your repository
* Supports all client-side git hooks

[Husky](https://typicode.github.io/husky/)
<!-- end_slide -->

Semantic Versioning
---

* A standard for versioning software
* Provides a way to communicate the impact of changes

[Major].[Minor].[Patch] => [Breaking].[Feature].[Fix]

[SemVer](https://semver.org/)

<!-- end_slide -->
Semantic Release
---

* A tool that automates the release process
* Determines the next version number based on commit messages
* Generates changelogs
* Publishes releases to GitHub, npm, etc.

[Semantic Release](https://semantic-release.gitbook.io/semantic-release/)

<!-- end_slide -->
GitHub Actions
---

* Automate workflows
* Can be used to run tests, build, and deploy
* Can be used to run semantic release
* Triggered by events such as push, pull request, etc.

[GitHub Actions](https://github.com/features/actions)
