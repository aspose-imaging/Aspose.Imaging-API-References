---
title: "WmfCompression"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración Compression especifica el tipo de compresión para una imagen de mapa de bits."
type: docs
weight: 16
url: /es/java/com.aspose.imaging.fileformats.wmf.consts/wmfcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfCompression extends System.Enum
```

La enumeración Compression especifica el tipo de compresión para una imagen de mapa de bits.
## Campos

| Campo | Descripción |
| --- | --- |
| [BI_RGB](#BI-RGB) | El mapa de bits está en formato rojo verde azul (RGB) sin comprimir que no está comprimido y no utiliza máscaras de color. |
| [BI_RLE8](#BI-RLE8) | Un formato RGB que utiliza compresión por codificación de longitud de ejecución (RLE) para mapas de bits de 8 bits por píxel. |
| [BI_RLE4](#BI-RLE4) | Un formato RGB que utiliza compresión RLE para mapas de bits de 4 bits por píxel. |
| [BI_BITFIELDS](#BI-BITFIELDS) | El mapa de bits no está comprimido y la tabla de colores consta de tres máscaras de color DWORD que especifican, respectivamente, los componentes rojo, verde y azul de cada píxel. |
| [BI_JPEG](#BI-JPEG) | La imagen es una imagen JPEG, según lo especificado en [JFIF]. |
| [BI_PNG](#BI-PNG) | La imagen es una imagen PNG, según lo especificado en [RFC2083]. |
| [BI_CMYK](#BI-CMYK) | La imagen es un formato CMYK sin comprimir. |
| [BI_CMYKRLE8](#BI-CMYKRLE8) | Un formato CMYK que utiliza compresión RLE para mapas de bits de 8 bits por píxel. |
| [BI_CMYKRLE4](#BI-CMYKRLE4) | Un formato CMYK que utiliza compresión RLE para mapas de bits de 4 bits por píxel. |
### BI_RGB {#BI-RGB}
```
public static final int BI_RGB
```


El mapa de bits está en formato rojo verde azul (RGB) sin comprimir que no está comprimido y no utiliza máscaras de color.

### BI_RLE8 {#BI-RLE8}
```
public static final int BI_RLE8
```


Un formato RGB que utiliza compresión por codificación de longitud de ejecución (RLE) para mapas de bits de 8 bits por píxel. La compresión usa un formato de 2 bytes que consiste en un byte de recuento seguido de un byte que contiene un índice de color.

### BI_RLE4 {#BI-RLE4}
```
public static final int BI_RLE4
```


Un formato RGB que utiliza compresión RLE para mapas de bits de 4 bits por píxel. La compresión usa un formato de 2 bytes que consiste en un byte de recuento seguido de dos índices de color de longitud de palabra.

### BI_BITFIELDS {#BI-BITFIELDS}
```
public static final int BI_BITFIELDS
```


El mapa de bits no está comprimido y la tabla de colores consta de tres máscaras de color DWORD que especifican, respectivamente, los componentes rojo, verde y azul de cada píxel. Esto es válido cuando se usa con mapas de bits de 16 y 32 bits por píxel.

### BI_JPEG {#BI-JPEG}
```
public static final int BI_JPEG
```


La imagen es una imagen JPEG, según lo especificado en [JFIF]. Este valor DEBE usarse solo en ciertas operaciones de mapa de bits, como el paso directo de JPEG. La aplicación DEBE consultar el soporte de paso directo, ya que no todos los dispositivos admiten el paso directo de JPEG. El uso de mapas de bits no RGB PUEDE limitar la portabilidad del metafichero a otros dispositivos. Por ejemplo, los contextos de dispositivo de pantalla generalmente no admiten este paso directo.

### BI_PNG {#BI-PNG}
```
public static final int BI_PNG
```


La imagen es una imagen PNG, según lo especificado en [RFC2083]. Este valor DEBE usarse solo en ciertas operaciones de mapa de bits, como el paso directo de JPEG/PNG. La aplicación DEBE consultar el soporte de paso directo, porque no todos los dispositivos admiten el paso directo de JPEG/PNG. El uso de mapas de bits no RGB PUEDE limitar la portabilidad del metafichero a otros dispositivos. Por ejemplo, los contextos de dispositivo de pantalla generalmente no admiten este paso directo.

### BI_CMYK {#BI-CMYK}
```
public static final int BI_CMYK
```


La imagen es un formato CMYK sin comprimir.

### BI_CMYKRLE8 {#BI-CMYKRLE8}
```
public static final int BI_CMYKRLE8
```


Un formato CMYK que utiliza compresión RLE para mapas de bits de 8 bits por píxel. La compresión usa un formato de 2 bytes que consiste en un byte de recuento seguido de un byte que contiene un índice de color.

### BI_CMYKRLE4 {#BI-CMYKRLE4}
```
public static final int BI_CMYKRLE4
```


Un formato CMYK que utiliza compresión RLE para mapas de bits de 4 bits por píxel. La compresión usa un formato de 2 bytes que consiste en un byte de recuento seguido de dos índices de color de longitud de palabra.

