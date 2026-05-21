---
title: "PixelDataFormat"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El formato de datos de píxel."
type: docs
weight: 84
url: /es/java/com.aspose.imaging/pixeldataformat/
---
**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

El formato de datos de píxel. Este es un objeto inmutable.
## Campos

| Campo | Descripción |
| --- | --- |
| [Grayscale](#Grayscale) | Obtiene el [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) definido para 8 bits por píxel con 8 bits que representan la intensidad en escala de grises en el intervalo 0-255. |
| [Grayscale16](#Grayscale16) | Definido para 16 bits por píxel con hasta 16 bits que representan la intensidad en escala de grises. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getRgb32Bpp()](#getRgb32Bpp--) | Obtiene el `PixelDataFormat` definido para 32 bits por píxel con 8 bits para cada uno de alfa, rojo, verde y azul. |
| [getCmyk()](#getCmyk--) | Obtiene el `PixelDataFormat` definido para 32 bits por píxel con 8 bits para cada uno de cian, magenta, amarillo y negro. |
| [getCmyka()](#getCmyka--) | Obtiene el acmyk. |
| [getRgb24Bpp()](#getRgb24Bpp--) | Obtiene el `PixelDataFormat` definido para 24 bits por píxel con 8 bits para cada uno de alfa, rojo, verde y azul, alfa no está definido. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | Obtiene el `PixelDataFormat` definido para 16 bits por píxel con 5 bits para cada uno de rojo, verde y azul, alfa no está definido. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | Obtiene el `PixelDataFormat` definido para 16 bits por píxel con 5 bits para rojo, 6 bits para verde y 5 bits para azul, alfa no está definido. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Obtiene el `PixelDataFormat` definido para indexado de 8 bits por color. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Obtiene el `PixelDataFormat` definido para indexado de 4 bits por color. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Obtiene el `PixelDataFormat` definido para indexado de 2 bits por color. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Obtiene el `PixelDataFormat` definido para indexado de 1 bit por color. |
| [getYCbCr()](#getYCbCr--) | Obtiene el `PixelDataFormat` definido para 24 bits por píxel con 8 bits para cada uno de los componentes de croma luma, diferencia de azul y diferencia de rojo. |
| [getYcck()](#getYcck--) | Obtiene el `PixelDataFormat` definido para 32 bits por píxel con 8 bits para cada uno de los componentes de croma luma, diferencia de azul, diferencia de rojo y negro. |
| [getRgba32Bpp()](#getRgba32Bpp--) | Obtiene el `PixelDataFormat` definido para 32 bits por píxel con 8 bits para cada uno de alfa, rojo, verde y azul. |
| [getRgb24BppPng()](#getRgb24BppPng--) | Obtiene el `PixelDataFormat` definido para 24 bits por píxel con 8 bits para cada uno de alfa, rojo, verde y azul, alfa no está definido. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | Obtiene el `PixelDataFormat` definido para 16 bits por píxel con 8 bits que representan la intensidad en escala de grises en el intervalo 0-255 y un componente alfa adicional de 8 bits. |
| [getPixelFormat()](#getPixelFormat--) | Obtiene el formato de píxel. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene los bits por píxel. |
| [getChannelsCount()](#getChannelsCount--) | Obtiene el recuento de canales. |
| [getChannelBits()](#getChannelBits--) | Obtiene el recuento de bits para cada canal. |
| [getCaption()](#getCaption--) | Obtiene la leyenda del formato de datos de píxel. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Obtiene el color en escala de grises con un número especificado de bits por muestra. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Obtiene el color GrayscaleAlpha con un número especificado de bits por muestra. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Obtiene el color GrayscaleAlpha con un número especificado de bits por muestra. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Obtiene el color RGB con un número especificado de bits por muestra. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Obtiene el color RGB con un número especificado de bits por muestra. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Obtiene el color RGBA con un número especificado de bits por muestra. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Obtiene el color RGBA con un número especificado de bits por muestra. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Obtiene el color indexado BGRA con un número especificado de bits por muestra. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Obtiene el color BGRA con un número especificado de bits por muestra. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Obtiene el color BGR con un número especificado de bits por muestra. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Obtiene el color YCbCr con un número especificado de bits por muestra. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Obtiene el color YCbCr con un número especificado de bits por muestra. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Obtiene el color CMYK con un número especificado de bits por muestra. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Obtiene el color CMYK con un número especificado de bits por muestra. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Obtiene el color CMYKA con un número especificado de bits por muestra. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Obtiene el color YCCK con un número especificado de bits por muestra. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Obtiene el color CIE Lab con un número especificado de bits por muestra. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Devuelve el resultado de desigualdad para dos clases `PixelDataFormat`. |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Devuelve el resultado de igualdad para dos clases `PixelDataFormat`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si el `System.Object` especificado es igual a esta instancia. |
| [hashCode()](#hashCode--) | Devuelve un código hash para esta instancia. |
| [toString()](#toString--) | Devuelve una `System.String` que representa esta instancia. |
### Grayscale {#Grayscale}
```
public static final PixelDataFormat Grayscale
```


Obtiene el [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) definido para 8 bits por píxel con 8 bits que representan la intensidad en escala de grises en el intervalo 0-255.

Valor: El [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) definido para 8 bits por píxel con 8 bits que representan la intensidad en escala de grises en el intervalo 0-255.

### Grayscale16 {#Grayscale16}
```
public static final PixelDataFormat Grayscale16
```


Definido para 16 bits por píxel con hasta 16 bits que representan la intensidad en escala de grises.

### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


Obtiene el `PixelDataFormat` definido para 32 bits por píxel con 8 bits para cada uno de alfa, rojo, verde y azul.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getCmyk() {#getCmyk--}
```
public static PixelDataFormat getCmyk()
```


Obtiene el `PixelDataFormat` definido para 32 bits por píxel con 8 bits para cada uno de cian, magenta, amarillo y negro.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


Obtiene el acmyk.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


Obtiene el `PixelDataFormat` definido para 24 bits por píxel con 8 bits para cada uno de alfa, rojo, verde y azul, alfa no está definido.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


Obtiene el `PixelDataFormat` definido para 16 bits por píxel con 5 bits para cada uno de rojo, verde y azul, alfa no está definido.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


Obtiene el `PixelDataFormat` definido para 16 bits por píxel con 5 bits para rojo, 6 bits para verde y 5 bits para azul, alfa no está definido.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


Obtiene el `PixelDataFormat` definido para 8 bits indexados por color. El almacenamiento de datos de píxel indexado está destinado a permitir el almacenamiento y la recuperación de datos en cualquier lugar donde se use la paleta de colores. Úselo con precaución, ya que puede requerir conversión de una paleta a otra o de RGBA a modelo de color indexado.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 8 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


Obtiene el `PixelDataFormat` definido para 4 bits indexados por color. El almacenamiento de datos de píxel indexado está destinado a permitir el almacenamiento y la recuperación de datos en cualquier lugar donde se use la paleta de colores. Úselo con precaución, ya que puede requerir conversión de una paleta a otra o de RGBA a modelo de color indexado.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 4 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


Obtiene el `PixelDataFormat` definido para 2 bits indexados por color. El almacenamiento de datos de píxel indexado está destinado a permitir el almacenamiento y la recuperación de datos en cualquier lugar donde se use la paleta de colores. Úselo con precaución, ya que puede requerir conversión de una paleta a otra o de RGBA a modelo de color indexado.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 2 bit per color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


Obtiene el `PixelDataFormat` definido para 1 bit indexado por color. El almacenamiento de datos de píxel indexado está destinado a permitir el almacenamiento y la recuperación de datos en cualquier lugar donde se use la paleta de colores. Úselo con precaución, ya que puede requerir conversión de una paleta a otra o de RGBA a modelo de color indexado.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 1 bit per color.
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


Obtiene el `PixelDataFormat` definido para 24 bits por píxel con 8 bits para cada uno de los componentes de croma luma, diferencia de azul y diferencia de rojo.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


Obtiene el `PixelDataFormat` definido para 32 bits por píxel con 8 bits para cada uno de los componentes de croma luma, diferencia de azul, diferencia de rojo y negro.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


Obtiene el `PixelDataFormat` definido para 32 bits por píxel con 8 bits para cada uno de alfa, rojo, verde y azul.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


Obtiene el `PixelDataFormat` definido para 24 bits por píxel con 8 bits para cada uno de alfa, rojo, verde y azul, alfa no está definido.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


Obtiene el `PixelDataFormat` definido para 16 bits por píxel con 8 bits que representan la intensidad en escala de grises en el intervalo 0-255 y un componente alfa adicional de 8 bits.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Obtiene el formato de píxel.

**Returns:**
int - El formato de píxel.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene los bits por píxel.

**Returns:**
int - Los bits por píxel.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Obtiene el recuento de canales.

**Returns:**
int - El recuento de canales.
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Obtiene el recuento de bits para cada canal.

**Returns:**
int[] - Los bits del canal.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Obtiene la leyenda del formato de datos de píxel.

**Returns:**
java.lang.String
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Obtiene el color en escala de grises con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Obtiene el color GrayscaleAlpha con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Obtiene el color GrayscaleAlpha con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |
| alphaChannelBits | int | El número de bits por muestra en el canal alfa. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Obtiene el color RGB con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Obtiene el color RGB con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerRedChannel | int | El número de bits por canal Rojo. |
| bitsPerGreenChannel | int | El número de bits por canal Verde. |
| bitsPerBlueChannel | int | El número de bits por canal Azul. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Obtiene el color RGBA con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Obtiene el color RGBA con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerRedChannel | int | El número de bits por canal Rojo. |
| bitsPerGreenChannel | int | El número de bits por canal Verde. |
| bitsPerBlueChannel | int | El número de bits por canal Azul. |
| bitsPerAlphaChannel | int | El número de bits por canal Alfa. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Obtiene el color indexado BGRA con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Obtiene el color BGRA con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Obtiene el color BGR con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGR color.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Obtiene el color YCbCr con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Obtiene el color YCbCr con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerY | int | El número de bits por canal Y. |
| bitsPerCb | int | El número de bits por canal Cb. |
| bitsPerCr | int | El número de bits por canal Cr. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Obtiene el color CMYK con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Obtiene el color CMYK con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerCyanChannel | int | El número de bits por canal Cian. |
| bitsPerMagentaChannel | int | El número de bits por canal Magenta. |
| bitsPerYellowChannel | int | El número de bits por canal Yellow. |
| bitsPerKeyChannel | int | El número de bits por canal Key. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Obtiene el color CMYKA con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerCyanChannel | int | El número de bits por canal Cian. |
| bitsPerMagentaChannel | int | El número de bits por canal Magenta. |
| bitsPerYellowChannel | int | El número de bits por canal Yellow. |
| bitsPerKeyChannel | int | El número de bits por canal Key. |
| bitsPerAlphaChannel | int | El número de bits por canal Alfa. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Obtiene el color YCCK con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerSample | int | El número de bits por muestra. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCCK color.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Obtiene el color CIE Lab con un número especificado de bits por muestra.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bitsPerL | int | El número de bits por canal L. |
| bitsPerA | int | El número de bits por canal A. |
| bitsPerB | int | El número de bits por canal B. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CIE Lab color.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Devuelve el resultado de desigualdad para dos clases `PixelDataFormat`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | El primer `PixelDataFormat` a comparar. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | El segundo `PixelDataFormat` a comparar. |

**Returns:**
boolean - Verdadero si ambos `pixelFormat1` y `pixelFormat2` contienen datos no iguales o uno de los parámetros es nulo.
### op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Devuelve el resultado de igualdad para dos clases `PixelDataFormat`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | El primer `PixelDataFormat` a comparar. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | El segundo `PixelDataFormat` a comparar. |

**Returns:**
boolean - Verdadero si ambos `pixelFormat1` y `pixelFormat2` contienen datos iguales o ambos parámetros son nulos.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si el `System.Object` especificado es igual a esta instancia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El `System.Object` para comparar con esta instancia. |

**Returns:**
boolean - `true` si el `System.Object` especificado es igual a esta instancia; de lo contrario, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Devuelve un código hash para esta instancia.

**Returns:**
int - Un código hash para esta instancia, adecuado para su uso en algoritmos de hash y estructuras de datos como una tabla hash.
### toString() {#toString--}
```
public String toString()
```


Devuelve una `System.String` que representa esta instancia.

**Returns:**
java.lang.String - Un `System.String` que representa esta instancia.
