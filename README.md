# GCP Orb


[![CircleCI](https://dl.circleci.com/status-badge/img/gh/mozilla/gcp-orb/tree/main.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/mozilla/gcp-orb/tree/main) [![CircleCI Orb Version](https://badges.circleci.com/orbs/mozilla/gcp.svg)](https://circleci.com/developer/orbs/orb/mozilla/gcp) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)] 


CircleCI Orb for common GCP-related CI commands used at Mozilla

---

## Resources

[CircleCI Orb Registry Page](https://circleci.com/developer/orbs/orb/mozilla/gcp) - The official registry page of this orb for all versions, executors, commands, and jobs described.

[CircleCI Orb Docs](https://circleci.com/docs/orb-intro/#section=configuration) - Docs for using, creating, and publishing CircleCI Orbs.

### How to Contribute

We welcome [issues](https://github.com/mozilla//issues) to and [pull requests](https://github.com/mozilla//pulls) against this repository!

### How to Publish An Update
1. Merge pull requests with desired changes to the main branch.
    - For the best experience, squash-and-merge and use [Conventional Commit Messages](https://conventionalcommits.org/).
2. Find the current version of the orb.
    - You can run `circleci orb info mozilla/gcp | grep "Latest"` to see the current version.
3. Create a [new Release](https://github.com/mozilla/gcp-orb/releases/new) on GitHub.
    - Click "Choose a tag" and _create_ a new [semantically versioned](http://semver.org/) tag. (ex: v1.0.0)
      - We will have an opportunity to change this before we publish if needed after the next step.
4.  Click _"+ Auto-generate release notes"_.
    - This will create a summary of all of the merged pull requests since the previous release.
    - If you have used _[Conventional Commit Messages](https://conventionalcommits.org/)_ it will be easy to determine what types of changes were made, allowing you to ensure the correct version tag is being published.
5. Now ensure the version tag selected is semantically accurate based on the changes included.
6. Click _"Publish Release"_.
    - This will push a new tag and trigger your publishing pipeline on CircleCI.