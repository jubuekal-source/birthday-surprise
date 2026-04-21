# Gipfelsturm - Interaktiver Geburtstagsgutschein

Ein interaktiver Gutschein fuer Johannes: 2-Tages-Bergtour auf die Zugspitze ueber den Stopselzieher-Klettersteig.

## Setup (GitHub Pages)

### 1. Repository erstellen
- Neues Repository auf GitHub erstellen
- Name: z.B. `birthday-surprise` oder `party-app` (nichts mit Zugspitze, falls Jo dein GitHub kennt)
- Sichtbarkeit: **Public** (noetig fuer GitHub Pages Free)

### 2. Dateien hochladen

Du brauchst diese Struktur:

```
birthday-surprise/
  index.html
  img/
    zugspitze.jpg
  README.md (optional)
```

**So erstellst du den img-Ordner auf GitHub:**

GitHub hat keinen "Ordner erstellen"-Button. Stattdessen:

1. Gehe in dein Repo und klicke auf **"Add file"** > **"Upload files"**
2. Lade zuerst die `index.html` und `README.md` hoch
3. Fuer das Bild im Unterordner: Klicke nochmal auf **"Add file"** > **"Create new file"**
4. Im Dateinamen-Feld tippst du: `img/zugspitze.jpg` - sobald du den `/` tippst, erstellt GitHub automatisch den Ordner!
5. Brich das ab, gehe stattdessen auf **"Add file"** > **"Upload files"**
6. **Aber einfacher:** Ziehe einfach alle Dateien per Drag & Drop rein. Erstelle dazu lokal auf deinem Computer einen Ordner `img` mit dem Bild drin, und ziehe den ganzen `img`-Ordner in das GitHub Upload-Fenster - GitHub erkennt die Ordnerstruktur automatisch!

**Wichtig:** Benenne dein Pixabay-Bild in `zugspitze.jpg` um bevor du es hochlaedst.

### 3. GitHub Pages aktivieren
1. Im Repo: **Settings** > **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main**, Ordner: **/ (root)**
4. **Save** klicken
5. Nach 1-2 Minuten live unter: `https://DEIN-USERNAME.github.io/birthday-surprise/`

### 4. Testen und Link teilen
- Oeffne den Link selbst zum Testen
- Schicke Johannes den Link auf der Party

## Wie es funktioniert

- **Party-Modus:** 5 Challenges vor Publikum, Jury bestaetigt per PIN
- **Solo-Modus:** 5 Hobby-Horsing-Quizfragen (Ablenkung vom wahren Geschenk!)
- **PIN fuer die Jury:** `4321`
- Falscher PIN: Dramatischer Alarm + Fake-Selbstzerstoerung
- Falsche Quiz-Antworten: Eskalierende Sprueche

## Anpassen

Alles steckt in der `index.html`. Du kannst Texte, Challenges, Fragen, PIN und Farben direkt aendern.
