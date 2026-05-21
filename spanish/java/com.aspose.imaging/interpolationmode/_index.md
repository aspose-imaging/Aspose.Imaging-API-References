---
title: "Modo de interpolación"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración com.aspose.imaging.InterpolationMode especifica el algoritmo que se utiliza cuando las imágenes se escalan o rotan."
type: docs
weight: 65
url: /es/java/com.aspose.imaging/interpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class InterpolationMode extends System.Enum
```

La enumeración `com.aspose.imaging.InterpolationMode` especifica el algoritmo que se utiliza cuando las imágenes se escalan o rotan.
## Campos

| Campo | Descripción |
| --- | --- |
| [Invalid](#Invalid) | Modo de interpolación no válido. |
| [Default](#Default) | Especifica el modo predeterminado. |
| [Low](#Low) | Especifica interpolación de baja calidad. |
| [High](#High) | Especifica interpolación de alta calidad. |
| [Bilinear](#Bilinear) | Especifica interpolación bilineal. |
| [Bicubic](#Bicubic) | Especifica interpolación bicúbica. |
| [NearestNeighbor](#NearestNeighbor) | Especifica interpolación por vecino más cercano. |
| [HighQualityBilinear](#HighQualityBilinear) | Especifica interpolación bilineal de alta calidad. |
| [HighQualityBicubic](#HighQualityBicubic) | Especifica interpolación bicúbica de alta calidad. |
### Invalid {#Invalid}
```
public static final int Invalid
```


Modo de interpolación no válido.

### Default {#Default}
```
public static final int Default
```


Especifica el modo predeterminado.

### Low {#Low}
```
public static final int Low
```


Especifica interpolación de baja calidad.

### High {#High}
```
public static final int High
```


Especifica interpolación de alta calidad.

### Bilinear {#Bilinear}
```
public static final int Bilinear
```


Especifica interpolación bilineal. No se realiza prefiltrado. Este modo no es adecuado para reducir una imagen por debajo del 50 % de su tamaño original.

### Bicubic {#Bicubic}
```
public static final int Bicubic
```


Especifica interpolación bicúbica. No se realiza prefiltrado. Este modo no es adecuado para reducir una imagen por debajo del 25 % de su tamaño original.

### NearestNeighbor {#NearestNeighbor}
```
public static final int NearestNeighbor
```


Especifica interpolación por vecino más cercano.

### HighQualityBilinear {#HighQualityBilinear}
```
public static final int HighQualityBilinear
```


Especifica interpolación bilineal de alta calidad. Se realiza prefiltrado para garantizar una reducción de alta calidad.

### HighQualityBicubic {#HighQualityBicubic}
```
public static final int HighQualityBicubic
```


Especifica interpolación bicúbica de alta calidad. Se realiza prefiltrado para garantizar una reducción de alta calidad. Este modo produce las imágenes transformadas de mayor calidad.

