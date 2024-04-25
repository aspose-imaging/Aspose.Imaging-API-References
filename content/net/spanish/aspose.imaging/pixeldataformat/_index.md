---
title: PixelDataFormat
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El formato de datos de píxeles. Este es un objeto inmutable.
type: docs
weight: 10720
url: /es/aspose.imaging/pixeldataformat/
---
## PixelDataFormat class

El formato de datos de píxeles. Este es un objeto inmutable.

```csharp
public class PixelDataFormat
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [Cmyk](../../aspose.imaging/pixeldataformat/cmyk) { get; } | Obtiene el[`PixelDataFormat`](../pixeldataformat) definido para 32 bits por píxel con 8 bits para cada uno de los colores cian, magenta, amarillo y negro. |
| static [Cmyka](../../aspose.imaging/pixeldataformat/cmyka) { get; } | Obtiene el acmyk. |
| static [Grayscale](../../aspose.imaging/pixeldataformat/grayscale) { get; } | Obtiene el[`PixelDataFormat`](../pixeldataformat)definido para 8 bits por píxel con 8 bits que representan la intensidad de la escala de grises en el intervalo 0-255. |
| static [GrayscaleAlpha](../../aspose.imaging/pixeldataformat/grayscalealpha) { get; } | Obtiene el[`PixelDataFormat`](../pixeldataformat) definido para 16 bits por píxel con 8 bits que representan la intensidad de la escala de grises en el intervalo 0-255 y un componente alfa adicional de 8 bits. |
| static [Rgb16Bpp555](../../aspose.imaging/pixeldataformat/rgb16bpp555) { get; } | Obtiene el[`PixelDataFormat`](../pixeldataformat) definido para 16 bits por píxel con 5 bits para cada rojo, verde y azul, alfa no está definido. |
| static [Rgb16Bpp565](../../aspose.imaging/pixeldataformat/rgb16bpp565) { get; } | Obtiene el[`PixelDataFormat`](../pixeldataformat) definido para 16 bits por píxel con 5 bits para rojo, 6 bits para verde y 5 bits para azul, alfa no está definido. |
| static [Rgb24Bpp](../../aspose.imaging/pixeldataformat/rgb24bpp) { get; } | Obtiene el[`PixelDataFormat`](../pixeldataformat) definido para 24 bits por píxel con 8 bits para cada uno de los alfa, rojo, verde y azul, alfa no está definido. |
| static [Rgb24BppPng](../../aspose.imaging/pixeldataformat/rgb24bpppng) { get; } | Obtiene el[`PixelDataFormat`](../pixeldataformat) definido para 24 bits por píxel con 8 bits para cada uno de los alfa, rojo, verde y azul, alfa no está definido. |
| static [Rgb32Bpp](../../aspose.imaging/pixeldataformat/rgb32bpp) { get; } | Obtiene el[`PixelDataFormat`](../pixeldataformat) definido para 32 bits por píxel con 8 bits para cada uno de los alfa, rojo, verde y azul. |
| static [Rgba32Bpp](../../aspose.imaging/pixeldataformat/rgba32bpp) { get; } | Obtiene el[`PixelDataFormat`](../pixeldataformat) definido para 32 bits por píxel con 8 bits para cada uno de los alfa, rojo, verde y azul. |
| static [RgbIndexed1Bpp](../../aspose.imaging/pixeldataformat/rgbindexed1bpp) { get; } | Obtiene el[`PixelDataFormat`](../pixeldataformat) definido para 1 bit indexado por color. El almacenamiento de datos de píxeles indexados está diseñado para permitir el almacenamiento y la recuperación de datos en cualquier lugar donde se utilice la paleta de colores. Úselo con precaución, ya que puede requerir la conversión de una paleta a otra o de RGBA a un modelo de color indexado . |
| static [RgbIndexed2Bpp](../../aspose.imaging/pixeldataformat/rgbindexed2bpp) { get; } | Obtiene el[`PixelDataFormat`](../pixeldataformat)definido para 2 bits indexados por color. El almacenamiento de datos de píxeles indexados está diseñado para permitir el almacenamiento y la recuperación de datos en cualquier lugar donde se use la paleta de colores. Úselo con precaución, ya que puede requerir la conversión de una paleta a otra o de RGBA a un modelo de color indexado . |
| static [RgbIndexed4Bpp](../../aspose.imaging/pixeldataformat/rgbindexed4bpp) { get; } | Obtiene el[`PixelDataFormat`](../pixeldataformat) definido para 4 bits indexados por color. El almacenamiento de datos de píxeles indexados está diseñado para permitir el almacenamiento y la recuperación de datos en cualquier lugar donde se utilice la paleta de colores. Úselo con precaución, ya que puede requerir la conversión de una paleta a otra o de RGBA a un modelo de color indexado . |
| static [RgbIndexed8Bpp](../../aspose.imaging/pixeldataformat/rgbindexed8bpp) { get; } | Obtiene el[`PixelDataFormat`](../pixeldataformat)definido para 8 bits indexados por color. El almacenamiento de datos de píxeles indexados está destinado a permitir el almacenamiento y la recuperación de datos en cualquier lugar donde se utilice la paleta de colores. Úselo con precaución, ya que puede requerir la conversión de una paleta a otra o de RGBA a un modelo de color indexado . |
| static [YCbCr](../../aspose.imaging/pixeldataformat/ycbcr) { get; } | Obtiene el[`PixelDataFormat`](../pixeldataformat) definido para 24 bits por píxel con 8 bits para cada uno de los componentes de croma de luminancia, diferencia de azul y diferencia de rojo. |
| static [Ycck](../../aspose.imaging/pixeldataformat/ycck) { get; } | Obtiene el[`PixelDataFormat`](../pixeldataformat) definido para 32 bits por píxel con 8 bits para cada uno de los componentes de luminancia, diferencia de azul, diferencia de rojo y croma negro. |
| [BitsPerPixel](../../aspose.imaging/pixeldataformat/bitsperpixel) { get; } | Obtiene los bits por píxel. |
| [Caption](../../aspose.imaging/pixeldataformat/caption) { get; } | Obtiene el título de formato de datos de píxeles. |
| [ChannelBits](../../aspose.imaging/pixeldataformat/channelbits) { get; } | Obtiene el conteo de bits para cada canal. |
| [ChannelsCount](../../aspose.imaging/pixeldataformat/channelscount) { get; } | Obtiene el conteo de canales. |
| [PixelFormat](../../aspose.imaging/pixeldataformat/pixelformat) { get; } | Obtiene el formato de píxel. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [GetBgr](../../aspose.imaging/pixeldataformat/getbgr)(int) | Obtiene el color BGR con un número específico de bits por muestra. |
| static [GetBgra](../../aspose.imaging/pixeldataformat/getbgra)(int) | Obtiene el color BGRA con un número específico de bits por muestra. |
| static [GetCieLab](../../aspose.imaging/pixeldataformat/getcielab)(int, int, int) | Obtiene color CIE Lab con un número específico de bits por muestra. |
| static [GetCmyk](../../aspose.imaging/pixeldataformat/getcmyk#getcmyk)(int) | Obtiene color CMYK con un número específico de bits por muestra. |
| static [GetCmyk](../../aspose.imaging/pixeldataformat/getcmyk#getcmyk_1)(int, int, int, int) | Obtiene color CMYK con un número específico de bits por muestra. |
| static [GetCmyka](../../aspose.imaging/pixeldataformat/getcmyka)(int, int, int, int, int) | Obtiene color CMYKA con un número específico de bits por muestra. |
| static [GetGrayscale](../../aspose.imaging/pixeldataformat/getgrayscale)(int) | Obtiene color en escala de grises con un número específico de bits por muestra. |
| static [GetGrayscaleAlpha](../../aspose.imaging/pixeldataformat/getgrayscalealpha#getgrayscalealpha)(int) | Obtiene el color GrayscaleAlpha con un número específico de bits por muestra. |
| static [GetGrayscaleAlpha](../../aspose.imaging/pixeldataformat/getgrayscalealpha#getgrayscalealpha_1)(int, int) | Obtiene el color GrayscaleAlpha con un número específico de bits por muestra. |
| static [GetRgb](../../aspose.imaging/pixeldataformat/getrgb#getrgb)(int) | Obtiene color RGB con un número específico de bits por muestra. |
| static [GetRgb](../../aspose.imaging/pixeldataformat/getrgb#getrgb_1)(int, int, int) | Obtiene color RGB con un número específico de bits por muestra. |
| static [GetRgba](../../aspose.imaging/pixeldataformat/getrgba#getrgba)(int) | Obtiene el color RGBA con un número específico de bits por muestra. |
| static [GetRgba](../../aspose.imaging/pixeldataformat/getrgba#getrgba_1)(int, int, int, int) | Obtiene el color RGBA con un número específico de bits por muestra. |
| static [GetRgbIndexed](../../aspose.imaging/pixeldataformat/getrgbindexed)(int) | Obtiene el color indexado BGRA con un número específico de bits por muestra. |
| static [GetYCbCr](../../aspose.imaging/pixeldataformat/getycbcr#getycbcr)(int) | Obtiene el color YCbCr con un número específico de bits por muestra. |
| static [GetYCbCr](../../aspose.imaging/pixeldataformat/getycbcr#getycbcr_1)(int, int, int) | Obtiene el color YCbCr con un número específico de bits por muestra. |
| static [GetYcck](../../aspose.imaging/pixeldataformat/getycck)(int) | Obtiene el color YCCK con un número específico de bits por muestra. |
| override [Equals](../../aspose.imaging/pixeldataformat/equals)(object) | Determina si el especificadoObject es igual a esta instancia. |
| override [GetHashCode](../../aspose.imaging/pixeldataformat/gethashcode)() | Devuelve un código hash para esta instancia. |
| override [ToString](../../aspose.imaging/pixeldataformat/tostring)() | Devuelve unString que representa esta instancia. |
| [operator ==](../../aspose.imaging/pixeldataformat/op_equality) | Devuelve resultado de igualdad para dos[`PixelDataFormat`](../pixeldataformat) clases. |
| [operator !=](../../aspose.imaging/pixeldataformat/op_inequality) | Devuelve resultado de no igualdad para dos[`PixelDataFormat`](../pixeldataformat) clases. |

### Ver también

* espacio de nombres [Aspose.Imaging](../../aspose.imaging)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
