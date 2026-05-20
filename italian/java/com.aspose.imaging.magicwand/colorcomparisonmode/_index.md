---
title: "ColorComparisonMode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Specifica come i colori vengono confrontati durante l'algoritmo Magic Wand."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.magicwand/colorcomparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorComparisonMode extends System.Enum
```

Specifica come i colori vengono confrontati durante l'algoritmo Magic Wand.
## Campi

| Campo | Descrizione |
| --- | --- |
| [RgbDefault](#RgbDefault) | I colori sono confrontati nello spazio colore RGB. |
| [YuvDefault](#YuvDefault) | I colori sono confrontati nello spazio colore YUV. |
| [YuvLessLumaSensitive](#YuvLessLumaSensitive) | I colori sono confrontati nello spazio colore YUV. |
| [Custom](#Custom) | L'algoritmo di confronto colore è definito dall'utente. |
### RgbDefault {#RgbDefault}
```
public static final int RgbDefault
```


I colori sono confrontati nello spazio colore RGB. Ogni differenza di colore deve soddisfare la soglia.

### YuvDefault {#YuvDefault}
```
public static final int YuvDefault
```


I colori sono confrontati nello spazio colore YUV. Ogni differenza di colore deve soddisfare la soglia.

### YuvLessLumaSensitive {#YuvLessLumaSensitive}
```
public static final int YuvLessLumaSensitive
```


I colori sono confrontati nello spazio colore YUV. Le differenze di informazioni colore devono soddisfare la soglia, la soglia per il componente di luminanza è raddoppiata.

### Custom {#Custom}
```
public static final int Custom
```


L'algoritmo di confronto colore è definito dall'utente.

