<p align="center">
  <a href="https://github.com/andry81-stats/github-action-extensions--gh-stats/commits/master/traffic/views">
    <img src="https://github.com/andry81-cache/andry81-devops--gh-content-cache/raw/master/repo/andry81-devops/github-action-extensions/badges/traffic/views/all.svg" valign="middle" alt="GitHub views|any|total" />
    <img src="https://github.com/andry81-cache/andry81-devops--gh-content-cache/raw/master/repo/andry81-devops/github-action-extensions/badges/traffic/views/all-14d.svg" valign="middle" alt="GitHub views|any|14d" /></a>
• <a href="https://github.com/andry81-stats/github-action-extensions--gh-stats/commits/master/traffic/views">
    <img src="https://github.com/andry81-cache/andry81-devops--gh-content-cache/raw/master/repo/andry81-devops/github-action-extensions/badges/traffic/views/unq.svg" valign="middle" alt="GitHub views|unique per day|total" />
    <img src="https://github.com/andry81-cache/andry81-devops--gh-content-cache/raw/master/repo/andry81-devops/github-action-extensions/badges/traffic/views/unq-14d.svg" valign="middle" alt="GitHub views|unique per day|14d" /></a>
</p>

<p align="center">
  <a href="https://github.com/andry81-stats/github-action-extensions--gh-stats/commits/master/traffic/clones">
    <img src="https://github.com/andry81-cache/andry81-devops--gh-content-cache/raw/master/repo/andry81-devops/github-action-extensions/badges/traffic/clones/all.svg" valign="middle" alt="GitHub clones|any|total" />
    <img src="https://github.com/andry81-cache/andry81-devops--gh-content-cache/raw/master/repo/andry81-devops/github-action-extensions/badges/traffic/clones/all-14d.svg" valign="middle" alt="GitHub clones|any|14d" /></a>
• <a href="https://github.com/andry81-stats/github-action-extensions--gh-stats/commits/master/traffic/clones">
    <img src="https://github.com/andry81-cache/andry81-devops--gh-content-cache/raw/master/repo/andry81-devops/github-action-extensions/badges/traffic/clones/unq.svg" valign="middle" alt="GitHub clones|unique per day|total" />
    <img src="https://github.com/andry81-cache/andry81-devops--gh-content-cache/raw/master/repo/andry81-devops/github-action-extensions/badges/traffic/clones/unq-14d.svg" valign="middle" alt="GitHub clones|unique per day|14d" /></a>
</p>

<p align="center">
  <a href="https://github.com/andry81/donate"><img src="https://github.com/andry81-cache/andry81--gh-content-cache/raw/master/common/badges/donate/donate.svg" valign="middle" alt="donate" /></a>
</p>

---

## Tutorial to setup GitHub action extensions

Other tutorials:

* https://github.com/andry81-devops/github-accum-stats

* https://github.com/andry81-devops/accum-content

Extensions:

* https://github.com/andry81-devops/gh-action--git-checkout

## gh-action--git-checkout@master

Extends `actions/checkout` action script mainly to be able to checkout an empty repository with additional features.

You need simply replace the `uses` value in a workflow script:

`actions/checkout@v3` -> `andry81-devops/gh-action--git-checkout@master`

If remote repository exists but has no any branch reference, then the action script does use `mkdir` bash shell command to create a directory from the `path` parameter and `git init` to initialize a working copy.

Additionally, the action script does use `mkdir -p` bash shell command to allocate a working copy subdirectories  from the `mkdir-p` extra parameter.

[Example snippet](https://github.com/andry81-devops/gh-action--git-checkout#example-snippet)

> :information_source: See <a href="https://github.com/andry81-devops/github-accum-stats#reuse">REUSE</a> section for details if you have multiple repositories and want to store all GitHub workflow scripts (`.github/workflows/*.yml`) in a single repository.

## Known Issues

https://github.com/andry81-devops/github-accum-stats#known-issues

## Last known issues updates

https://github.com/andry81-devops/github-accum-stats#last-known-issues-updates
