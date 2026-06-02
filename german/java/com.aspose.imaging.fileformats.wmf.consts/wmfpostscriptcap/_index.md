---
title: "WmfPostScriptCap"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die PostScriptCap‑Aufzählung definiert Linienende‑Typen für die Verwendung mit einem PostScript‑Druckertreiber."
type: docs
weight: 31
url: /de/java/com.aspose.imaging.fileformats.wmf.consts/wmfpostscriptcap/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfPostScriptCap extends System.Enum
```

Die PostScriptCap‑Aufzählung definiert Linienende‑Typen für die Verwendung mit einem PostScript‑Druckertreiber.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [PostScriptNotSet](#PostScriptNotSet) | Gibt an, dass der Zeilenende‑Stil nicht festgelegt wurde und dass ein Standardstil MAY [24] verwendet werden kann. |
| [PostScriptFlatCap](#PostScriptFlatCap) | Gibt an, dass die Linie am letzten Punkt endet. |
| [PostScriptRoundCap](#PostScriptRoundCap) | Gibt einen kreisförmigen Abschluss an. |
| [PostScriptSquareCap](#PostScriptSquareCap) | Gibt einen quadratischen Abschluss an. |
### PostScriptNotSet {#PostScriptNotSet}
```
public static final int PostScriptNotSet
```


Gibt an, dass der Zeilenende‑Stil nicht festgelegt wurde und dass ein Standardstil MAY [24] verwendet werden kann.

### PostScriptFlatCap {#PostScriptFlatCap}
```
public static final int PostScriptFlatCap
```


Gibt an, dass die Linie am letzten Punkt endet. Das Ende ist quadratisch abgeflacht.

### PostScriptRoundCap {#PostScriptRoundCap}
```
public static final int PostScriptRoundCap
```


Gibt eine runde Endung an. Der Mittelpunkt des Kreises ist der letzte Punkt der Linie. Der Durchmesser des Kreises entspricht der Linienbreite; das heißt, der Dicke der Linie.

### PostScriptSquareCap {#PostScriptSquareCap}
```
public static final int PostScriptSquareCap
```


Gibt eine quadratische Endung an. Der Mittelpunkt des Quadrats ist der letzte Punkt der Linie. Höhe und Breite des Quadrats entsprechen der Linienbreite; das heißt, der Dicke der Linie.

