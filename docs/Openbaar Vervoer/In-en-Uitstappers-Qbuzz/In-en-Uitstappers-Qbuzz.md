---
layout: default
title: In en Uitstappers Qbuzz
parent: Openbaar Vervoer
has_children: true
permalink: docs/openbaar-vervoer/in-en-uitstappers-qbuzz
nav_order: 1


---

# In en Uitstappers Qbuzz

{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>



---

## Algemene informatie

Deze dataset bevat gegevens over het aantal passagiers dat in en uitstapt bij verschillende tram en bushaltes in de regio. Elke bushalte wordt geindentficieerd door een unieke haltecode en de bijbehorende straatnaam. De dataset maakt onderscheid tussen de aantallen passagiers tijdens werkdagen en weekenden (zaterdag/zondag). Bovendien zijn er voor sommige straten twee bushaltes, dit wordt aangegeven door een extra haltecode.

Momenteel wordt de ruwe dataset getransformeerd door weeknummers en jaarnummers toe te voegen aan de Exel bestanden, hier heeft Coen van Tooren een script voor geschreven.

De haltecode is van bijzonder belang omdat deze ook voorkomt in andere datasets zoals ["Buslijnen Netwerk"]() en ["Toegankelijkheid Bushaltes"](). Door de datasets te koppelen op basis van deze gemeenschappelijke kolom kunnen we waardevolle nieuwe inzichten verkrijgen.

---

## Metadata

| Afhankelijkheden |                 |
| ---------------- | --------------- |
| Monitors         | Mobiliteitsplan |

| Databron     |           |
| ------------ | --------- |
| Databronnaam | Translink |
| Dataformaat  | CSV       |

| Datalevering                |                                                             |
| --------------------------- | ----------------------------------------------------------- |
| Leverancier                 | Roy van den Berg <Translink, roy.van.den.berg@translink.nl> |
| Leveringsmethode            | E-mail                                                      |
| Huidige frequentie levering | Incidenteel                                                 |
| Wens rondom frequentie      | Jaarlijks                                                   |

| Dataopslag                                |                                                              |
| ----------------------------------------- | ------------------------------------------------------------ |
| Opslaglocatie ruwe data                   | W:\SO\MM\MBZ\02 Modaliteitsdata\04 OV\01 Bus en Tram\01 In en Uitstappers (Qbuzz)\02 Ruwe Data |
| Opslaglocatie bewerkte data               | W:\SO\MM\MBZ\02 Modaliteitsdata\04 OV\01 Bus en Tram\01 In en Uitstappers (Qbuzz)\03 Bewerkte Data |
| Verantwoordelijke collega/contact persoon | Sander van Weperen <Gemeente Utrecht, sander.van.weperen@utrecht.nl> |

---

## Datatransformaties

- Toevoegen van jaar en weeknummer aan de kolommen
  - **Tijdsduur om data te transformeren**:  10-20 minutes
- Data reduceren naar enkel haltes in Utrecht doormiddel van een filter
  - **Tijdsduur om data te transformeren**:  10-20 minutes

---

## Databetrouwbaarheid en kwaliteit

**Probleem**: De dataleverancier is de Provincie Utrecht en deze maakt regelmatig fouten zoals de actualiteit van de bus en tramhalte informatie.

**Frequentie van data kwaliteitswaarborging dataset**: Op moment van aanlevering.

**Oplossing**: Meer checks op de data die geleverd wordt voorafgaand een data analyse om zo te bepalen hoe goed die data aansluit op het bus en tramhalte netwerk in de realiteit.

----

## Data - gebruik en toegang

Deze dataset is algemeen beschibaar en is geanominiseerd 

---

## Dataverrijkingsmogelijkheden

### Potentiele dataverrijkingsbron: KNMI

- **Is er een barrière voor deze dataverrijking?**: 
  - Gemiddelde waarden voor "werkdag" geeft te onnauwkeurig inzicht om het effect van het weer te kunnen bepalen op moment-basis
- **Voorwaarden voor gebruik dataverrijking?**: Exacte data voor de werkdagen
- **Voordelen van deze dataverrijking voor het team?**: Inzicht in het effect van het weer op OV gebruik/overstap bewegingen van Qbuzz in en uitstappers

----

## Handleiding

[Sharepoint - Mobiliteitsonderzoek: Handleiding Verwerken In en Uitstappers Qbuzz](https://utrechtcloud.sharepoint.com/:w:/r/sites/Mobiliteitsonderzoek_OORBIIPM/_layouts/15/Doc.aspx?sourcedoc={4FE06C0D-C6F7-4026-845E-DA79E4E0D6FD}&file=Handleiding verwerken In en uitstappers QBuzz.docx&wdLOR=cA268D0BC-CBAE-422D-B15B-2345CAAFB8F5&action=default&mobileredirect=true)

