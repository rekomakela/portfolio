# SearchAudit

## Ongelma

Hakudata, sisäisen haun termit ja sisältöjen kehitysideat jäävät helposti irrallisiksi listoiksi.

Ilman yhteistä työjonoa on vaikea päättää:

- mitkä termit ovat oikeasti relevantteja?
- mitkä kannattaa hyväksyä jatkokäsittelyyn?
- mitkä ovat riskisiä?
- mitä käyttäjä odottaa löytävänsä?
- miten havainnot viedään seuraavaan tarkistukseen?

## Ratkaisu

SearchAudit on paikallinen työkalu sisäisen haun termikandidaattien manuaaliseen arviointiin.

Se tukee termien tuontia, luokittelua, tarkistustiloja, kohdesivuprofiilia, tarkistuspakettien vientiä ja suositusmatriisia.

## Mitä demo näyttää

- termikandidaattien tuonti ja muokkaus
- review / approved / rejected -työnkulku
- kohdesivuprofiilin määrittely
- ChatGPT-promptin muodostaminen manuaaliseen käyttöön
- tarkistuspaketin vienti
- suositusmatriisi ihmisen tarkistettavaksi
- paikallinen FastAPI + SvelteKit -sovellus

## Mitä osaamista tämä näyttää

- SEO- ja sisäisen haun kehittäminen
- termikandidaattien arviointiprosessi
- työnkulkujen suunnittelu
- paikallisten työkalujen rakentaminen
- analyysin muuttaminen vientitiedostoiksi
- Python-, FastAPI- ja SvelteKit-pohjainen työkalukehitys

## Arvo asiakkaalle

SearchAudit näyttää, miten hakukäyttäytymiseen liittyvät havainnot voidaan muuttaa selkeäksi arviointi- ja vientiprosessiksi.

Tämä auttaa tiimejä välttämään sen, että termilistoja käsitellään satunnaisesti tai ilman yhteistä päätösmallia.

## Rajaukset

- Ei tee automaattisia CMS-muutoksia.
- Ei kutsu LLM-rajapintaa automaattisesti.
- Ei korvaa ihmisen tekemää arviointia.
- Käyttää paikallista tarkistus- ja vientityönkulkua.
