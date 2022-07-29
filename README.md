If any pull request description in a repo contains an emoji modifier character that isn't modifying anything, Renovate will throw an error while fetching and hashing PRs.

Sample PR to show issue: https://github.com/ecraig12345/renovate-emoji-repro/pull/2

NOTE: The project's dependencies aren't relevant for this issue, so I just added one dependency on an outdated `typescript` version.
