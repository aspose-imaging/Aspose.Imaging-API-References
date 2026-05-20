---
title: "WmfPostScriptClipping"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die PostScriptClipping‑Aufzählung definiert Funktionen, die auf den Beschneidungspfad angewendet werden können, der für PostScript‑Ausgabe verwendet wird."
type: docs
weight: 32
url: /de/java/com.aspose.imaging.fileformats.wmf.consts/wmfpostscriptclipping/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfPostScriptClipping extends System.Enum
```

Die PostScriptClipping‑Aufzählung definiert Funktionen, die auf den Beschneidungspfad angewendet werden können, der für PostScript‑Ausgabe verwendet wird.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [CLIP_SAVE](#CLIP-SAVE) | Speichert den aktuellen PostScript-Clipping-Pfad. |
| [CLIP_RESTORE](#CLIP-RESTORE) | Stellt den PostScript-Clipping-Pfad wieder her, indem er den letzten Clipping-Pfad verwendet, der von einer vorherigen CLIP\_SAVE‑Funktion gespeichert wurde, die durch einen CLIP\_TO\_PATH‑Datensatz (Abschnitt 2.3.6.6) angewendet wurde. |
| [CLIP_INCLUSIVE](#CLIP-INCLUSIVE) | Schneidet den aktuellen PostScript-Clipping-Pfad mit dem aktuellen Clipping-Pfad und speichert das Ergebnis als neuen PostScript-Clipping-Pfad. |
### CLIP_SAVE {#CLIP-SAVE}
```
public static final int CLIP_SAVE
```


Speichert den aktuellen PostScript-Clipping-Pfad.

### CLIP_RESTORE {#CLIP-RESTORE}
```
public static final int CLIP_RESTORE
```


Stellt den PostScript-Clipping-Pfad wieder her, indem er den letzten Clipping-Pfad verwendet, der von einer vorherigen CLIP\_SAVE‑Funktion gespeichert wurde, die durch einen CLIP\_TO\_PATH‑Datensatz (Abschnitt 2.3.6.6) angewendet wurde.

### CLIP_INCLUSIVE {#CLIP-INCLUSIVE}
```
public static final int CLIP_INCLUSIVE
```


Schneidet den aktuellen PostScript-Clipping-Pfad mit dem aktuellen Clipping-Pfad und speichert das Ergebnis als neuen PostScript-Clipping-Pfad.

