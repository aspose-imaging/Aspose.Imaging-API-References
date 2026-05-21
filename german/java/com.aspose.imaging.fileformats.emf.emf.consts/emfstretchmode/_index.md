---
title: "EmfStretchMode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die StretchMode‑Aufzählung wird verwendet, um anzugeben, wie Farbdaten zu gestreckten oder komprimierten Bitmaps hinzugefügt oder daraus entfernt werden."
type: docs
weight: 43
url: /de/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStretchMode extends System.Enum
```

Die StretchMode‑Aufzählung wird verwendet, um anzugeben, wie Farbdaten zu gestreckten oder komprimierten Bitmaps hinzugefügt oder daraus entfernt werden.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [STRETCH_ANDSCANS](#STRETCH-ANDSCANS) | Führt eine boolesche UND-Operation unter Verwendung der Farbwerte für die eliminierten und vorhandenen Pixel aus. |
| [STRETCH_ORSCANS](#STRETCH-ORSCANS) | Führt eine boolesche ODER-Operation unter Verwendung der Farbwerte für die eliminierten und vorhandenen Pixel aus. |
| [STRETCH_DELETESCANS](#STRETCH-DELETESCANS) | Löscht die Pixel. |
| [STRETCH_HALFTONE](#STRETCH-HALFTONE) | Mappt Pixel vom Quellrechteck in Blöcke von Pixeln im Zielrechteck. |
### STRETCH_ANDSCANS {#STRETCH-ANDSCANS}
```
public static final int STRETCH_ANDSCANS
```


Führt eine Boolean-UND-Operation unter Verwendung der Farbwerte für die eliminierten und vorhandenen Pixel aus. Wenn das Bitmap ein monochromes Bitmap ist, bewahrt dieser Modus schwarze Pixel auf Kosten weißer Pixel.

### STRETCH_ORSCANS {#STRETCH-ORSCANS}
```
public static final int STRETCH_ORSCANS
```


Führt eine Boolean-OR-Operation unter Verwendung der Farbwerte für die eliminierten und vorhandenen Pixel aus. Wenn das Bitmap ein monochromes Bitmap ist, bewahrt dieser Modus weiße Pixel auf Kosten schwarzer Pixel.

### STRETCH_DELETESCANS {#STRETCH-DELETESCANS}
```
public static final int STRETCH_DELETESCANS
```


Löscht die Pixel. Dieser Modus löscht alle eliminierten Pixelzeilen, ohne zu versuchen, deren Informationen zu erhalten.

### STRETCH_HALFTONE {#STRETCH-HALFTONE}
```
public static final int STRETCH_HALFTONE
```


Mappt Pixel vom Quellrechteck in Blöcke von Pixeln im Zielrechteck. Die durchschnittliche Farbe über den Zielblock von Pixeln approximiert die Farbe der Quellpixel.

