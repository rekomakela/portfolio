# Publication checklist

Tämän listan tarkoitus on varmistaa, että portfolio on turvallinen, selkeä ja helppo arvioida ennen kuin sitä näytetään ulkopuoliselle.

## 1. Sisältö

- Jokaisella päädemolla on selkeä ongelma.
- Jokaisella päädemolla on selkeä ratkaisu.
- Jokaisella päädemolla on kohta: mitä osaamista tämä näyttää.
- Jokaisella päädemolla on kohta: mikä arvo tästä syntyy.
- README kertoo heti, miksi repo on olemassa.
- Landing page avautuu paikallisesti selaimessa.

## 2. Kuvakaappaukset

- Jokaisesta päädemosta on vähintään yksi kuvakaappaus.
- Kuvakaappaus näyttää työnkulun, ei pelkkää tyhjää käyttöliittymää.
- Kuvakaappauksessa ei näy asiakasdataa.
- Kuvakaappauksessa ei näy salaisuuksia, API-avaimia tai sisäisiä tunnisteita.
- Kuvakaappauksen nimi on selkeä.

## 3. Data ja turvallisuus

- Repo ei sisällä palvelutiliavaimia.
- Repo ei sisällä `.env`-tiedostoja.
- Repo ei sisällä oikeaa asiakasdataa.
- Repo ei sisällä henkilötietoja.
- Repo ei sisällä sisäisiä tiedostopolkuja, joita ei ole tarkoitettu ulkopuoliselle.
- `.DS_Store` on ignoroitu.

## 4. Arvioijan käyttökokemus

- `README.md` kertoo, mistä aloittaa.
- `docs/reviewer-guide.md` kertoo lukujärjestyksen.
- `index.html` antaa nopean yleiskuvan.
- Linkit toimivat.
- Demoista näkee nopeasti, mitä ne todistavat osaamisesta.

## 5. Ennen julkaisua

- Aja `git status --short`.
- Tarkista muuttuneet tiedostot.
- Avaa `index.html` selaimessa.
- Lue `README.md` GitHubin näkökulmasta.
- Poista tai siirrä keskeneräinen tutkimusmateriaali, jos repo muutetaan julkiseksi.
