---
version: 0.13.0-fluesterfee.1
name: fluesterfee-brand
description: |
  Markenvorgaben der AI Flüsterfee (Heike Bruckhuisen) für alle Higgsfield Skills:
  Bildsprache, Farben, Schriften, Formate, Texte im Bild, Sprache für Vertonung.
  Use when: irgendein higgsfield Skill für Heike oder die AI Flüsterfee arbeitet,
  "im Flüsterfee Stil", "für meinen LinkedIn Post", "für den KI Talk",
  "für KI 4 Excellence", "Newsletter Bild", "Erklärvideo für meine Leute".
  Immer VOR der ersten Generierung lesen. Die Vorgaben hier gehen den
  Standardvorgaben der higgsfield Skills vor.
argument-hint: "[Anlass oder Kanal]"
allowed-tools: Bash
---

# AI Flüsterfee, Markenvorgaben für Higgsfield

Diese Datei gilt für jeden Auftrag von Heike Bruckhuisen. Sie ergänzt die
higgsfield Skills und hat Vorrang vor deren Standardstil.

Hinweis zur Ablage: Dieses Repository ist öffentlich. Hier stehen nur
Vorgaben, die öffentlich sein dürfen. Interne Zahlen, Preise und Privates
gehören nie in diese Dateien, auch nicht in Prompts, die hier gespeichert werden.

## Wer die Marke ist

AI Flüsterfee. Heike Bruckhuisen, Trainerin, Beraterin und Coach seit 2006.
Sie begleitet Trainerinnen, Berater und Coaches im DACH Raum, meist 45 bis 60,
solo selbständig, durch den Umbau ihres Geschäfts mit KI.

Kernsatz: Du entscheidest, welcher Teil deiner Arbeit ab jetzt wem gehört.
Zweiter Satz: Du bist am Ende erkennbar dieselbe, mit KI in der Arbeit.
Logozusatz: Einfach magisch.

Prüffrage für jedes Bild und jedes Video: Hat die Betrachterin Lust, das morgen
früh zu probieren, ohne dafür jemand anderes werden zu müssen?

## Ausstrahlung

Geerdet. Zugewandt. Souverän. Fröhlich. Großzügig. Dazu ein Funken Magie.
Die Fee ist ernst gemeint und steht auf zwanzig Jahren Fundament.

Gewünschte Wirkung: Erleichterung, Erkanntwerden, Sicherheit, Zutrauen, Lust, Ruhe.

## Bildsprache

**Motive aus dem echten Arbeitsalltag.** Seminarraum mit Flipchart, Schreibtisch
mit Laptop und Kaffeetasse, Notizbuch, Moderationskarten, ein Zoom Call am
Küchentisch, der frühe ICE mit Laptop auf dem Klapptisch, Ordner und Festplatten
voller Material. Der Mensch steht im Bild, die Technik ist Werkzeug am Rand.

**Menschen.** Erfahrene Frauen und Männer zwischen 45 und 60, gut angezogen,
entspannt, kompetent. Echte Gesichter mit Lachfalten. Gruppen mittlerer Größe,
um die 15 Personen. Heike selbst ist eine Frau über 50.

**Licht und Stimmung.** Warmes Tageslicht, ruhige Komposition, viel Luft im Bild.
Natürliche Materialien wie Holz, Papier, Leinen. Leichtigkeit und ein Lächeln.

**Die Magie.** Sparsam und fein. Ein kleiner Lichtfunke, ein feiner Glanz über
einer Notiz, ein Hauch Leuchten in Magenta oder Türkis. Höchstens ein magisches
Element pro Bild. Keine Feenfigur mit Flügeln, kein Glitzerregen, kein Kitsch.

**Diese Motive kommen nie vor:**
→ Roboter, Roboterhände, Cyborgs, leuchtende Gehirne, Neonnetze, Platinen,
  blaue Matrixwelten, Binärcode, Hologramme
→ Raketen, Zielscheiben, Treppen nach oben, Pokale, Siegerposen, Geldregen
→ Countdowns, Uhren mit Zeitdruck, Ausrufezeichen, Alarmfarben
→ Hektik, gestresste Menschen als Schreckbild, Bilder der Angst
→ Logos von Softwareanbietern und Toolscreenshots als Hauptmotiv
→ Stufen, Leitern, Reifegradmodelle
→ Kinder, Familienszenen, Krankenhaus, Krankheit
→ Generische Stockfoto Teams mit Daumen hoch

## Farben

| Token | Hex | Einsatz |
|---|---|---|
| Magenta 500 | #c02b5c | Signaturfarbe, genau ein Akzent pro Motiv |
| Türkis 500 | #60aaa9 | Zweiter Akzent, sparsam |
| Ink Navy 500 | #1e2f5c | Überschriften, große Zahlen, Wortmarke |
| Schiefer | #4a575e | Nebentext |
| Kohle | #1f2a2e | Fließtext |
| Nebel | #eae8e6 | Linien, ruhige Flächen |
| Off White | #f7f6f4 | Hintergrund |

Abstufungen: Magenta hell #e095ae und #ecbfce. Türkis hell #b0d4d4 und #cfe6e5.
Navy hell #8e97ae und #bcc1ce.

Grundzustand ist hell und ruhig. Farbe nur mit Funktion. Kein Farbverlauf,
keine Neonfarben, kein Schwarz mit Leuchteffekten.

Im Prompt so formulieren: "warm natural light, calm editorial composition,
off white and soft warm grey tones, one subtle accent in deep magenta (#c02b5c),
optional touch of muted teal (#60aaa9), lots of negative space".

## Schriften

Tenor Sans für Überschriften. Jost für Text. Wenn ein Modell Schrift direkt ins
Bild setzt: "elegant thin serif free headline in the style of Tenor Sans,
clean geometric sans body text in the style of Jost". Für exakte Schrift
lieber Bild ohne Text erzeugen und den Text danach setzen.

## Texte im Bild

→ Deutsch, immer duzen
→ Kurz. Höchstens sieben Wörter als Überschrift
→ Keine Bindestriche, außer bei E-Mail und ähnlich etablierten Begriffen
→ Keine Superlative, keine Hashtags, keine Ausrufezeichen
→ Keine Dringlichkeit: kein "Jetzt", "Nur noch", "Letzte Chance", "Restplätze"
→ Keine Preise auf Reichweitenbildern
→ Kein Negations Reframing, auch nicht als Überschrift. Verboten sind
  Muster wie "Kein X. Ein Y.", "Nicht X, sondern Y", "X statt Y"
→ Gesperrte Wörter: revolutionieren, transformieren, ganzheitlich, Game Changer,
  nahtlos, Potenzial entfalten, neues Level, wegweisend, Mindset, Purpose,
  Empowerment, Mastery, Reifegrad, Stufe, Niveau, Umgang mit KI
→ Wörter, die sitzen: KI Souveränität, Aufteilungsplan, Prozess first Tools second,
  Vom Könner zum Dirigenten, Live Projekt, Begleitung, Einfach magisch

Erlaubte Signaturen: das Feen Emoji 🧚 in Begleittexten, die Grußformel
"Magische Grüße".

## Kanäle und Formate

| Kanal | Format | Hinweis |
|---|---|---|
| LinkedIn Bildpost | 4:5 (1080 x 1350) | Hauptkanal, Schaufenster |
| LinkedIn Karussell | 4:5, 5 bis 8 Seiten | Eine Aussage pro Seite |
| LinkedIn Link oder Banner | 1.91:1 | ruhig, viel Weißraum |
| LinkedIn Video | 4:5 oder 1:1 | Untertitel auf Deutsch |
| Newsletter Kopfbild | 2:1 | wöchentlich, gekoppelt an den KI Talk |
| KI Talk Ankündigung | 4:5 und 16:9 | Titel als Frage aus dem Alltag, ohne Toolnamen |
| Website ki4excellence.aifluesterfee.de | 16:9 Hero | warm, menschlich |
| Workshop und Präsentation | 16:9 | passend zum editorial Folienstil |

Kein YouTube und kein Podcast. Diese Kanäle werden nicht vorgeschlagen.

## Video und Vertonung

→ Sprache Deutsch, Du Ansprache
→ Ruhiges Tempo, warme Stimme, ohne Werbeton und ohne Begeisterungsrufe
→ Kurze Sätze, dann ein längerer Erklärsatz, dann wieder kurz
→ Alltagsbilder für komplexe Dinge
→ Struktur gern als Dreischritt
→ Kein Countdown, keine Verknappung, kein Weckruf, keine Zukunftsdrohung
→ Untertitel in Jost, Kohle auf Off White oder Weiß auf Navy

## Heikes Gesicht

Für Bilder und Videos mit Heike wird eine Soul Character Identität genutzt
(Skill higgsfield-soul-id). Die reference_id trägt Heike nach dem Training hier
ein:

`SOUL_ID_HEIKE = ba8ae231-2968-4375-a27d-8df8d54935a8` (Name: Heike Flüsterfee, Typ soul_2)

Nutzbar mit den Modellen `soul_2` und `soul_cinematic`.

Darstellung: souverän, zugewandt, lächelnd, im Arbeitskontext. Nie als
Technikerin vor Bildschirmwänden. Alter ist Teil der Marke und wird nie als
Handicap inszeniert.

## Vorgehen bei jedem Auftrag

1. Anlass und Kanal klären, Format aus der Tabelle nehmen.
2. Motiv aus dem Arbeitsalltag wählen, ein magischer Akzent höchstens.
3. Farb und Lichtangaben aus diesem Dokument in den Prompt übernehmen.
4. Text im Bild gegen die Regeln oben prüfen.
5. Zwei bis drei Varianten erzeugen und eine davon mit Begründung empfehlen.
6. Heike entscheidet. Korrekturen sofort umsetzen, ohne Entschuldigung.
