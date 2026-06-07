# Case study: AIAuditLab

AIAuditLab on paikallinen työtila AI-näkyvyyden, prompt-pohjien, AI-vastausten, manuaalisten löydösten ja arviointien hallintaan.

## Tilanne

Markkinointi- tai sisältötiimi haluaa ymmärtää, miten AI-avusteiset hakupalvelut ja kielimallit tulkitsevat yrityksen verkkosisältöjä.

Ongelma ei ole vain se, että AI:ta pitäisi kokeilla. Ongelma on se, että kokeiluista pitäisi saada toistettava ja tarkistettava työnkulku.

## Mitä tässä rakennettiin

AIAuditLab kokoaa samaan paikalliseen työtilaan:

- tarkistettavat sivut
- sivun taustatiedot
- prompt-pohjat
- AI-vastaukset
- vastausten vertailun
- manuaaliset löydökset
- pisteytykset ja tarkistushistorian

Tavoite on muuttaa yksittäiset AI-kokeilut hallituksi arviointiprosessiksi.

## Työnkulku

1. Valitaan tarkistettava sivu.
2. Täydennetään sivun taustatiedot.
3. Renderöidään prompt-pohja.
4. Kopioidaan prompt AI-työkaluun.
5. Liitetään vastaus takaisin työtilaan.
6. Kirjataan löydökset.
7. Tehdään manuaalinen arvio.
8. Tallennetaan tarkistushistoria.

## Screenshots

### Run overview

![AIAuditLab run overview](../../assets/screenshots/ai-audit-lab/ai-audit-lab-run-overview.png)

Run overview näyttää yksittäisen tarkistusajon kontekstin: mikä sivu on arvioinnissa, mikä oli odotettu sivutyyppi, mikä on ensisijainen entiteetti, montako AI-vastausta on mukana ja montako löydöstä tarkistuksessa syntyi.

### Scorecard comparison

![AIAuditLab scorecard comparison](../../assets/screenshots/ai-audit-lab/ai-audit-lab-scorecard-comparison.png)

Scorecard comparison näyttää, miten eri AI-vastauksia voidaan vertailla yhteisellä arviointirungolla. Tarkoitus ei ole automatisoida päätöstä, vaan tehdä vertailusta näkyvämpää ja toistettavampaa.

### Findings

![AIAuditLab findings](../../assets/screenshots/ai-audit-lab/ai-audit-lab-findings.png)

Findings-näkymä kokoaa yksittäiset havainnot tarkistettavaksi listaksi. Löydöksillä on tyyppi, vakavuus, tila ja tiivistelmä, jolloin AI-vastauksesta syntyy jatkokäsiteltävää työaineistoa.

## Miksi tämä on arvokasta

AIAuditLab tekee AI-aiheen käsittelystä käytännöllistä. Se ei jää ideatasolle, vaan näyttää miten tiimi voisi arvioida sisältöjä, vastauksia ja löydöksiä järjestelmällisesti.

## Rajaus

Demo on paikallinen työnkulku- ja arviointityökalu. Se ei ole tuotantojärjestelmä eikä se julkaise asiakasdataa.

## Linkit

- [Portfolio landing page](../../index.html)
- [AIAuditLab scenario](../../scenarios/ai-audit-lab-scenario.md)
- [AIAuditLab demo description](../../demos/01-ai-audit-lab/README.md)
