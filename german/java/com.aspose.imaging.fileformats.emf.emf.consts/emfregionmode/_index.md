---
title: "EmfRegionMode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Aufzählung RegionMode definiert Werte, die mit EMR_SELECTCLIPPATH und EMR_EXTSELECTCLIPRGN verwendet werden und den aktuellen Pfad oder einen neuen Bereich angeben, der mit dem aktuellen Clip‑Bereich kombiniert wird."
type: docs
weight: 39
url: /de/java/com.aspose.imaging.fileformats.emf.emf.consts/emfregionmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRegionMode extends System.Enum
```

Die RegionMode‑Aufzählung definiert Werte, die mit EMR\_SELECTCLIPPATH und EMR\_EXTSELECTCLIPRGN verwendet werden und den aktuellen Pfad oder einen neuen Bereich angeben, der mit dem aktuellen Clip‑Bereich kombiniert wird.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [RGN_AND](#RGN-AND) | Der neue Clipping‑Bereich umfasst die Schnittmenge (überlappende Bereiche) des aktuellen Clipping‑Bereichs und des aktuellen Pfads (oder neuen Bereichs). |
| [RGN_OR](#RGN-OR) | Die neue Beschneidungsregion umfasst die Vereinigung (kombinierte Bereiche) der aktuellen Beschneidungsregion und des aktuellen Pfads (oder einer neuen Region). |
| [RGN_XOR](#RGN-XOR) | Die neue Beschneidungsregion umfasst die Vereinigung der aktuellen Beschneidungsregion und des aktuellen Pfads (oder einer neuen Region), jedoch ohne die überlappenden Bereiche. |
| [RGN_DIFF](#RGN-DIFF) | Die neue Beschneidungsregion umfasst die Bereiche der aktuellen Beschneidungsregion, wobei die des aktuellen Pfads (oder einer neuen Region) ausgeschlossen werden. |
| [RGN_COPY](#RGN-COPY) | Die neue Beschneidungsregion ist der aktuelle Pfad (oder die neue Region). |
### RGN_AND {#RGN-AND}
```
public static final int RGN_AND
```


Der neue Clipping‑Bereich umfasst die Schnittmenge (überlappende Bereiche) des aktuellen Clipping‑Bereichs und des aktuellen Pfads (oder neuen Bereichs).

### RGN_OR {#RGN-OR}
```
public static final int RGN_OR
```


Die neue Beschneidungsregion umfasst die Vereinigung (kombinierte Bereiche) der aktuellen Beschneidungsregion und des aktuellen Pfads (oder einer neuen Region).

### RGN_XOR {#RGN-XOR}
```
public static final int RGN_XOR
```


Die neue Beschneidungsregion umfasst die Vereinigung der aktuellen Beschneidungsregion und des aktuellen Pfads (oder einer neuen Region), jedoch ohne die überlappenden Bereiche.

### RGN_DIFF {#RGN-DIFF}
```
public static final int RGN_DIFF
```


Die neue Beschneidungsregion umfasst die Bereiche der aktuellen Beschneidungsregion, wobei die des aktuellen Pfads (oder einer neuen Region) ausgeschlossen werden.

### RGN_COPY {#RGN-COPY}
```
public static final int RGN_COPY
```


Die neue Beschneidungsregion ist der aktuelle Pfad (oder die neue Region).

