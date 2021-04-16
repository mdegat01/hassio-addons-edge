# Changelog since v1.0.2
- Merge pull request #38 from mdegat01/update-addon-base

Bump addons base to `9.1.7` 
- Bump addons base to `9.1.7` 
- Merge pull request #37 from mdegat01/dependabot/github_actions/brpaz/hadolint-action-v1.4.0

Bump brpaz/hadolint-action from v1.3.1 to v1.4.0 
- Bump brpaz/hadolint-action from v1.3.1 to v1.4.0

Bumps [brpaz/hadolint-action](https://github.com/brpaz/hadolint-action) from v1.3.1 to v1.4.0.
- [Release notes](https://github.com/brpaz/hadolint-action/releases)
- [Changelog](https://github.com/hadolint/hadolint-action/blob/master/.releaserc)
- [Commits](https://github.com/brpaz/hadolint-action/compare/v1.3.1...473e36ba306c199243ffe4f1e652a8b60a8fa296)

Signed-off-by: dependabot[bot] <support@github.com> 
- Merge pull request #36 from mdegat01/aa-amd64

Support amd64 with custom apparmor profile 
- Add overlay variable for opt 
- Add /usr/lib/locale with overlay path 
- Support amd64 with custom apparmor profile 
- Merge pull request #35 from mdegat01/dependabot/github_actions/actions/cache-v2.1.5

Bump actions/cache from v2.1.4 to v2.1.5 
- Bump actions/cache from v2.1.4 to v2.1.5

Bumps [actions/cache](https://github.com/actions/cache) from v2.1.4 to v2.1.5.
- [Release notes](https://github.com/actions/cache/releases)
- [Commits](https://github.com/actions/cache/compare/v2.1.4...1a9e2138d905efd099035b49d8b7a3888c653ca8)

Signed-off-by: dependabot[bot] <support@github.com> 
- Merge pull request #34 from mdegat01/aa-add-my.cnf.d

Add my.cnf.d and proc loadavg to aa profile 
- Add my.cnf.d and proc loadavg to aa profile 
- Merge pull request #33 from mdegat01/aa-add-proc-stat

Missing proc stat and couple files from aa profile 
- Missing proc stat and couple files from aa profile 
- Merge pull request #32 from mdegat01/add-apparmor

Add custom apparmor profile 
- Updated profile after local testing 
- Add apparmor profile 
- Merge pull request #31 from mdegat01/use-dsaparam

Use dsaparam option to generate dhparam for ssl 
- Use dsaparam option to generate dhparam for ssl

Generating a 4096 bit dhparam takes too long on a pi-like device, use `dsaparam` like the NGinx add-on does. 
- Merge pull request #30 from mdegat01/devcontainer-dev

Add devcontainer config 
- Merge branch 'main' into devcontainer-dev 
- Prettier for json files 
- Add devcontainer config 
- Merge pull request #28 from mdegat01/stable-to-beta

Deploys to stable also go to beta 
- Merge branch 'main' into stable-to-beta 
- Merge pull request #29 from mdegat01/node-update-14.16.1-r1

Update to nodejs & npm `14.16.1-r1` 
- Update to nodejs & npm `14.16.1-r1`

Update to latest nodejs and npm version 
- Deploys to stable also go to beta

New stable releases should also update the beta 
- Merge pull request #27 from mdegat01/generate-dhparamfile

Deprecate `dhparamfile` option, generate it instead 
- Small typo 
- Don't generate /data/ssl, not needed 
- Permissions of new dhparam file 
- Deprecate dhparamfile, generate it instead 
- Merge pull request #26 from mdegat01/config-is-empty

Use not is empty instead of exists for UI 
- Use not is empty instead of exists for UI 
- Merge pull request #25 from mdegat01/beta-support

Add support for beta environment 
- Add support for beta environment 
- Merge pull request #23 from mdegat01/dependabot/github_actions/docker/setup-qemu-action-v1.0.2

Bump docker/setup-qemu-action from v1.0.1 to v1.0.2 
- Bump docker/setup-qemu-action from v1.0.1 to v1.0.2

Bumps [docker/setup-qemu-action](https://github.com/docker/setup-qemu-action) from v1.0.1 to v1.0.2.
- [Release notes](https://github.com/docker/setup-qemu-action/releases)
- [Commits](https://github.com/docker/setup-qemu-action/compare/v1.0.1...25f0500ff22e406f7191a2a8ba8cda16901ca018)

Signed-off-by: dependabot[bot] <support@github.com> 
- Bump docker/setup-buildx-action from v1.1.1 to v1.1.2 (#22) 
- Merge pull request #24 from mdegat01/bump-nodejs

Update nodejs/npm to `14.16.1-r0` 
- Update nodejs/npm to 14.16.1-r0 
- Merge pull request #21 from mdegat01/dependabot/github_actions/docker/build-push-action-v2.4.0

Bump docker/build-push-action from v2.3.0 to v2.4.0 
- Bump docker/build-push-action from v2.3.0 to v2.4.0

Bumps [docker/build-push-action](https://github.com/docker/build-push-action) from v2.3.0 to v2.4.0.
- [Release notes](https://github.com/docker/build-push-action/releases)
- [Commits](https://github.com/docker/build-push-action/compare/v2.3.0...e1b7f96249f2e4c8e4ac1519b9608c0d48944a1f)

Signed-off-by: dependabot[bot] <support@github.com> 
