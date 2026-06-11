# Meine Gefühlswelt 🌟

Interaktive Audio-Begleitwebsite zur **Gefühlswerkzeugkiste** (Phase 1) – entwickelt als digitales Scaffold für den Einsatz im Zyklus 2.

---

## Über das Projekt

Diese Website ergänzt die physische Gefühlswerkzeugkiste und erklärt Kindern die sieben Basisemotionen nach Paul Ekman sowie ihre Nuancen in gesprochener Form. Pro Emotion gibt es eine farblich passende Karte mit der zugehörigen Figur, einer Nuancenliste und einer Audioerklärung.

Die sieben Emotionen:

| Emotion | Farbe |
|---|---|
| Wut | Korallrot |
| Trauer | Hellblau |
| Angst | Lila |
| Freude | Hellgelb |
| Ekel | Mintgrün |
| Verachtung | Pfirsich |
| Überraschung | Pink |

---

## Funktionen

- Audioplayer pro Karte mit **Play/Pause**, **Fortschrittsbalken** (klick- und ziehbar) und **Zeitanzeige**
- Nur ein Audio spielt gleichzeitig – wechselt man die Karte, pausiert das vorherige automatisch
- Responsives Grid-Layout (funktioniert auf Desktop, Tablet und Handy)
- Alle Bilder und Audiodateien sind direkt in der HTML-Datei eingebettet – **keine externe Abhängigkeit**

---

## Dateistruktur

```
/
├── index.html               # Komplette Website (Bilder als Base64 eingebettet)
├── audio/
│   ├── wut.m4a
│   ├── trauer.m4a
│   ├── angst.m4a
│   ├── freude.m4a
│   ├── ekel.m4a
│   ├── verachtung.m4a
│   └── ueberraschung.m4a
└── README.md
```

> Die Audiodateien liegen separat im Ordner `audio/` und werden relativ zur HTML-Datei geladen.

---

## Hosting via GitHub Pages

1. Repository auf GitHub erstellen (oder dieses forken)
2. Unter **Settings → Pages** den Branch `main` und den Ordner `/ (root)` auswählen
3. GitHub generiert eine URL – diese als QR-Code ausdrucken und in die Gefühlswerkzeugkiste legen

---

## Pädagogischer Hintergrund

Die Gefühlswerkzeugkiste ist ein Lernmaterial für den Zyklus 2, das Kinder in drei Phasen begleitet:

- **Phase 1** – Emotionen wahrnehmen und benennen (Selbstwahrnehmung)
- **Phase 2** – Situationen analysieren anhand der Gewaltfreien Kommunikation nach Marshall Rosenberg
- **Phase 3** – Konflikte gemeinsam lösen

Theoretische Grundlagen: Ekman (Basisemotionen), Damasio, Goleman, Juslin & Laukka, CASEL-Framework.

---

## Entwickelt im Rahmen

Leistungsnachweis (LNW) im Modul **KuS 2**  
Pädagogische Hochschule Graubünden (PHGR)