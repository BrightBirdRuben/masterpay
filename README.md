# MASTER PAY — Hoe werkt het?

Voorbeeldpagina met vier illustraties, uitklapbare voorbeelden en lokale demonstraties van deelbetaling, herinnering en dossierafsluiting.

## Publiceren via GitHub en Vercel

1. Pak het ZIP-bestand uit.
2. Maak een nieuwe GitHub-repository aan.
3. Upload de uitgepakte bestanden en mappen. Zorg dat `index.html` en `vercel.json` direct in de hoofdmap van de repository staan, niet in een extra bovenliggende map. Upload dus niet alleen het ZIP-bestand.
4. Importeer de repository in Vercel als nieuw project.
5. Gebruik Framework Preset `Other`, Root Directory de hoofdmap, geen Build Command en Output Directory `.`. De meegeleverde `vercel.json` stelt het framework, de buildopdracht en uitvoermap al in.
6. Klik op Deploy. Latere wijzigingen in de gekoppelde GitHub-branch kunnen opnieuw worden gepubliceerd door Vercel.

Er is geen installatie, database, API-sleutel of abonnement voor de werking van deze statische pagina nodig. Eventuele hostingvoorwaarden en -kosten zijn die van je eigen Vercel-account.

## Bestanden

- `index.html`: zelfstandige browserexport met opmaak, interacties, logo en vier ingebedde afbeeldingen. Kan ook lokaal geopend worden.
- `vercel.json`: instellingen voor de statische publicatie.
- `illustraties/`: de vier oorspronkelijke PNG-bestanden, apart meegeleverd voor later gebruik. De pagina gebruikt de reeds ingebedde, compacte versies.

## Wat deze versie doet

De vier stappen, illustraties, veelgestelde vragen en interactieve voorbeelden zijn zichtbaar. Er worden geen facturen geüpload, geen betalingen verwerkt en geen herinneringen verstuurd. De uploadknop toont dat het om een ontwerpvoorbeeld gaat. De pagina bevat geen echte klantgegevens.

De export bevat een ingesloten pagina voor de oorspronkelijke interactieve weergave. De illustraties en het logo zijn ingebed. Kleine pictogrammen kunnen afhankelijk zijn van de meegeleverde browserruntime en internettoegang; de tekst en hoofdillustraties zijn daarvan onafhankelijk.

Vercel-documentatie: https://vercel.com/docs/builds/configure-a-build
