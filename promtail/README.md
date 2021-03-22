# Home Assistant Add-on: Promtail

[![GitHub Release][releases-shield]][releases]
![Project Stage][project-stage-shield]
[![License][license-shield]](LICENSE.md)

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]

[![Github Actions][github-actions-shield]][github-actions]
![Project Maintenance][maintenance-shield]
[![GitHub Activity][commits-shield]][commits]

[Promtail][promtail] is an agent which ships the contents of local logs to a private
[Loki][loki] instance or [Grafana Cloud][grafana-cloud]. It is usually deployed
to every machine that has applications needed to be monitored.

⛔ **Known Issue** - This add-on is waiting on upcoming supervisor functionality
to function, specifically [this PR](https://github.com/home-assistant/supervisor/pull/2722).
Once that makes its way into the supervisor release I will update the add-on
to use the new `journald` config. Until then this add-on cannot scrape logs from
the system journal as promised. If you choose to use it before that you should set
`skip_default_scrape_config` to `true` and provide a file for `additional_scrape_configs`
as it will only be able to see log files created by add-ons.

[![Open your Home Assistant instance and show the add add-on repository dialog
with a specific repository URL pre-filled.][add-repo-shield]][add-repo]
[![Open your Home Assistant instance and show the dashboard of a Supervisor add-on.][add-addon-shield]][add-addon]

## WARNING! THIS IS AN EDGE REPOSITORY

This Add-ons repository contains edge builds of add-ons. Edge
builds add-ons are based upon the latest development version.

- They may not work at all.
- They might stop working at any time.
- They could have a negative impact on your system.

This repository was created for:

- Anybody willing to test.
- Anybody interested in trying out upcoming add-ons or add-on features.
- Developers.

If you are more interested in stable releases of these add-ons:

<https://github.com/mdegat01/hassio-addons>

## About

By default this addon version of Promtail will tail logs from the systemd
journal. This will include all logs from all addons, supervisor, home assistant,
docker, and the host system itself. In addition you can set it up to look for
local log files in `/share` or `/ssl` if you have a particular add-on that logs
to a file instead of to `stdout`.

## Support

Got questions?

You have several ways to get them answered:

- The Home Assistant [Community Forum][forum]. I am
  [CentralCommand][forum-centralcommand] there.
- The Home Assistant [Discord Chat Server][discord-ha]. Use the #add-ons channel,
  I am CentralCommand#0913 there.

You could also [open an issue here][issue] on GitHub.

## Authors & contributors

The original setup of this repository is by [Mike Degatano][mdegat01].

For a full list of all authors and contributors,
check [the contributor's page][contributors].

## License

MIT License

Copyright (c) 2021 mdegat01

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[add-addon-shield]: https://my.home-assistant.io/badges/supervisor_addon.svg
[add-addon]: https://my.home-assistant.io/redirect/supervisor_addon/?addon=7eb274d5_promtail
[add-repo-shield]: https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg
[add-repo]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fmdegat01%2Fhassio-addons
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[commits-shield]: https://img.shields.io/github/commit-activity/y/mdegat01/addon-promtail.svg
[commits]: https://github.com/mdegat01/addon-promtail/commits/main
[contributors]: https://github.com/mdegat01/addon-promtail/graphs/contributors
[discord-ha]: https://discord.gg/c5DvZ4e
[docs]: https://github.com/mdegat01/addon-promtail/blob/main/promtail/DOCS.md
[forum-centralcommand]: https://community.home-assistant.io/u/CentralCommand/?u=CentralCommand
[forum]: https://community.home-assistant.io?u=CentralCommand
[grafana-cloud]: https://grafana.com/products/cloud/
[loki]: https://grafana.com/oss/loki
[mdegat01]: https://github.com/mdegat01
[github-actions-shield]: https://github.com/mdegat01/addon-promtail/workflows/CI/badge.svg
[github-actions]: https://github.com/mdegat01/addon-promtail/actions
[i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[issue]: https://github.com/mdegat01/addon-promtail/issues
[license-shield]: https://img.shields.io/github/license/mdegat01/addon-promtail.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2021.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-yellow.svg
[promtail]: https://grafana.com/docs/loki/latest/clients/promtail/
[releases-shield]: https://img.shields.io/github/release/mdegat01/addon-promtail.svg
[releases]: https://github.com/mdegat01/addon-promtail/releases
