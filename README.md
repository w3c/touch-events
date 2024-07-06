Touch Events
============

This is the document repository for the [Touch Events Community Group](http://www.w3.org/community/touchevents/).

**This Community Group is now closed, and the last version of the specification that the group worked on has been mirrored to: [Final Community Group Report for Touch Events Level 2](https://www.w3.org/community/reports/touchevents/CG-FINAL-touch-events-20240704/)**.

There is currently no intention to carry on further work on the Touch Events specification. This document has been maintained up to this point to reflect additions and changes made in user agents since the release of the original [Touch Events Level 1](https://www.w3.org/TR/touch-events/) specification. The Community Group considers Touch Events a _legacy API_ – authors are strongly encouraged to adopt [Pointer Events](https://www.w3.org/TR/pointerevents/) instead.

# Branches

This repo has two branches of note:

* `gh-pages` - this branch is active; it contains the [Touch Events Level 2](http://w3c.github.io/touch-events/) editors draft, which includes all the changes from an old `v1-errata` branch and the [Touch Events Extension Working Group Note](http://www.w3.org/TR/touch-events-extensions/))
* `v1` - this branch is it not active, and only contains the working branch for the v1 specification

# Process for Landing Changes

Per the group's [2015-Jan-27 agreement](http://www.w3.org/2015/01/27-touchevents-minutes.html#item05), the following process was used to review and approve Pull Requests:

* Submit a pull request and post the PR's link to the [public-touchevents](https://lists.w3.org/Archives/Public/public-touchevents/) e-mail list asking for feedback.
* As soon as one of the listed spec editors approves the PR it can be merged.
* If there's debate over a PR that has already landed, it may be reverted until consensus is reached.

## Tests

For normative changes, a corresponding
[web-platform-tests](https://github.com/web-platform-tests/wpt) PR is highly appreciated. Typically,
both PRs will be merged at the same time. Note that a test change that contradicts the spec should
not be merged before the corresponding spec change. If testing is not practical, please explain why
and if appropriate [file an issue](https://github.com/web-platform-tests/wpt/issues/new) to follow
up later. Add the `type:untestable` or `type:missing-coverage` label as appropriate.
