# Changelog since v1.4.2
- Merge pull request #75 from mdegat01/ci-clear-build-cache

Clear build cache during CI 
- Clear cache in deploy and add turnstyle to builds 
- Clear build cache during CI

Appears there is an issue where the build cache grows unbounded until it hits Github's limit (https://github.com/docker/build-push-action/issues/252, https://github.com/moby/buildkit/issues/1896). Clear the cache after builds to prevent this 
