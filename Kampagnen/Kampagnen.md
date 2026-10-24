---
titel: Kampagnen
typ: index
tags:
  - elyria/register
---

# Kampagnen

Mehrere Kampagnen in derselben Welt, aber **voneinander unabhängig**: eigene Gruppe, eigene Helden, eigene Handlung, eigener Zeitanker. Gemeinsam ist nur Elyria selbst.

## Aufbau einer Kampagne

```
Kampagnen/
└── Kampagne 01/
    ├── Kampagne 01.md    ← Rahmen: Pitch, Truths, Gruppe, Konflikte
    └── Chronik 01.md     ← Sitzungsprotokolle, neueste oben
```

Für längere Kampagnen darf daneben alles liegen, was nur diese Kampagne betrifft: eigene NSC, Gegnerwerte, Handouts, Kartenausschnitte.

## Übersicht

![[Kampagnen.base#Übersicht]]

## Status

| Status | Bedeutung |
| --- | --- |
| `idee` | Nur ein Geistesblitz, noch nichts festgelegt |
| `vorbereitung` | Session Null geplant oder gelaufen, Weltbezug geklärt |
| `laufend` | Wird regelmäßig gespielt |
| `pausiert` | Ruht, wird vielleicht wieder aufgenommen |
| `abgeschlossen` | Ende erreicht, Chronik ist vollständig |

## Neue Kampagne anlegen

1. Ordner `Kampagnen/Kampagne NN/` erstellen.
2. [[Vorlage Kampagne]] als `Kampagne NN.md` speichern, Platzhalter füllen.
3. [[Vorlage Session]]-Kopf in `Chronik NN.md` übernehmen (oder [[Chronik 01]] als Muster kopieren).
4. Zeitanker in [[Kanon und Kontinuität]] eintragen – sonst kollidieren die Kampagnen früher oder später.
5. In der Basis oben erscheint die Kampagne automatisch (Tag `kampagne`).

## Regeln für Parallelbetrieb

- **Nichts aus einer anderen Kampagne ist verbindlich**, solange es nicht im Weltkanon steht.
- **Keine Kampagne entscheidet über eine andere.** Wenn A eine Stadt rettet, darf B sie trotzdem bedroht sehen – es sei denn, du erklärst es zum Weltkanon.
- **Zeitanker respektieren:** Kampagnen, die früher spielen, kennen spätere Ereignisse nicht.
- **Gerüchte statt Fakten** als Brücke zwischen Gruppen.

## Was in die Weltnotizen gehört – und was nicht

| Gehört in die Welt | Gehört in die Kampagne |
| --- | --- |
| Regionen, Orte, Fraktionen, wiederkehrende NSC | Auftraggeber, Zufallsfiguren, lokale Gegner |
| Kosmologie, Magie, Geschichte bis „Jetzt“ | Was die Gruppe erlebt und verändert hat |
| Karten und Entfernungen | Reiserouten dieser Gruppe |

## Verwandt

[[Kanon und Kontinuität]] · [[Daggerheart am Tisch]] · [[Weltüberblick]]
