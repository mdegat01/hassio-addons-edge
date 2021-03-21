# EDGE - mdegat01's Home Assistant Add-ons

⚠ **Pre-Alpha Stage** - If you stumbled across this, it's in a very early stage.
Expect issues and things may change at any time.

[![Open your Home Assistant instance and show the add add-on repository dialog
with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fmdegat01%2Fhassio-addons-edge)

A hopefully useful collection of HA add-ons made by mdegat01.

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

If you are more interested in stable releases of our add-ons:

<https://github.com/mdegat01/hassio-addons>

## Add-ons provided by this repository

### &#10003; [Loki][addon-loki]

[Grafana Loki](https://grafana.com/oss/loki/) is a horizontally-scalable,
highly-available, multi-tenant log aggregation system inspired by Prometheus. It
is designed to be very cost effective and easy to operate. It does not index the
contents of the logs, but rather a set of labels for each log stream.

[:books: loki add-on documentation][addon-doc-loki]

### &#10003; [Promtail][addon-promtail]

[Promtail](https://grafana.com/docs/loki/latest/clients/promtail/) is an agent
which ships the contents of local logs to a private [Loki](https://grafana.com/oss/loki)
instance or [Grafana Cloud](https://grafana.com/products/cloud/). It is usually
deployed to every machine that has applications needed to be monitored.

[:books: promtail add-on documentation][addon-doc-promtail]
