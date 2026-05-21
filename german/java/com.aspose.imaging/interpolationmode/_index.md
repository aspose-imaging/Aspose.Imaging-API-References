---
title: "Interpolationsmodus"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Aufzählung com.aspose.imaging.InterpolationMode gibt den Algorithmus an, der verwendet wird, wenn Bilder skaliert oder rotiert werden."
type: docs
weight: 65
url: /de/java/com.aspose.imaging/interpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class InterpolationMode extends System.Enum
```

Die Aufzählung `com.aspose.imaging.InterpolationMode` gibt den Algorithmus an, der verwendet wird, wenn Bilder skaliert oder rotiert werden.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Invalid](#Invalid) | Ungültiger Interpolationsmodus. |
| [Default](#Default) | Gibt den Standardmodus an. |
| [Low](#Low) | Gibt eine Interpolation von niedriger Qualität an. |
| [High](#High) | Gibt eine Interpolation von hoher Qualität an. |
| [Bilinear](#Bilinear) | Gibt bilineare Interpolation an. |
| [Bicubic](#Bicubic) | Gibt bikubische Interpolation an. |
| [NearestNeighbor](#NearestNeighbor) | Gibt die nächstgelegene Nachbarinterpolation an. |
| [HighQualityBilinear](#HighQualityBilinear) | Gibt die hochwertige, bilineare Interpolation an. |
| [HighQualityBicubic](#HighQualityBicubic) | Gibt die hochwertige, bikubische Interpolation an. |
### Invalid {#Invalid}
```
public static final int Invalid
```


Ungültiger Interpolationsmodus.

### Default {#Default}
```
public static final int Default
```


Gibt den Standardmodus an.

### Low {#Low}
```
public static final int Low
```


Gibt eine Interpolation von niedriger Qualität an.

### High {#High}
```
public static final int High
```


Gibt eine Interpolation von hoher Qualität an.

### Bilinear {#Bilinear}
```
public static final int Bilinear
```


Gibt die bilineare Interpolation an. Es wird keine Vorfilterung durchgeführt. Dieser Modus ist nicht geeignet, ein Bild unter 50 % seiner Originalgröße zu verkleinern.

### Bicubic {#Bicubic}
```
public static final int Bicubic
```


Gibt die bikubische Interpolation an. Es wird keine Vorfilterung durchgeführt. Dieser Modus ist nicht geeignet, ein Bild unter 25 % seiner Originalgröße zu verkleinern.

### NearestNeighbor {#NearestNeighbor}
```
public static final int NearestNeighbor
```


Gibt die nächstgelegene Nachbarinterpolation an.

### HighQualityBilinear {#HighQualityBilinear}
```
public static final int HighQualityBilinear
```


Gibt die hochwertige, bilineare Interpolation an. Vorfilterung wird durchgeführt, um ein hochwertiges Verkleinern zu gewährleisten.

### HighQualityBicubic {#HighQualityBicubic}
```
public static final int HighQualityBicubic
```


Gibt die hochwertige, bikubische Interpolation an. Vorfilterung wird durchgeführt, um ein hochwertiges Verkleinern zu gewährleisten. Dieser Modus erzeugt die qualitativ hochwertigsten transformierten Bilder.

