---
title: "WmfDeviceIndependentBitmap"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto DeviceIndependentBitmap define una imagen en formato de mapa de bits independiente del dispositivo (DIB)."
type: docs
weight: 27
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfDeviceIndependentBitmap extends MetaObject
```

El objeto DeviceIndependentBitmap define una imagen en formato bitmap independiente del dispositivo (DIB)
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getHeader()](#getHeader--) | Obtiene o establece ya sea un objeto BitmapCoreHeader (sección 2.2.2.2) o un objeto BitmapInfoHeader (sección 2.2.2.3) que especifica información sobre la imagen. |
| [setHeader(WmfBitmapBaseHeader value)](#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-) | Obtiene o establece ya sea un objeto BitmapCoreHeader (sección 2.2.2.2) o un objeto BitmapInfoHeader (sección 2.2.2.3) que especifica información sobre la imagen. |
| [getColorsData()](#getColorsData--) | Obtiene o establece una matriz opcional de ya sea objetos RGBQuad (sección 2.2.2.20) o enteros sin signo de 16 bits que definen una tabla de colores. |
| [setColorsData(byte[] value)](#setColorsData-byte---) | Obtiene o establece una matriz opcional de ya sea objetos RGBQuad (sección 2.2.2.20) o enteros sin signo de 16 bits que definen una tabla de colores. |
| [getAData()](#getAData--) | Obtiene o establece una matriz de bytes que define la imagen. |
| [setAData(byte[] value)](#setAData-byte---) | Obtiene o establece una matriz de bytes que define la imagen. |
| [getCachedImage()](#getCachedImage--) | Obtiene la imagen rasterizada en caché. |
| [setCachedImage(byte[] value)](#setCachedImage-byte---) | Establece la imagen rasterizada en caché. |
### WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap--}
```
public WmfDeviceIndependentBitmap()
```


### getHeader() {#getHeader--}
```
public WmfBitmapBaseHeader getHeader()
```


Obtiene o establece ya sea un objeto BitmapCoreHeader (sección 2.2.2.2) o un objeto BitmapInfoHeader (sección 2.2.2.3) que especifica información sobre la imagen.

**Returns:**
[WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
### setHeader(WmfBitmapBaseHeader value) {#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-}
```
public void setHeader(WmfBitmapBaseHeader value)
```


Obtiene o establece ya sea un objeto BitmapCoreHeader (sección 2.2.2.2) o un objeto BitmapInfoHeader (sección 2.2.2.3) que especifica información sobre la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader) |  |

### getColorsData() {#getColorsData--}
```
public byte[] getColorsData()
```


Obtiene o establece una matriz opcional de ya sea objetos RGBQuad (sección 2.2.2.20) o enteros sin signo de 16 bits que definen una tabla de colores. El tamaño y el contenido de este campo DEBERÍA determinarse a partir del registro de metarchivo u objeto que contiene este DeviceIndependentBitmap y de la información en el campo DIBHeaderInfo. Consulte la enumeración ColorUsage (sección 2.1.1.6) y la enumeración BitCount (sección 2.1.1.3) para obtener detalles adicionales.

**Returns:**
byte[]
### setColorsData(byte[] value) {#setColorsData-byte---}
```
public void setColorsData(byte[] value)
```


Obtiene o establece una matriz opcional de ya sea objetos RGBQuad (sección 2.2.2.20) o enteros sin signo de 16 bits que definen una tabla de colores. El tamaño y el contenido de este campo DEBERÍA determinarse a partir del registro de metarchivo u objeto que contiene este DeviceIndependentBitmap y de la información en el campo DIBHeaderInfo. Consulte la enumeración ColorUsage (sección 2.1.1.6) y la enumeración BitCount (sección 2.1.1.3) para obtener detalles adicionales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getAData() {#getAData--}
```
public byte[] getAData()
```


Obtiene o establece una matriz de bytes que define la imagen. El tamaño y el formato de estos datos se determinan mediante la información en el campo DIBHeaderInfo.

**Returns:**
byte[]
### setAData(byte[] value) {#setAData-byte---}
```
public void setAData(byte[] value)
```


Obtiene o establece una matriz de bytes que define la imagen. El tamaño y el formato de estos datos se determinan mediante la información en el campo DIBHeaderInfo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getCachedImage() {#getCachedImage--}
```
public final byte[] getCachedImage()
```


Obtiene la imagen rasterizada en caché.

Valor: La imagen en caché.

**Returns:**
byte[]
### setCachedImage(byte[] value) {#setCachedImage-byte---}
```
public void setCachedImage(byte[] value)
```


Establece la imagen rasterizada en caché.

Valor: La imagen en caché.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

