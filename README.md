# Handtekening-generator Cooper Projectrealisatie

Statische pagina: vul gegevens in, kopieer de handtekening, plak in Gmail.

- `index.html` – de tool (geen build, geen backend)
- `assets/` – logo en iconen (Gmail laadt deze via https, dus de pagina moet op https staan)
- `build-icons.mjs` – maakt de icoon-PNG's opnieuw (optioneel, vereist playwright)

Bedrijfsgegevens en kleuren staan bovenin het `<script>` in `index.html`.
Logo vervangen: `assets/logo.png` overschrijven (nu 600 px breed, gerenderd uit de EPS).
