# Zeespons.com

De centrale hub voor digitale projecten, contentcreatie, links en handleidingen van **Zeespons**. De website is opgebouwd als een statische site in HTML en CSS voor hosting via GitHub Pages op [zeespons.com](https://www.zeespons.com).

## Pagina's en onderdelen

* **Home (`index.html`)**: Landingspagina met logo, korte introductie en directe knoppen naar het grid en de links.
* **Grid (`grid.html`)**: Bento-grid op basis van een 4-koloms CSS Grid met een herhalend patroon van kleine (`S`), middelgrote (`M`) en grote (`L`) blokken, ondersteuning voor klikbare linkkaarten en foto/tekst-combinaties.
* **Links (`links.html`)**: Overzicht van kanalen (zoals Twitch, YouTube, Instagram, Discord, TikTok en Spotify) en gerelateerde projecten (zoals *Boeitmijnul.nl* en *Yappelkaas.nl*).
* **Juridische pagina's (`privacy-policy.html` & `terms-of-service.html`)**: Privacyverklaring en algemene voorwaarden, bereikbaar vanuit de footer op de site.
* **Foutpagina (`404.html`)**: Aangepaste 404-pagina in donkere stijl met gele accenten en een knop terug naar de startpagina.
* **Bestanden en SEO (`files/7tv.txt`, `sitemap.xml`, `robots.txt`, `CNAME`)**: Bevat onder meer de 7TV-editorhandleiding, de XML-sitemap, crawlregels voor zoekmachines en het aangepaste domein `[www.zeespons.com](https://www.zeespons.com)`.

## Projectstructuur

```text
zeespons.github.io/
├── 404.html
├── CNAME
├── grid.html
├── index.html
├── links.html
├── privacy-policy.html
├── robots.txt
├── sitemap.xml
├── style.css
├── terms-of-service.html
├── assets/
│   ├── logo.webp
│   ├── zeeSHRUG.jpg
│   └── logos/
│       ├── boeitmijnul.webp
│       ├── discord.webp
│       ├── instagram.webp
│       ├── linktree.webp
│       ├── snapchat.webp
│       ├── spotify.webp
│       ├── tiktok.webp
│       ├── twitch.webp
│       ├── yappelkaas.webp
│       └── youtube.webp
├── files/
│   └── 7tv.txt
├── links/
└── media/
    ├── favicon.png
    └── og.png
```

## Vormgeving en techniek

* **HTML5 en CSS3**: Geen externe frameworks of build-stappen nodig; alle opmaak staat in `style.css` met CSS-variabelen voor het donkere kleurenpalet en de gele accentkleur (`#f4c430`).
* **Responsieve indeling**: Op bredere schermen werkt het grid met 4 kolommen en automatische `:nth-child`-breedtes; op kleinere schermen schakelt de layout terug naar een enkele kolom.

## Lokale preview en publicatie

1. Kloon of download de repository naar je computer.
2. Open `index.html` (of een andere HTML-pagina) in je browser of start een lokale webserver (bijvoorbeeld met de *Live Server*-extensie in VS Code).
3. Push wijzigingen naar de hoofdbranch om de live site op `zeespons.com` bij te werken.

## Copyright en licentie

© 2026 Zeespons. Alle rechten voorbehouden. Eigen teksten, ontwerpen en het Zeespons-logo zijn eigendom van Zeespons, tenzij anders vermeld.
~~~[cite: 36, 37, 38, 39, 40, 41, 42, 43, 44, 45, 48]
