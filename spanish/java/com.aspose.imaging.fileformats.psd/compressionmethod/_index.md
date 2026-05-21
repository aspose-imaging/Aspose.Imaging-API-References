---
title: "CompressionMethod"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Define el método de compresión utilizado para los datos de imagen."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.psd/compressionmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CompressionMethod extends System.Enum
```

Define el método de compresión utilizado para los datos de imagen.
## Campos

| Campo | Descripción |
| --- | --- |
| [Raw](#Raw) | Sin compresión. |
| [RLE](#RLE) | Los datos de imagen comprimidos con RLE comienzan con los recuentos de bytes para todas las líneas de escaneo (filas \\* canales), con cada recuento almacenado como un valor de dos bytes. |
| [ZipWithoutPrediction](#ZipWithoutPrediction) | ZIP sin predicción. |
| [ZipWithPrediction](#ZipWithPrediction) | ZIP con predicción. |
### Raw {#Raw}
```
public static final short Raw
```


Sin compresión. Los datos de imagen se almacenan como bytes sin procesar en orden planar RGBA. Eso significa que primero se escribe todo el dato R, luego todo el dato G, luego todo el dato B y finalmente todo el dato A.

### RLE {#RLE}
```
public static final short RLE
```


Los datos de imagen comprimidos con RLE comienzan con los recuentos de bytes para todas las líneas de escaneo (filas \\* canales), con cada recuento almacenado como un valor de dos bytes. A continuación se encuentran los datos comprimidos con RLE, con cada línea de escaneo comprimida por separado. La compresión RLE es el mismo algoritmo de compresión usado por la rutina PackBits del ROM de Macintosh y el estándar TIFF.

### ZipWithoutPrediction {#ZipWithoutPrediction}
```
public static final short ZipWithoutPrediction
```


ZIP sin predicción.

### ZipWithPrediction {#ZipWithPrediction}
```
public static final short ZipWithPrediction
```


ZIP con predicción.

