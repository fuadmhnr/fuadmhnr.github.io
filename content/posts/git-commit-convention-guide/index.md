---
title: 'Git Commit Convention Guide'
date: 2026-02-04
draft: false
summary: 'This guide covers 9 standard git commit message conventions that help make commit history clear and meaningful'
topics: ['Programming', 'Coding']
showTaxonomies: true
---

I've been learning to follow proper git commit conventions lately. I started applying this at my previous workplace and want to share it with you all. Using clear commit messages, instead of just "fix fix fix", is incredibly helpful for developers who need to review commit history or continue someone else's work.

Here's a breakdown of the main commit types:

**1. feat**

Short for "feature." Use this when adding new features or functionality to your project.

Example:

```
feat: add new feature
```

**2. fix**

Use this when fixing a bug. Apply it whenever you resolve an error, bug, or unexpected system behavior.

Example:

```
fix: correct password validation logic
```

**3. chore**

For routine tasks that don't affect application functionality, such as updating dependencies, configuration files, or build scripts.

Example:

```
chore: update npm dependencies
```

**4. refactor**

Use when improving code without changing its behavior. This includes rewriting functions to be more efficient, readable, or maintainable while keeping the output the same.

Example:

```
refactor: simplify user authentication logic
```

**5. docs**

For updating or adding documentation, such as README files or code comments.

Example:

```
docs: update installation instructions
```

**6. style**

For style-related changes that don't affect application logic, like formatting, fixing indentation, spacing, or addressing linter warnings.

Example:

```
style: fix ESLint warnings in user model
```

**7. test**

When updating or creating new tests, such as unit tests or integration tests.

Example:

```
test: add tests for login API
```

**8. perf**

For changes that improve application performance, like optimizing database queries.

Example:

```
perf: improve database query speed
```

**9. build**

For changes affecting the build system or external dependencies, such as updating build scripts or CI/CD pipelines.

Example:

```
build: update webpack config for production
```

---

While there aren't strict rules for commit messages, following these conventions makes it much easier for other developers to understand what each commit is about. It provides valuable context that saves time and reduces confusion. I'm writing this as a reminder for myself too, since I sometimes forget! Hope this helps.
