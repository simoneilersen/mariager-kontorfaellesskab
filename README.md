# Mariager Kontorfællesskab – landing page

En enkel, statisk landingsside til Mariager Kontorfællesskab, der bruger de eksisterende logoer og lokale-billeder fra mappen `pictures/`.

## Struktur

- `index.html` – selve landingssiden
- `styles.css` – styling og layout
- `pictures/` – logoer og billeder af lokaler (allerede i dit projekt)

Siden er bygget som en klassisk landing page med:

- Hero-sektion med logo, payoff og call-to-action
- Afsnit om kontorfællesskabet og hvem det passer til
- Oversigt over faciliteter
- Galleri med billeder af lokalerne
- Simpel pris-/mulighedssektion
- Kontaktsektion (visuel formular uden backend)

## Sådan ser du siden lokalt

I projektmappen:

```bash
cd "/Users/simoneilersen/Library/Mobile Documents/com~apple~CloudDocs/Github/kontorfællesskab"
python3 -m http.server 8000
```

Åbn derefter i din browser:

- `http://localhost:8000/`

## Tilpasning

- Ret tekst, kontaktoplysninger og evt. priser direkte i `index.html`.
- Hvis du vil ændre farver, fonte og generelt udtryk, gør du det i `styles.css`.
- Du kan frit bytte billederne i galleriet ud ved at ændre `src`-stierne i sektionen "Lokalerne" i `index.html`.
