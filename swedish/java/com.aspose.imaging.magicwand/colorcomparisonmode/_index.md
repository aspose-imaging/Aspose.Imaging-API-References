---
title: "ColorComparisonMode"
second_title: "Aspose.Imaging för Java API-referens"
description: "Anger hur färger jämförs under Magic Wand-algoritmen."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.magicwand/colorcomparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorComparisonMode extends System.Enum
```

Anger hur färger jämförs under Magic Wand-algoritmen.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [RgbDefault](#RgbDefault) | Färger jämförs i RGB-färgrymden. |
| [YuvDefault](#YuvDefault) | Färger jämförs i YUV-färgrymden. |
| [YuvLessLumaSensitive](#YuvLessLumaSensitive) | Färger jämförs i YUV-färgrymden. |
| [Custom](#Custom) | Färgjämförelsealgoritmen definieras av användaren. |
### RgbDefault {#RgbDefault}
```
public static final int RgbDefault
```


Färger jämförs i RGB-färgrymden. Varje färgskillnad måste uppfylla tröskelvärdet.

### YuvDefault {#YuvDefault}
```
public static final int YuvDefault
```


Färger jämförs i YUV-färgrymden. Varje färgskillnad måste uppfylla tröskelvärdet.

### YuvLessLumaSensitive {#YuvLessLumaSensitive}
```
public static final int YuvLessLumaSensitive
```


Färger jämförs i YUV-färgrymden. Skillnader i färginformation måste uppfylla tröskelvärdet, tröskelvärdet för luminanskomponenten är fördubblat.

### Custom {#Custom}
```
public static final int Custom
```


Färgjämförelsealgoritmen definieras av användaren.

