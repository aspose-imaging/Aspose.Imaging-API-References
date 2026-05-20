---
title: "EmfMapMode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Aufzählung MapMode wird verwendet, um die Maßeinheit für die Umwandlung von Seiteneinheiten in Geräteeinheiten zu definieren und um die Ausrichtung der Zeichenachsen festzulegen."
type: docs
weight: 30
url: /de/java/com.aspose.imaging.fileformats.emf.emf.consts/emfmapmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfMapMode extends System.Enum
```

Die Aufzählung MapMode wird verwendet, um die Maßeinheit für die Umwandlung von Seiteneinheiten in Geräteeinheiten zu definieren und um die Ausrichtung der Zeichenachsen festzulegen.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [MM_TEXT](#MM-TEXT) | Jede logische Einheit wird auf ein Gerätepixel abgebildet. |
| [MM_LOMETRIC](#MM-LOMETRIC) | Jede logische Einheit wird auf 0,1 Millimeter abgebildet. |
| [MM_HIMETRIC](#MM-HIMETRIC) | Jede logische Einheit wird auf 0,01 Millimeter abgebildet. |
| [MM_LOENGLISH](#MM-LOENGLISH) | Jede logische Einheit wird auf 0,01 Zoll abgebildet. |
| [MM_HIENGLISH](#MM-HIENGLISH) | Jede logische Einheit wird auf 0,001 Zoll abgebildet. |
| [MM_TWIPS](#MM-TWIPS) | Jede logische Einheit wird auf ein Zwanzigstel eines Druckerpunktes abgebildet (1/1440 Zoll, auch "twip" genannt). |
| [MM_ISOTROPIC](#MM-ISOTROPIC) | Logische Einheiten werden auf beliebige Einheiten mit gleich skalierten Achsen abgebildet; das heißt, eine Einheit entlang der x-Achse ist gleich einer Einheit entlang der y-Achse. |
| [MM_ANISOTROPIC](#MM-ANISOTROPIC) | Logische Einheiten werden auf beliebige Einheiten mit beliebig skalierten Achsen abgebildet. |
### MM_TEXT {#MM-TEXT}
```
public static final int MM_TEXT
```


Jede logische Einheit wird auf ein Gerätepixel abgebildet. Positives x ist nach rechts; positives y ist nach unten.

### MM_LOMETRIC {#MM-LOMETRIC}
```
public static final int MM_LOMETRIC
```


Jede logische Einheit wird auf 0,1 Millimeter abgebildet. Positives x ist nach rechts; positives y ist nach oben.

### MM_HIMETRIC {#MM-HIMETRIC}
```
public static final int MM_HIMETRIC
```


Jede logische Einheit wird auf 0,01 Millimeter abgebildet. Positives x ist nach rechts; positives y ist nach oben.

### MM_LOENGLISH {#MM-LOENGLISH}
```
public static final int MM_LOENGLISH
```


Jede logische Einheit wird auf 0,01 Zoll abgebildet. Positives x ist nach rechts; positives y ist nach oben

### MM_HIENGLISH {#MM-HIENGLISH}
```
public static final int MM_HIENGLISH
```


Jede logische Einheit wird auf 0,001 Zoll abgebildet. Positives x ist nach rechts; positives y ist nach oben.

### MM_TWIPS {#MM-TWIPS}
```
public static final int MM_TWIPS
```


Jede logische Einheit wird auf ein Zwanzigstel eines Druckerpunktes abgebildet (1/1440 Zoll, auch "twip" genannt). Positives x ist nach rechts; positives y ist nach oben.

### MM_ISOTROPIC {#MM-ISOTROPIC}
```
public static final int MM_ISOTROPIC
```


Logische Einheiten werden auf beliebige Einheiten mit gleich skalierten Achsen abgebildet; das heißt, eine Einheit entlang der x-Achse ist gleich einer Einheit entlang der y-Achse. Die EMR\_SETWINDOWEXTEX und EMR\_SETVIEWPORTEXTEX Datensätze SHOULD verwendet werden, um die Einheiten und die Orientierung der Achsen anzugeben. Anpassungen MUST vorgenommen werden, falls nötig, um sicherzustellen, dass die x- und y-Einheiten dieselbe Größe behalten. Zum Beispiel, wenn die Fenstergröße festgelegt wird, das Ansichtsfenster MUST angepasst werden, um die Einheiten isotrop zu halten.

### MM_ANISOTROPIC {#MM-ANISOTROPIC}
```
public static final int MM_ANISOTROPIC
```


Logische Einheiten werden auf beliebige Einheiten mit beliebig skalierten Achsen abgebildet. Die EMR\_SETWINDOWEXTEX und EMR\_SETVIEWPORTEXTEX Datensätze SHOULD verwendet werden, um die Einheiten, die Orientierung und die Skalierung anzugeben.

