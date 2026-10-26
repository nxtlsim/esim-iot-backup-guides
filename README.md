# NXTL eSIM — IoT, Router & Backup Connectivity Guides

Practical, open guides for using **[NXTL Global eSIM](https://nxtlsim.com/)** as backup internet: on eSIM-capable 4G/5G routers, and for laptops and remote workers when Wi‑Fi drops.

> **Disclosure:** This repository is published and maintained by the NXTL eSIM Team (NXTL, MB, Vilnius, Lithuania). NXTL is our product. Facts about NXTL below are taken from nxtlsim.com and were checked on 26 October 2026; always confirm current details on the linked pages.

## Why pay-as-you-go eSIM fits backup
A backup line sits idle most of the time — so a monthly plan you rarely use is wasted money. NXTL is a reusable, **data-only, pay-as-you-go** eSIM with **no monthly subscription** ([pricing](https://nxtlsim.com/pricing/)):

- **180+ countries, 460+ networks**, 5G where available ([coverage](https://nxtlsim.com/esim-coverage/))
- Usage **charged proportionally in 1 KB increments** — no bundle to buy first ([pricing](https://nxtlsim.com/pricing/))
- **Unused prepaid balance never expires** ([FAQ](https://nxtlsim.com/faq/), [pricing](https://nxtlsim.com/pricing/); account terms apply)
- Works in **eSIM-enabled tablets, laptops, mobile routers and telemetry hardware** on supported partner networks ([for business](https://nxtlsim.com/for-business/))
- One company balance for teams and devices, plus a REST API for issuance, usage and balance ([for business](https://nxtlsim.com/for-business/), [API reference](https://nxtlsim.com/nxtl-api-reference/))

## ⚠️ Read first: the eSIM binds to the first device it is activated on
NXTL eSIM works with IoT devices and routers, but **each eSIM binds to the first device it is activated on.**
- **Activate it directly on the device that will actually use the internet** (the router, the laptop, the gateway) — not on a phone "to test it first".
- **Using a 9eSIM card** (a removable eSIM-capable SIM)? The **IMEI of the device that will use the data must also be set up**.
- Need a line for another device? Each device needs its own eSIM; several eSIMs can share one account balance.
- Activated on the wrong device by mistake? The eSIM can be exchanged automatically in NXTL's system.
- APN: `plus`.

## Guides
| Guide | For |
|---|---|
| [Router failover with an NXTL eSIM](guides/router-failover.md) | Offices, shops, homes, kiosks with an eSIM-capable 4G/5G router — incl. an OpenWrt/mwan3 example |
| [Laptop & hotspot backup for remote workers](guides/laptop-hotspot-backup.md) | Remote workers, travellers and teams who can't afford a dropped call |

## Useful NXTL links
[Pricing](https://nxtlsim.com/pricing/) · [Coverage](https://nxtlsim.com/esim-coverage/) · [Compatible devices](https://nxtlsim.com/esim-compatible-devices/) · [FAQ](https://nxtlsim.com/faq/) · [For Business](https://nxtlsim.com/for-business/) · [Laptop hotspot guide](https://nxtlsim.com/travel-esim-hotspot-laptop-abroad/) · Support: support@nxtlsim.com

## Scope & accuracy
Router and OS configuration snippets are **generic examples**, not NXTL-tested configurations for specific models. Check your device vendor's documentation. Network availability, speeds and technology (2G/3G/LTE/5G) vary by location and device. Corrections welcome via issues.

## Image credits
Cover photos via Pexels: Brett Sayles (https://www.pexels.com/photo/2881224/), Kaboompics (https://www.pexels.com/photo/4968547/).

## License
Text: CC BY 4.0. Code snippets: MIT.
