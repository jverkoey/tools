# Contributing

Want to contribute? Great! First, read this page (including the small print at the end).

### Before you contribute

Before we can use your code, you must sign the [Google Individual Contributor License Agreement](https://cla.developers.google.com/about/google-individual)
(CLA), which you can do online. The CLA is necessary mainly because you own the copyright to your changes, even after your contribution becomes part of our codebase, so we need your permission to use and distribute your code.  We also need to be sure of various other things—for instance that you'll tell us if you know that your code infringes on other people's patents.  You don't have to sign the CLA until after you've submitted your code for review and a member has approved it, but you must do it before we can put your code into our codebase. Before you start working on a larger contribution, you should get in touch with us first through the issue tracker with your idea so that we can help out and possibly guide you.  Coordinating up front makes it much easier to avoid frustration later on.

## Code reviews

All submissions, including submissions by project members, require review.

For core and regular contributors we use [Phabricator](http://codereview.cc/) for all code reviews.

We encourage everyone else to issue GitHub pull requests as you would with any GitHub project.

### The small print

Contributions made by corporations are covered by a different agreement than
the one above, the
[Software Grant and Corporate Contributor License 
Agreement](https://cla.developers.google.com/about/google-corporate).

---

## Contributing to the Starmap

### Patch acceptance process

- Read the [Governance](governance.md) article.
- Discuss your proposed changes and get agreement on our mailing list.
- [Create a pull request](https://material-motion.gitbooks.io/material-motion-team/content/gitbook_pull_request.html). This process differs from the typical GitHub pull request process.
  - Ensure that you have signed [Google's Contributor License Agreement](https://cla.developers.google.com/)
- Once your pull request has been approved, a core contributor will merge your pull request.

### Proposing new concepts

This book covers opinionated topics related to the creation of interactive software interfaces. The Starmap is not an exhaustive list of topics and ideas for motion and interaction in general.

If you feel that the Starmap is missing a concept please follow our patch acceptance process.

### Proposing terminology changes

Throughout the Starmap we will associate specific terminology with concepts. Such associations are rarely perfect, nor do we expect them to be. The goal of the following process is to minimize the subjective nature of these discussions.

If you feel that a chosen term does not effectively communicate the intended meaning, please do the following:

1. Perform a global find-and-replace of the term. Ensure that the new term applies to all existing contexts. 
1. Write an explanation for why you feel the new term should supplant the existing term including answers to each of the following questions: 
  1. What do you feel the current term describes? 
  1. What do you feel the new term describes that the current term does not? 
  1. Are there existing uses of your proposed term in the software industry? If so, please provide links to references. 
1. Propose the change as a patch.

If no consensus by the core team is reachable then the terminology will not be changed.
