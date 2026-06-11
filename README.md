# Fonts Adservio

**Spécimen interactif : [adservio.github.io/adservio-fonts](https://adservio.github.io/adservio-fonts/)**

![Spécimen Adservio Fonts](docs/images/specimen-hero.png)

Quatre familles de caractères pour l'identité Adservio. Toutes sous licence SIL Open Font License 1.1 (OFL.txt dans chaque dossier).

## Familles

| Famille | Usage | Graisses | Origine |
|---|---|---|---|
| **Adservio Sans** | Texte, UI, titres | Light 300 → Bold 700, roman + italique, variable | Inclusive Sans (modifiée) |
| **Adservio Serif** | Éditorial | Light 300 → Bold 700, roman + italique, variable | Junicode |
| **Adservio Mono** | Code | Thin 100 → ExtraBold 800, roman + italique, variable | JetBrains Mono |
| **Adservio Pixel** | Display | 5 styles : Square, Circle, Grid, Line, Triangle | Geist Pixel |

## Particularités d'Adservio Sans

- « a » et « g » simplifiés (simple étage) par défaut
- Zéro sans barre
- G majuscule à coin de fût arrondi
- J majuscule avec barre et point
- Ligatures actives par défaut : ff, ffi, fi (avec point), fl, ft

## Contenu de chaque dossier

- `ttf/` — statiques TrueType (usage bureautique, installation système)
- `otf/` — statiques OpenType CFF (Adservio Sans uniquement)
- `variable/` — fonts variables (axe de graisse)
- `webfonts/` — WOFF2 pour le web

## Utilisation web

```css
@font-face {
  font-family: "Adservio Sans";
  src: url("AdservioSans/webfonts/AdservioSans[wght].woff2") format("woff2");
  font-weight: 300 700;
  font-style: normal;
}
@font-face {
  font-family: "Adservio Sans";
  src: url("AdservioSans/webfonts/AdservioSans-Italic[wght].woff2") format("woff2");
  font-weight: 300 700;
  font-style: italic;
}
```

## Spécimen

![Graisses et styles](docs/images/specimen-weights.png)

![Ligatures](docs/images/specimen-ligatures.png)

![Grille de glyphes et métriques](docs/images/specimen-glyphs.png)

![Prévisualisation d'un glyphe avec lignes de métriques](docs/images/specimen-preview-G.png)

Version en ligne : [adservio.github.io/adservio-fonts](https://adservio.github.io/adservio-fonts/) — ou ouvrir `specimen.html` à la racine du package : testeur interactif (taille, interligne, espacement, graisses, italique), grille complète des glyphes et prévisualisation avec lignes de métriques pour les quatre familles.

## Auteur

Familles réalisées par **Anis ZOUAOUI**, en s'inspirant de superbes fonts open source.

## Remerciements

Ces familles sont des dérivées de fonts open source remarquables, que nous remercions chaleureusement :

- **[Inclusive Sans](https://github.com/LivKing/Inclusive-Sans)** d'Olivia King — base d'Adservio Sans, une linéale pensée pour la lisibilité et l'accessibilité.
- **[Junicode](https://github.com/psb1558/Junicode-font)** de Peter S. Baker — base d'Adservio Serif, une serif érudite au répertoire exceptionnel.
- **[JetBrains Mono](https://github.com/JetBrains/JetBrainsMono)** de JetBrains — base d'Adservio Mono, référence des fonts de code avec ses ligatures de programmation.
- **[Geist Pixel](https://github.com/vercel/geist-font)** de Vercel — base d'Adservio Pixel et de ses cinq trames display.

Conformément à la licence OFL, les mentions de copyright d'origine sont conservées dans les fichiers et les noms d'origine ne sont pas réutilisés. Merci à ces créatrices et créateurs de publier leur travail en open source — ce package n'existerait pas sans eux.
