---
title: "WmfDeviceIndependentBitmap"
second_title: "Aspose.Imaging för Java API-referens"
description: "DeviceIndependentBitmap-objektet definierar en bild i enhetsoberoende bitmap DIB-format."
type: docs
weight: 27
url: /sv/java/com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfDeviceIndependentBitmap extends MetaObject
```

DeviceIndependentBitmap-objektet definierar en bild i enhetsoberoende bitmap (DIB)-format.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfDeviceIndependentBitmap()](#WmfDeviceIndependentBitmap--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeader()](#getHeader--) | Hämtar eller anger antingen ett BitmapCoreHeader-objekt (avsnitt 2.2.2.2) eller ett BitmapInfoHeader-objekt (avsnitt 2.2.2.3) som specificerar information om bilden. |
| [setHeader(WmfBitmapBaseHeader value)](#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-) | Hämtar eller anger antingen ett BitmapCoreHeader-objekt (avsnitt 2.2.2.2) eller ett BitmapInfoHeader-objekt (avsnitt 2.2.2.3) som specificerar information om bilden. |
| [getColorsData()](#getColorsData--) | Hämtar eller anger en valfri array av antingen RGBQuad-objekt (avsnitt 2.2.2.20) eller 16-bitars osignerade heltal som definierar en färgtabell. |
| [setColorsData(byte[] value)](#setColorsData-byte---) | Hämtar eller anger en valfri array av antingen RGBQuad-objekt (avsnitt 2.2.2.20) eller 16-bitars osignerade heltal som definierar en färgtabell. |
| [getAData()](#getAData--) | Hämtar eller anger en bytearray som definierar bilden. |
| [setAData(byte[] value)](#setAData-byte---) | Hämtar eller anger en bytearray som definierar bilden. |
| [getCachedImage()](#getCachedImage--) | Hämtar den cachade rasterbilden. |
| [setCachedImage(byte[] value)](#setCachedImage-byte---) | Anger den cachade rasterbilden. |
### WmfDeviceIndependentBitmap() {#WmfDeviceIndependentBitmap--}
```
public WmfDeviceIndependentBitmap()
```


### getHeader() {#getHeader--}
```
public WmfBitmapBaseHeader getHeader()
```


Hämtar eller anger antingen ett BitmapCoreHeader-objekt (avsnitt 2.2.2.2) eller ett BitmapInfoHeader-objekt (avsnitt 2.2.2.3) som specificerar information om bilden.

**Returns:**
[WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
### setHeader(WmfBitmapBaseHeader value) {#setHeader-com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader-}
```
public void setHeader(WmfBitmapBaseHeader value)
```


Hämtar eller anger antingen ett BitmapCoreHeader-objekt (avsnitt 2.2.2.2) eller ett BitmapInfoHeader-objekt (avsnitt 2.2.2.3) som specificerar information om bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader) |  |

### getColorsData() {#getColorsData--}
```
public byte[] getColorsData()
```


Hämtar eller anger en valfri array av antingen RGBQuad-objekt (avsnitt 2.2.2.20) eller 16-bitars osignerade heltal som definierar en färgtabell. Storleken och innehållet i detta fält SKA bestämmas från metafilsposten eller objektet som innehåller detta DeviceIndependentBitmap samt från information i DIBHeaderInfo-fältet. Se ColorUsage‑enumerationen (avsnitt 2.1.1.6) och BitCount‑enumerationen (avsnitt 2.1.1.3) för ytterligare detaljer.

**Returns:**
byte[]
### setColorsData(byte[] value) {#setColorsData-byte---}
```
public void setColorsData(byte[] value)
```


Hämtar eller anger en valfri array av antingen RGBQuad-objekt (avsnitt 2.2.2.20) eller 16-bitars osignerade heltal som definierar en färgtabell. Storleken och innehållet i detta fält SKA bestämmas från metafilsposten eller objektet som innehåller detta DeviceIndependentBitmap samt från information i DIBHeaderInfo-fältet. Se ColorUsage‑enumerationen (avsnitt 2.1.1.6) och BitCount‑enumerationen (avsnitt 2.1.1.3) för ytterligare detaljer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getAData() {#getAData--}
```
public byte[] getAData()
```


Hämtar eller anger en bytearray som definierar bilden. Storleken och formatet på dessa data bestäms av information i DIBHeaderInfo-fältet.

**Returns:**
byte[]
### setAData(byte[] value) {#setAData-byte---}
```
public void setAData(byte[] value)
```


Hämtar eller anger en bytearray som definierar bilden. Storleken och formatet på dessa data bestäms av information i DIBHeaderInfo-fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getCachedImage() {#getCachedImage--}
```
public final byte[] getCachedImage()
```


Hämtar den cachade rasterbilden.

Värde: Den cachade bilden.

**Returns:**
byte[]
### setCachedImage(byte[] value) {#setCachedImage-byte---}
```
public void setCachedImage(byte[] value)
```


Anger den cachade rasterbilden.

Värde: Den cachade bilden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

