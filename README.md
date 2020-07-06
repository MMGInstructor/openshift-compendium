# Openshift Compendium

![Gatsby Publish](https://github.com/IronicBadger/openshift-compendium/workflows/Gatsby%20Publish/badge.svg)

This repo contains handy commands, snippets and other tips + tricks for working with OpenShift Container Platform.

To contribute please open a PR by contributing a `.md` file (or several) to the `notes/` folder. Please keep PRs scoped by topic. For example, if adding a few commands and a few example snippets, open two PRs.

A few points to note when submitting PRs:

- Tags are case sensitive
- Links and emoji are optional
- Code blocks support multilanguage syntax highlighting with [Github flavored markdown syntax](https://help.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax)

Each note should contain some front matter. This allows the theme to parse and organize the contents more easily. For example:

```
---
title: Display etcd member table
tags:
  - Openshift 4
  - Admin Tasks
  - etcd
emoji: 🧹
link: https://access.redhat.com/solutions/4985441
---
```

Links and emoji are optional.
