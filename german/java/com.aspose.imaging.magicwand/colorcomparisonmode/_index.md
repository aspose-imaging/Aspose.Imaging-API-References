---
title: "ColorComparisonMode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Gibt an, wie Farben während des Magic‑Wand‑Algorithmus verglichen werden."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.magicwand/colorcomparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorComparisonMode extends System.Enum
```

Gibt an, wie Farben während des Magic‑Wand‑Algorithmus verglichen werden.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [RgbDefault](#RgbDefault) | Farben werden im RGB-Farbraum verglichen. |
| [YuvDefault](#YuvDefault) | Farben werden im YUV-Farbraum verglichen. |
| [YuvLessLumaSensitive](#YuvLessLumaSensitive) | Farben werden im YUV-Farbraum verglichen. |
| [Custom](#Custom) | Der Farbvergleich-Algorithmus wird vom Benutzer definiert. |
### RgbDefault {#RgbDefault}
```
public static final int RgbDefault
```


Farben werden im RGB-Farbraum verglichen. Jede Farbabweichung muss den Schwellenwert erfüllen.

### YuvDefault {#YuvDefault}
```
public static final int YuvDefault
```


Farben werden im YUV-Farbraum verglichen. Jede Farbabweichung muss den Schwellenwert erfüllen.

### YuvLessLumaSensitive {#YuvLessLumaSensitive}
```
public static final int YuvLessLumaSensitive
```


Farben werden im YUV-Farbraum verglichen. Farbinfo-Unterschiede müssen den Schwellenwert erfüllen, der Schwellenwert für die Luminanzkomponente ist verdoppelt.

### Custom {#Custom}
```
public static final int Custom
```


Der Farbvergleich-Algorithmus wird vom Benutzer definiert.

