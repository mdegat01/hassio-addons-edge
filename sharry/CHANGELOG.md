# Changelog since v1.4.2
- Merge pull request #84 from mdegat01/remove-github-token-input

Remove `GITHUB_TOKEN` input from all workflows 
- Bump mariadb-client to `10.6.4-r2`

Bump mariadb-client from `10.6.4-r1` to `10.6.4-r2` 
- Remove `GITHUB_TOKEN` input from all workflows 
- Merge pull request #83 from mdegat01/bump-addon-base-11.0.0

Bump addon base to `11.0.0` 
- Bump mariadb-client to `10.6.4-r1` 
- Bump addon base to `11.0.0`

Bump addon base from `10.2.3` to [11.0.0](https://github.com/hassio-addons/addon-base/releases/tag/v11.0.0). Additionally bump the following packages to latest for alpine 3.15:

- mariadb-client: `10.5.13-r0` -> `10.6.4-r1`
- netcat-openbsd: `1.130-r2` -> `1.130-r3`
- openjdk11-jre: `11.0.11_p9-r0` -> `11.0.13_p8-r0` 
- Merge pull request #82 from mdegat01/dependabot/docker/sharry/alpine-3.15.0

Bump alpine from 3.14.3 to 3.15.0 in /sharry 
- Bump curl to `7.80.0-r0`

Bump curl from `7.79.1-r0` to `7.80.0-r0` 
- Bump alpine from 3.14.3 to 3.15.0 in /sharry

Bumps alpine from 3.14.3 to 3.15.0.

---
updated-dependencies:
- dependency-name: alpine
  dependency-type: direct:production
  update-type: version-update:semver-minor
...

Signed-off-by: dependabot[bot] <support@github.com> 
- Merge pull request #81 from mdegat01/remove-inherited-templates

Inherit org's PR and release drafter templates 
- Inherit org's PR and release drafter templates 
- Merge pull request #80 from mdegat01/config-to-yaml

Convert config from json to yaml 
- Convert config from json to yaml 
- Merge pull request #79 from mdegat01/add-pr-template

Add PR template 
- Add PR template 
- Merge pull request #78 from mdegat01/centralize-workflows

Centralize GitHub Action workflows 
- Centralize GitHub Action workflows 
- Merge pull request #77 from mdegat01/bump-addon-base-10.2.3

Bump addon base to `10.2.3` 
- Bump `mariadb-client` to `10.5.13-r0`

Bump `mariadb-client` from `10.5.12-r0` to `10.5.13-r0` 
- Bump addon base to `10.2.3`

Bump addon base from `10.2.2` to [10.2.3](https://github.com/hassio-addons/addon-base/releases/tag/v10.2.3) 
- Merge pull request #76 from mdegat01/dependabot/docker/sharry/alpine-3.14.3

Bump alpine from 3.14.2 to 3.14.3 in /sharry 
- Bump alpine from 3.14.2 to 3.14.3 in /sharry

Bumps alpine from 3.14.2 to 3.14.3.

---
updated-dependencies:
- dependency-name: alpine
  dependency-type: direct:production
  update-type: version-update:semver-patch
...

Signed-off-by: dependabot[bot] <support@github.com> 
- Merge pull request #75 from mdegat01/ci-clear-build-cache

Clear build cache during CI 
- Clear cache in deploy and add turnstyle to builds 
- Clear build cache during CI

Appears there is an issue where the build cache grows unbounded until it hits Github's limit (https://github.com/docker/build-push-action/issues/252, https://github.com/moby/buildkit/issues/1896). Clear the cache after builds to prevent this 
