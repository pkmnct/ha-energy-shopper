# Energy Shopper for Home Assistant

Ranks Pennsylvania gas and electric supplier offers (PA Gas Switch, PA Power Switch) against your own usage and current rate, including Duquesne Light Time-of-Use, and tells you when switching pays: sensors, repair issues and an event for notifications.

**Unofficial.** Not affiliated with the utilities or the PA PUC. See the
[source repository](https://github.com/pkmnct/pa-power-notifier) for how it works, the full setup guide and issues.

## Install

With [HACS](https://hacs.xyz): HACS → ⋮ → Custom repositories → add this repository's URL
as an **Integration**, then install **Energy Shopper (PA energy offers)** and restart Home Assistant.

Manually: copy `custom_components/energy_shopper/` into your Home Assistant `config/custom_components/`
and restart.

Then Settings → Devices & services → Add integration → **Energy Shopper (PA energy offers)**.

Setup guide: [https://github.com/pkmnct/pa-power-notifier/blob/main/docs/home-assistant.md#energy-shopper](https://github.com/pkmnct/pa-power-notifier/blob/main/docs/home-assistant.md#energy-shopper)

Requires Home Assistant 2026.2.0 or newer. Version 0.1.0.

This repository is generated from [pa-power-notifier](https://github.com/pkmnct/pa-power-notifier); please open
issues and pull requests there.
