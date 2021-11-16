# Changelog since v1.4.2
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
