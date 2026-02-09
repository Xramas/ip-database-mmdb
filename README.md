# IP Info Database (MMDB Collection)

[![License](https://img.shields.io/github/license/Xramas/IP_INFO_DATABASE)](https://github.com/Xramas/IP_INFO_DATABASE/blob/master/LICENSE)
[![Last Update](https://img.shields.io/github/release-date/Xramas/IP_INFO_DATABASE)](https://github.com/Xramas/IP_INFO_DATABASE/releases/latest)

A repository for automated aggregation, update, and distribution of popular public IP geolocation databases in MMDB format.

---

## Quick Download (Latest Releases)

| Database Name | Source | Download Link |
| :--- | :--- | :--- |
| **IPinfo Lite** | IPinfo.io | [Download](https://github.com/Xramas/IP_INFO_DATABASE/releases/latest/download/ipinfo_lite.mmdb) |
| **Combined Geo-Whois** | Sapics/MaxMind | [Download](https://github.com/Xramas/IP_INFO_DATABASE/releases/latest/download/geolite2-geo-whois-asn-country.mmdb) |
| **GeoLite2 Country** | MaxMind | [Download](https://github.com/Xramas/IP_INFO_DATABASE/releases/latest/download/GeoLite2-Country.mmdb) |
| **DB-IP City Lite** | DB-IP | [Download](https://github.com/Xramas/IP_INFO_DATABASE/releases/latest/download/dbip-city-lite.mmdb) |

---

## Databases & Licenses

The data files distributed in this repository are governed by the terms of their original providers.

| Source | License Type | Attribution Requirement |
| :--- | :--- | :--- |
| **MaxMind GeoLite2** | [GeoLite2 EULA](https://www.maxmind.com/en/geolite2/eula) | Must state: "This product includes GeoLite2 data created by MaxMind." |
| **DB-IP Lite** | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) | Must provide a link to [db-ip.com](https://db-ip.com). |
| **IPinfo Free** | [CC BY-SA 4.0](https://ipinfo.io/products/free-ip-database) | Must provide a link back to [ipinfo.io](https://ipinfo.io). |

---

## Automation

This repository uses GitHub Actions to pull and repackage data every Monday (00:00 UTC). 

---

## Disclaimer & Limitation of Liability

* **Scope**: The MIT License of this repository applies to the **scripts and code only**, not to the binary `.mmdb` files.
* **Data Freshness**: The author does not guarantee the timeliness or accuracy of the data. IP allocations change frequently; use these files at your own discretion.
* **Compliance**: Users are responsible for ensuring their use of the data complies with the EULA/Terms of the respective providers. The author shall not be held liable for any damages or legal issues arising from the use of the data provided.
