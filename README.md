# Handtekening-generator Cooper Projectrealisatie

Statische pagina: vul gegevens in, kopieer de handtekening, plak in Gmail.

- `index.html` – de tool (geen build, geen backend)
- `assets/` – logo en iconen (Gmail laadt deze via https, dus de pagina moet op https staan)
- `build-icons.mjs` – maakt de icoon-PNG's opnieuw (optioneel, vereist playwright)

Bedrijfsgegevens en kleuren staan bovenin het `<script>` in `index.html`.
Logo vervangen: `assets/logo.png` overschrijven (nu 600 px breed, gerenderd uit de EPS).

## Klanten

| Pad | Klant |
|---|---|
| `/` | Cooper Projectrealisatie |
| `/parrot/` | Parrot Agency |

Elke klant heeft een eigen map met `index.html` en `assets/`. De afbeeldings-URL's in de handtekening worden afgeleid van het adres van de pagina.
Parrot-logo: `LOGO_FILE` bovenin het script kiest `logo-halo.png` (standaard), `logo-black.png` of `logo-white.png`.
