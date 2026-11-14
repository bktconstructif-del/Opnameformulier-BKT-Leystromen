# Opnameformulieren Constructif – installeren via GitHub en gebruiken op de iPad

Deze map bevat de opnameformulieren voor **Leystromen** en **Poort6** als losse webapp.
Via GitHub Pages krijg je een eigen webadres. Op de iPad zet je het formulier als app op het beginscherm.
Het werkt daarna ook zonder internet.

```
opnameformulier/
├── index.html          startpagina: kies Leystromen of Poort6
├── leystromen/         het opnameformulier Leystromen (index.html, iconen, offline-bestand)
├── poort6/             het opnameformulier Poort6
├── .nojekyll           hoort erbij, niet verwijderen
└── README.md           deze handleiding
```

---

## Stap 1 – GitHub-account maken (eenmalig)

1. Ga op je laptop naar **github.com** en klik op **Sign up**.
2. Kies een gebruikersnaam, bijvoorbeeld `constructif-ronald`. Deze naam komt in het webadres.
3. Bevestig je e-mailadres.

## Stap 2 – Repository aanmaken

1. Klik rechtsboven op **+** → **New repository**.
2. Repository name: `opnameformulier`
3. Kies **Public**.
   - GitHub Pages is gratis voor openbare repositories. Voor een privé-repository met Pages heb je GitHub Pro of Team nodig.
   - Openbaar betekent: de *programmacode* is te zien (met de kleuren- en prijslijsten van de opdrachtgevers). **Je opnames staan níét op GitHub**, die blijven alleen op je iPad.
4. Klik op **Create repository**.

## Stap 3 – Bestanden uploaden

1. Pak het zipbestand uit op je laptop.
2. Klik in de nieuwe repository op **uploading an existing file** (of **Add file → Upload files**).
3. Open de uitgepakte map `opnameformulier` en sleep **de inhoud** naar het uploadvenster:
   `index.html`, `README.md`, de mappen `leystromen` en `poort6`.
   - Zie je `.nojekyll` niet (verborgen bestand)? Maak hem dan zelf: **Add file → Create new file**, naam `.nojekyll`, leeg laten, **Commit changes**.
4. Klik op **Commit changes**.

## Stap 4 – GitHub Pages aanzetten

1. Ga naar **Settings** (tandwiel) → links **Pages**.
2. Bij *Build and deployment* → *Source*: **Deploy from a branch**.
3. Branch: **main**, map: **/ (root)** → **Save**.
4. Wacht 1–2 minuten en ververs de pagina. Bovenaan verschijnt:
   **Your site is live at `https://<gebruikersnaam>.github.io/opnameformulier/`**

Je webadressen worden:

| Formulier  | Adres |
|------------|-------|
| Startpagina | `https://<gebruikersnaam>.github.io/opnameformulier/` |
| Leystromen | `https://<gebruikersnaam>.github.io/opnameformulier/leystromen/` |
| Poort6     | `https://<gebruikersnaam>.github.io/opnameformulier/poort6/` |

## Stap 5 – Op de iPad zetten

1. Open **Safari** op de iPad (niet Chrome: alleen Safari kan op iOS een app op het beginscherm zetten).
2. Ga naar het adres van **Leystromen**.
3. Tik op de **Deel-knop** (vierkantje met pijl omhoog) → **Zet op beginscherm** → **Voeg toe**.
4. Doe hetzelfde voor **Poort6**.

Je hebt nu twee apps met het Constructif-logo: **Opname Leystromen** en **Opname Poort6**.
Ze openen schermvullend en werken ook zonder internet, nadat je ze één keer online hebt geopend.

---

## Werken met de iPad-app

**Opslaan:** alles wordt automatisch op de iPad bewaard: opnames, tekeningen, handtekeningen en foto's.
Leystromen en Poort6 hebben elk hun eigen lijst.

**Foto's:** met "📷 Foto maken" open je direct de camera; met "🖼️ Uit galerij" kies je foto's uit Foto's.

**PDF en bestanden:** bij "Opname afdrukken / opslaan als PDF" kies je in het printvenster de Deel-knop → *Bewaar in Bestanden* (of OneDrive).
Bij "bewaren (.html)", de offerte of het dashboard opent het deelmenu: kies *Bewaar in Bestanden*, *OneDrive* of *Mail*.

**Back-up – belangrijk:**
De opnames staan alleen op deze iPad. Maak daarom regelmatig een back-up, bijvoorbeeld aan het eind van elke werkdag:
1. Tik op het overzicht op **💾 Back-up van alle opnames maken**.
2. Kies **OneDrive** (bijv. de map *Bkt*) of *Bewaar in Bestanden*.

Het back-upbestand (`opnames-backup-leystromen-JJJJ-MM-DD.json`) bevat alle opnames met foto's.

**Back-up terugzetten of opnames overzetten naar een ander apparaat** (andere iPad, laptop):
open daar hetzelfde formulier → **📂 Opname of back-up openen** → kies het back-upbestand.
Losse opnamebestanden (`opname-….html`) kun je op dezelfde manier openen, ook die uit de claude.ai-versie.
Van een opname die al in de lijst staat, wordt alleen de nieuwste versie bewaard.

> **Let op:** wis in Safari niet de *websitegegevens* van github.io (Instellingen → Safari → Geavanceerd → Websitegegevens). Daarmee verwijder je ook de opnames op de iPad. Met een recente back-up zet je ze terug.

---

## Verschil met de claude.ai-versie

| | claude.ai | GitHub / iPad-app |
|---|---|---|
| Opnames op meerdere apparaten tegelijk | ja, via je account | nee – per apparaat, overzetten met back-up |
| Werkt zonder internet | nee | ja |
| Inloggen nodig | ja (Claude-account) | nee |
| Foto's | in je account | op de iPad |

Beide versies kunnen elkaars opnamebestanden openen.

---

## Bijwerken als er een nieuwe versie is

1. Vraag Claude om een nieuw GitHub-pakket; je krijgt dan een nieuwe zip.
2. Upload in de repository de nieuwe bestanden opnieuw (**Add file → Upload files**), zodat de oude worden overschreven → **Commit changes**.
3. Open de app op de iPad één keer met internet: de nieuwe versie wordt automatisch geladen. Eventueel de app sluiten en opnieuw openen.

Je opnames op de iPad blijven bij een update gewoon staan.
