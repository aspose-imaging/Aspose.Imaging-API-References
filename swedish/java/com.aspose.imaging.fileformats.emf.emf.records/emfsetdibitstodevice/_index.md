---
title: "EmfSetDiBitsToDevice"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_SETDIBITSTODEVICE-posten specificerar en blocköverföring av pixlar från angivna skanningslinjer i en källbitmap till en destinationsrektangel."
type: docs
weight: 124
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfBitmapRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfbitmaprecordtype)
```
public final class EmfSetDiBitsToDevice extends EmfBitmapRecordType
```

EMR\_SETDIBITSTODEVICE-posten specificerar en blocköverföring av pixlar från angivna skanningslinjer i en källbitmap till en destinationsrektangel.

Denna post stöder källbilder i JPEG- och PNG-format. Komprimeringsfältet i källbitmapens huvud specificerar bildformatet.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfSetDiBitsToDevice(EmfRecord source)](#EmfSetDiBitsToDevice-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfSetDiBitsToDevice`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBounds()](#getBounds--) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar destinationens avgränsningsrektangel i enhetsenheter. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar destinationens avgränsningsrektangel i enhetsenheter. |
| [getXDest()](#getXDest--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [setXDest(int value)](#setXDest-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [getYDest()](#getYDest--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [setYDest(int value)](#setYDest-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av destinationsrektangeln. |
| [getXSrc()](#getXSrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar x-koordinaten i pixlar för det nedre vänstra hörnet av källrektangeln. |
| [setXSrc(int value)](#setXSrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar x-koordinaten i pixlar för det nedre vänstra hörnet av källrektangeln. |
| [getYSrc()](#getYSrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar y-koordinaten i pixlar för det nedre vänstra hörnet av källrektangeln. |
| [setYSrc(int value)](#setYSrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar y-koordinaten i pixlar för det nedre vänstra hörnet av källrektangeln. |
| [getCxSrc()](#getCxSrc--) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar bredden i pixlar för källrektangeln. |
| [setCxSrc(int value)](#setCxSrc-int-) | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar bredden i pixlar för källrektangeln. |
| [getCySrc()](#getCySrc--) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar höjden i pixlar för källrektangeln |
| [setCySrc(int value)](#setCySrc-int-) | Hämtar eller anger ett 32-bitars signerat heltal som specificerar höjden i pixlar för källrektangeln |
| [getUsageSrc()](#getUsageSrc--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. |
| [setUsageSrc(int value)](#setUsageSrc-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. |
| [getIStartScan()](#getIStartScan--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar den första skanningslinjen i arrayen. |
| [setIStartScan(int value)](#setIStartScan-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar den första skanningslinjen i arrayen. |
| [getCScans()](#getCScans--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet skanningslinjer. |
| [setCScans(int value)](#setCScans-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet skanningslinjer. |
| [getSourceBitmap()](#getSourceBitmap--) | Hämtar eller anger en buffert som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_SETDIBITSTODEVICE-posten. |
| [setSourceBitmap(WmfDeviceIndependentBitmap value)](#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Hämtar eller anger en buffert som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_SETDIBITSTODEVICE-posten. |
### EmfSetDiBitsToDevice(EmfRecord source) {#EmfSetDiBitsToDevice-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetDiBitsToDevice(EmfRecord source)
```


Initierar en ny instans av klassen `EmfSetDiBitsToDevice`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar destinationens avgränsningsrektangel i enhetsenheter.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar destinationens avgränsningsrektangel i enhetsenheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getXDest() {#getXDest--}
```
public int getXDest()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av destinationsrektangeln.

**Returns:**
int
### setXDest(int value) {#setXDest-int-}
```
public void setXDest(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra hörnet av destinationsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getYDest() {#getYDest--}
```
public int getYDest()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av destinationsrektangeln.

**Returns:**
int
### setYDest(int value) {#setYDest-int-}
```
public void setYDest(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra hörnet av destinationsrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getXSrc() {#getXSrc--}
```
public int getXSrc()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar x-koordinaten i pixlar för det nedre vänstra hörnet av källrektangeln.

**Returns:**
int
### setXSrc(int value) {#setXSrc-int-}
```
public void setXSrc(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar x-koordinaten i pixlar för det nedre vänstra hörnet av källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getYSrc() {#getYSrc--}
```
public int getYSrc()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar y-koordinaten i pixlar för det nedre vänstra hörnet av källrektangeln.

**Returns:**
int
### setYSrc(int value) {#setYSrc-int-}
```
public void setYSrc(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar y-koordinaten i pixlar för det nedre vänstra hörnet av källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCxSrc() {#getCxSrc--}
```
public int getCxSrc()
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar bredden i pixlar för källrektangeln.

**Returns:**
int
### setCxSrc(int value) {#setCxSrc-int-}
```
public void setCxSrc(int value)
```


Hämtar eller anger ett 32‑bitars signerat heltal som specificerar bredden i pixlar för källrektangeln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCySrc() {#getCySrc--}
```
public int getCySrc()
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar höjden i pixlar för källrektangeln

**Returns:**
int
### setCySrc(int value) {#setCySrc-int-}
```
public void setCySrc(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som specificerar höjden i pixlar för källrektangeln

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getUsageSrc() {#getUsageSrc--}
```
public int getUsageSrc()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. Detta värde MÅSTE finnas i DIBColors‑enumerationen (avsnitt 2.1.9).

**Returns:**
int
### setUsageSrc(int value) {#setUsageSrc-int-}
```
public void setUsageSrc(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i färgtabellen i källbitmapens huvud ska tolkas. Detta värde MÅSTE finnas i DIBColors‑enumerationen (avsnitt 2.1.9).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getIStartScan() {#getIStartScan--}
```
public int getIStartScan()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar den första skanningslinjen i arrayen.

**Returns:**
int
### setIStartScan(int value) {#setIStartScan-int-}
```
public void setIStartScan(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar den första skanningslinjen i arrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCScans() {#getCScans--}
```
public int getCScans()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet skanningslinjer.

**Returns:**
int
### setCScans(int value) {#setCScans-int-}
```
public void setCScans(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet skanningslinjer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getSourceBitmap() {#getSourceBitmap--}
```
public WmfDeviceIndependentBitmap getSourceBitmap()
```


Hämtar eller anger en buffert som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_SETDIBITSTODEVICE-posten. Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setSourceBitmap(WmfDeviceIndependentBitmap value) {#setSourceBitmap-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setSourceBitmap(WmfDeviceIndependentBitmap value)
```


Hämtar eller anger en buffert som innehåller källbitmapen, vilken inte behöver vara sammanhängande med den fasta delen av EMR\_SETDIBITSTODEVICE-posten. Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

