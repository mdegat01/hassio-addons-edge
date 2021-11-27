# Changelog since v1.9.0
- Merge pull request #173 from mdegat01/dependabot/docker/promtail/alpine-3.15.0

Bump alpine from 3.14.3 to 3.15.0 in /promtail 
- Bump curl to `7.80.0-r0`

Bump curl from `7.79.1-r0` to `7.80.0-r0` 
- Bump alpine from 3.14.3 to 3.15.0 in /promtail

Bumps alpine from 3.14.3 to 3.15.0.

---
updated-dependencies:
- dependency-name: alpine
  dependency-type: direct:production
  update-type: version-update:semver-minor
...

Signed-off-by: dependabot[bot] <support@github.com> 
- Merge pull request #172 from mdegat01/bump-yq-4.15.1

Bump yq to `4.15.1` 
- Bump yq to `4.15.1`

Bump yq from `4.14.2` to [4.15.1](https://github.com/mikefarah/yq/releases/tag/v4.15.1) 
- Merge pull request #171 from mdegat01/remove-inherited-templates

Inherit org's PR and release drafter templates 
- Inherit org's PR and release drafter templates 
- Merge pull request #170 from mdegat01/config-to-yaml

Convert config from json to yaml 
- Convert config from json to yaml 
- Merge pull request #169 from mdegat01/add-pr-template

Add PR template 
- Add PR template 
- Merge pull request #168 from mdegat01/centralize-workflows

Centralize GitHub Action workflows 
- Centralize GitHub Action workflows 
- Merge pull request #167 from mdegat01/bump-yq-4.14.2

Bump yq to `4.14.2` 
- Bump yq to `4.14.2`

Bump yq from `4.14.1` to [4.14.2](https://github.com/mikefarah/yq/releases/tag/v4.14.2) 
- Merge pull request #166 from mdegat01/dependabot/docker/promtail/alpine-3.14.3

Bump alpine from 3.14.2 to 3.14.3 in /promtail 
- Bump alpine from 3.14.2 to 3.14.3 in /promtail

Bumps alpine from 3.14.2 to 3.14.3.

---
updated-dependencies:
- dependency-name: alpine
  dependency-type: direct:production
  update-type: version-update:semver-patch
...

Signed-off-by: dependabot[bot] <support@github.com> 
- Merge pull request #164 from mdegat01/ci-clear-build-cache

Cache management and one-at-a-time builds in CI 
- Add turnstyle and use .docker-cache-new in deploy 
- Use /tmp/.docker-cache-new in ci 
- Clear build cache after build in deploy 
- Clear build cache during CI

Appears there is an issue where the build cache grows unbounded until it hits Github's limit (https://github.com/docker/build-push-action/issues/252, https://github.com/moby/buildkit/issues/1896). Clear the cache after builds to prevent this 
