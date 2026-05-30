# Mark Shaman Website

Offizielle Website von Mark Shaman – Energetische Standortbestimmung.
Live: [markshaman.ch](https://www.markshaman.ch)

---

## Ordnerstruktur

```
markshaman/
├── index.html          ← Die Website
├── netlify.toml        ← Netlify-Konfiguration
├── admin/
│   ├── index.html      ← Decap CMS Interface
│   └── config.yml      ← CMS Felder-Definition
└── _data/
    ├── hero.json        ← Startbereich Texte
    ├── geschichte.json  ← Geschichte Texte
    ├── angebot.json     ← Angebot Texte
    ├── enkasy.json      ← EnKaaSy Methode Texte
    ├── testimonials.json← Stimmen Texte
    └── kontakt.json     ← Kontakt Texte
```

---

## Inhalte ändern (CMS)

1. Gehe auf **markshaman.ch/admin**
2. Login mit deinem Netlify-Account
3. Inhalte bearbeiten → „Publish" klicken
4. Website ist innert ~30 Sekunden aktuell

---

## Design/Struktur ändern (via Claude.ai)

1. Änderung in Claude.ai besprechen
2. Neue `index.html` erhalten
3. Datei in GitHub hochladen (ersetzt die alte)
4. Netlify deployed automatisch

---

## Einmaliges Setup (nur beim ersten Mal)

### GitHub
1. Repository erstellen: github.com → „New repository" → Name: `markshaman`
2. Alle Dateien hochladen (diesen ZIP-Inhalt)

### Netlify
1. netlify.com → „Add new site" → „Import from Git" → GitHub → `markshaman`
2. Deploy starten

### Netlify Identity aktivieren
1. In Netlify: Site settings → Identity → „Enable Identity"
2. Unter „Registration": auf „Invite only" stellen
3. Unter „Services → Git Gateway": „Enable Git Gateway" klicken
4. Dann: Identity → „Invite users" → deine E-Mail eingeben
5. Du erhältst eine Einladungs-E-Mail → Account bestätigen

### Domain verbinden
1. Netlify → Site settings → Domain management → „Add custom domain"
2. `markshaman.ch` eingeben
3. DNS beim Registrar auf Netlify-Nameserver umstellen
