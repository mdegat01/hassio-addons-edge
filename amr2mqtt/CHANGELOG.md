# Changelog since v0.0.1
- Use dictionaries correctly 
- Merge pull request #34 from mdegat01/permissions-on-data

Grant read permission on /data 
- Grant read permission on /data 
- Trim base ids list as well 
- Echo ids to get value in bash 
- Merge pull request #33 from mdegat01/per-meter-config

Change config to be based around meters 
- Change config to be based around meters 
- Merge pull request #32 from mdegat01/remove-discovery-mode

Remove discovery mode 
- Remove unused link 
- Remove discovery mode 
- Merge pull request #31 from mdegat01/add-scmplus-r900

Add scm+ and r900 support 
- Add scm+ and r900 support 
- Merge pull request #30 from mdegat01/fix-list-config-parsing

Fix handling list configs 
- Fix handling list configs 
- Doc tweaks 
- Merge pull request #29 from mdegat01/docs-and-discovery-mode

Fill in documentation and add discovery mode 
- Fix ordered list for MD029 
- Fill in documentation and add discovery mode 
- Merge pull request #28 from mdegat01/quiet-rtl_tcp

Quiet `rtl_tcp` based on `log_level` 
- Quiet rtl_tcp based on log level 
- Multiplier must be cast to float now 
- Merge pull request #27 from mdegat01/fix-reading-multiplier

Change `wh_multiplier` to `reading_multiplier` 
- Also change option in doc 
- `wh_multiplier` to more `reading_multiplier` 
- Merge pull request #26 from mdegat01/keepalive-mqtt-connection

Keep connection to MQTT broker while running 
- Keep connection to MQTT broker while running 
- Merge pull request #25 from mdegat01/fix-auth-settings

Using incorrect EV name for auth 
- Using incorrect EV name for auth 
- Merge pull request #24 from mdegat01/missing-port-config

Missing port config option 
- Missing port config option 
- Merge pull request #23 from mdegat01/correct-ssl-certs

Use `/ssl` for ca cert and not for client certs 
- Use /ssl for ca cert and not for client certs 
- Wrong field for meter ID in SCM 
- Merge pull request #22 from mdegat01/run-rtl_tcp-root

Don't run rtl_tcp as a user 
- Don't run rtl_tcp as a user 
- Fix type in bashio 
- Merge pull request #21 from mdegat01/rtl-tcp-separate-service

Start `rtl_tcp` as a separate managed service 
- Newlines at end of script files 
- Start rtl_tcp as a separate managed service 
- Merge pull request #20 from mdegat01/use-built-in-id-filter

Use `rtlamr`'s built-in ID filter 
- Use rtlamr's built-in ID filter 
- Merge pull request #19 from mdegat01/fix-interval-test

Initialize `interval_cur` so check works 
- Initialize `interval_cur` so check works 
- Merge pull request #18 from mdegat01/fix-generated-readme

Use new name in generated readme 
- Use new name in generated readme 
- Merge pull request #17 from mdegat01/change-name-amr2mqtt

Change name to `amr2mqtt` 
- Fix old name references in Dockerfile 
- Addon name change to amr2mqtt 
- Merge pull request #16 from mdegat01/fix-f-strings

Incorrect syntax for f strings 
- Incorrect syntax for f strings 
- Merge pull request #15 from mdegat01/fix-message-types-enum

Fix message types config option 
- Fix message types config option 
- Merge pull request #14 from mdegat01/fix-message-types-config

Fix message types config option 
- Fix message types config option 
- Merge pull request #13 from mdegat01/add-scm-support

Add support for scm type messages 
- Add support for scm type messages 
- Merge pull request #12 from mdegat01/add-usb-support

Add USB to add-on config 
- Add USB to add-on config 
- Merge pull request #11 from mdegat01/config-rtl-sdr

Map udev and add rtl-sdr config/rules 
- Map udev and add rtl-sdr config/rules 
- Merge pull request #10 from mdegat01/bug-fixes

Fix log level, settings and example config 
- Fix log level, settings and example config 
- Merge pull request #8 from mdegat01/remove-pr-template

Inherit org's pull request template 
- Inherit org's pull request template 
- Merge pull request #7 from mdegat01/remove-release-drafter-template

Inherit org's release drafter template 
- Inherit org's release drafter template 
- Merge pull request #6 from mdegat01/add-pr-template

Add a PR template 
- Add a PR template 
- Merge pull request #5 from mdegat01/recover-release-drafter-tempalte

Recover release drafter template 
- Recover release drafter template 
- Merge pull request #4 from mdegat01/deploy-ghcr-token

Pass ghcr token to deploy workflow 
- Pass ghcr token to deploy workflow 
- Merge pull request #3 from mdegat01/centralized-workflows

Switch to centralized GitHub Actions workflows 
- Centralize other basic workflows 
- Version as dev and use correct repo 
- Switch to centralized workflows 
- Merge pull request #2 from mdegat01/deploy-use-yaml

Use yq instead of jq in deploy 
- Use yq instead of jq in deploy 
- Merge pull request #1 from mdegat01/initial-commit

Initial state of the addon 
- Initial docs and support new settings 
- Add user correctly for debian 
- rtlamr binary is already correct name 
- yq not jq since config is yaml now 
- No i386 support 
- Missing yaml document start 
- Initial state of the addon 
