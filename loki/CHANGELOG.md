# Changelog since v1.9.0
- Merge pull request #124 from mdegat01/aa-loki-access-proc-cpuset

AA - Allow Loki access to process cpuset 
- AA - Allow Loki access to process cpuset 
- Merge pull request #123 from mdegat01/aa-create-wal-folder

AA allow creation of wal folder in s6 services 
- AA allow creation of wal folder in s6 services 
- Merge pull request #121 from mdegat01/aa-fix-runtime-access-loki-2.4.0

Grant required runtime usage in AA profile 
- Grant required runtime usage in AA profile

Loki seems to require access to `/proc/cpuset` and the `wal` folder inside its s6 services directory as of the latest version. 
- Merge pull request #120 from mdegat01/ci-clear-build-cache

Cache management and one-at-a-time builds in CI 
- Clear cache in deploy and add turnstyle to builds 
- Clear build cache during CI

Appears there is an issue where the build cache grows unbounded until it hits Github's limit (https://github.com/docker/build-push-action/issues/252, https://github.com/moby/buildkit/issues/1896). Clear the cache after builds to prevent this. 
