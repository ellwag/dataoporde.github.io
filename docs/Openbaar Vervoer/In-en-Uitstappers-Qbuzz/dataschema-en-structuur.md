---
layout: default
title: Dataschema en structuur
grand_parent: Openbaar Vervoer
parent: In en Uitstappers Qbuzz
permalink: docs/openbaar-vervoer/in-en-uitstappers-qbuzz/dataschema-en-structuur
nav_order: 2
---

# Dataschema en structuur 

{: .no_toc }

Datum laatste aanpassing: 28-06-2024

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>

----

| Centralisatie     |      |
| ----------------- | ---- |
| Naar de database? | Ja   |

| dim_station          | Toelichting                               | Voorbeeld (optioneel) |
| -------------------- | ----------------------------------------- | --------------------- |
| **stationID**        | Uniek nummer voor iedere rij van de tabel |                       |
| **stationNaam**      | Naam van bus/tramhalte                    |                       |
| **stationHaltecode** | Unieke code voor de halte                 | 59152830              |
| **geometrieID**      | Verwijst naar de dim_geometrie tabel      |                       |

| dim_uur   | Toelichting                               | Voorbeeld (optioneel) |
| --------- | ----------------------------------------- | --------------------- |
| **uurID** | Uniek nummer voor iedere rij van de tabel |                       |
| **uur**   | Tijdsvak weergegeven als geheel getal     | 12 (12:00 - 12:59)    |

| dim_dag       | Toelichting                               | Voorbeeld (optioneel)                        |
| ------------- | ----------------------------------------- | -------------------------------------------- |
| **dagTypeID** | Uniek nummer voor iedere rij van de tabel | 1,2,3 voor werkdag, za en zo respectievelijk |
| **werkdag**   | Geeft aan of het een werkdag is           |                                              |
| **zaterdag**  | Geeft aan of het een zaterdag is          |                                              |
| **zondag**    | Geeft aan of het een zondag is            |                                              |

---

