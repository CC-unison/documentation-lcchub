---
title: About
layout: about
---

# **An attempt to document the lcc hub social service project**

**Author**: enrique giottonini \
**Status**: in progress \
**Created**: 2024-03-29

---

The first task I received when I joined this social service project was to fix some
broken features of the LCC Hub application. The only info at my disposal was code
in a GitHub repository, a one-page document with a high level description of the project,
and the credentials to access a server through ssh.

Unfortunately to me, the code was written in a language paradigm unknown to me (Dart/Flutter), in a monolithic fashion, with large sections of code sparsely commented,
and commit messages that looked like this:

```bash
commit 232c814, message: 'Login', showing 17 changed files with 424 additions and 59 deletions
commit 2aa50f1, message: 'Project was restructured', showing 66 changed files with 937 additions and 316 deletions
```

A lot of time went lost trying to make sense of the project, I was planning to
document it, or approach it through testing, but at the end, it seemed easier
to do it from scratch.

## How to not repeat the same mistakes?

One suggestion is to document our thoughts. As we lack expertise, we explore
may ideas until we run out of time, and then, we inadvertently cover
our tracks. With documentation
we could share knowledge, explain decisions, and facilitate resources to others. Also,
exposing ourselves in this way force us to be conscious in how we approach
the project, and the results are more honest.

The idea isn't new, this blog post ['Documentation as way to build Community'](https://labs.quansight.org/blog/2020/03/documentation-as-a-way-to-build-community)
may convince you to give more importance to documentation in your next projects.

## Approach

Let's use a [Documentation System](https://documentation.divio.com/)
for the next reasons:

1. It was recommended in Hacker News
2. Seems to be used by numpy, django, etc.

If we have some first hand experience using a methodology to write our documentation, we will
be better equipped to use documentation from some big projects.
