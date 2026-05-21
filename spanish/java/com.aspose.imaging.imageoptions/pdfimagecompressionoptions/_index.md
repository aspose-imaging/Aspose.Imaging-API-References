---
title: "PdfImageCompressionOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Opciones de compresión de imágenes PDF"
type: docs
weight: 35
url: /es/java/com.aspose.imaging.imageoptions/pdfimagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfImageCompressionOptions extends System.Enum
```

Opciones de compresión de imágenes PDF
## Campos

| Campo | Descripción |
| --- | --- |
| [Auto](#Auto) | Selecciona automáticamente la compresión más adecuada para cada imagen. |
| [None](#None) | Guarda los bytes de imagen sin procesar, lo que resulta en archivos PDF más grandes. |
| [Rle](#Rle) | Compresión Run Length. |
| [Flate](#Flate) | Compresión Flate. |
| [LzwBaselinePredictor](#LzwBaselinePredictor) | La selección del predictor está restringida al predictor PNG Paeth para acelerar el proceso. |
| [LzwOptimizedPredictor](#LzwOptimizedPredictor) | La selección del predictor es más complicada y debería producir tamaños de imagen más pequeños, pero lleva más tiempo. |
| [Jpeg](#Jpeg) | Compresión JPEG. |
| [Ccitt3](#Ccitt3) | /CCITTFaxDecode/DecodeParms/K 0/Columns 173 No admite transparencia. |
| [Ccitt4](#Ccitt4) | /CCITTFaxDecode/DecodeParms/K -1/Columns 173 No admite transparencia. |
### Auto {#Auto}
```
public static final int Auto
```


Selecciona automáticamente la compresión más adecuada para cada imagen.

### None {#None}
```
public static final int None
```


Guarda los bytes de imagen sin procesar, lo que resulta en archivos PDF más grandes.

### Rle {#Rle}
```
public static final int Rle
```


Compresión Run Length.

### Flate {#Flate}
```
public static final int Flate
```


Compresión Flate.

### LzwBaselinePredictor {#LzwBaselinePredictor}
```
public static final int LzwBaselinePredictor
```


La selección del predictor está restringida al predictor PNG Paeth para acelerar el proceso. En la práctica funciona sorprendentemente bien. Mejor que [LzwOptimizedPredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\#LzwOptimizedPredictor).

### LzwOptimizedPredictor {#LzwOptimizedPredictor}
```
public static final int LzwOptimizedPredictor
```


La selección del predictor es más complicada y debería producir tamaños de imagen más pequeños, pero lleva más tiempo. RFC 2083 dice que es la mejor opción. Pero en los datos de prueba el predictor de referencia [LzwBaselinePredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\#LzwBaselinePredictor) sobresale, dejando al predictor optimizado atrás con una ganancia de tasa de compresión del 25‑40 %.

### Jpeg {#Jpeg}
```
public static final int Jpeg
```


Compresión JPEG. No admite transparencia.

### Ccitt3 {#Ccitt3}
```
public static final int Ccitt3
```


/CCITTFaxDecode/DecodeParms/K 0/Columns 173 No admite transparencia.

### Ccitt4 {#Ccitt4}
```
public static final int Ccitt4
```


/CCITTFaxDecode/DecodeParms/K -1/Columns 173 No admite transparencia.

