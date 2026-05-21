---
title: "EmfLogPenEx"
second_title: "Aspose.Imaging för Java API-referens"
description: "LogPenEx‑objektet specificerar stilens bredd och färg för en utökad logisk penna."
type: docs
weight: 28
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPenEx extends EmfBasePen
```

LogPenEx-objektet specificerar stil, bredd och färg för en utökad logisk penna.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfLogPenEx()](#EmfLogPenEx--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | Hämtar eller anger pennstilen. |
| [setPenStyle(int value)](#setPenStyle-int-) | Hämtar eller anger pennstilen. |
| [getWidth()](#getWidth--) | Hämtar eller anger ett 32-bit osignerat heltal som specificerar bredden på den linje som pennan ritar. |
| [setWidth(int value)](#setWidth-int-) | Hämtar eller anger ett 32-bit osignerat heltal som specificerar bredden på den linje som pennan ritar. |
| [getBrushStyle()](#getBrushStyle--) | Hämtar eller anger ett 32-bit osignerat heltal som specificerar en penselstil för pennan från WMF BrushStyle‑enumerationen ([MS-WMF] sektion 2.1.1.4). |
| [setBrushStyle(int value)](#setBrushStyle-int-) | Hämtar eller anger ett 32-bit osignerat heltal som specificerar en penselstil för pennan från WMF BrushStyle‑enumerationen ([MS-WMF] sektion 2.1.1.4). |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Hämtar eller anger ett WMF ColorRef‑objekt ([MS-WMF] sektion 2.2.2.8). |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Hämtar eller anger ett WMF ColorRef‑objekt ([MS-WMF] sektion 2.2.2.8). |
| [getBrushHatch()](#getBrushHatch--) | Hämtar eller anger penselns hakmönster. |
| [setBrushHatch(int value)](#setBrushHatch-int-) | Hämtar eller anger penselns hakmönster. |
| [getNumStyleEntities()](#getNumStyleEntities--) | Hämtar antalet element i arrayen som specificeras i StyleEntry‑fältet. |
| [getStyleEntry()](#getStyleEntry--) | Hämtar eller anger en valfri array av 32-bit osignerade heltal som definierar längderna på streck och mellanrum i den linje som pennan ritar, när värdet av PenStyle är PS\_USERSTYLE linjestil för pennan. |
| [setStyleEntry(int[] value)](#setStyleEntry-int---) | Hämtar eller anger en valfri array av 32-bit osignerade heltal som definierar längderna på streck och mellanrum i den linje som pennan ritar, när värdet av PenStyle är PS\_USERSTYLE linjestil för pennan. |
| [getBrushDibPattern()](#getBrushDibPattern--) | Hämtar eller anger penselns dib‑mönster. |
| [setBrushDibPattern(WmfDeviceIndependentBitmap value)](#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Hämtar eller anger penselns dib‑mönster. |
### EmfLogPenEx() {#EmfLogPenEx--}
```
public EmfLogPenEx()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


Hämtar eller anger pennstilen.

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


Hämtar eller anger pennstilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar eller anger ett 32-bit osignerat heltal som specificerar bredden på den linje som pennan ritar. Om penntypen i PenStyle‑fältet är PS\_GEOMETRIC är detta värde bredden i logiska enheter; annars anges bredden i enheter för enheten. Om penntypen i PenStyle‑fältet är PS\_COSMETIC måste detta värde vara 0x00000001.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Hämtar eller anger ett 32-bit osignerat heltal som specificerar bredden på den linje som pennan ritar. Om penntypen i PenStyle‑fältet är PS\_GEOMETRIC är detta värde bredden i logiska enheter; annars anges bredden i enheter för enheten. Om penntypen i PenStyle‑fältet är PS\_COSMETIC måste detta värde vara 0x00000001.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


Hämtar eller anger ett 32-bit osignerat heltal som specificerar en penselstil för pennan från WMF BrushStyle‑enumerationen ([MS-WMF] sektion 2.1.1.4). Om penntypen i PenStyle‑fältet är PS\_GEOMETRIC måste detta värde vara antingen BS\_SOLID eller BS\_HATCHED. Värdet i detta fält kan vara BS\_NULL, men endast om linjestilen som specificeras i PenStyle är PS\_NULL. BS\_NULL‑stilen BÖR användas för att specificera en pensel som inte har någon effekt.

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


Hämtar eller anger ett 32-bit osignerat heltal som specificerar en penselstil för pennan från WMF BrushStyle‑enumerationen ([MS-WMF] sektion 2.1.1.4). Om penntypen i PenStyle‑fältet är PS\_GEOMETRIC måste detta värde vara antingen BS\_SOLID eller BS\_HATCHED. Värdet i detta fält kan vara BS\_NULL, men endast om linjestilen som specificeras i PenStyle är PS\_NULL. BS\_NULL‑stilen BÖR användas för att specificera en pensel som inte har någon effekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Hämtar eller anger ett WMF ColorRef‑objekt ([MS-WMF] sektion 2.2.2.8). Tolkningen av detta fält beror på BrushStyle‑värdet, som visas i tabellen senare i detta avsnitt.

Värde: Den 32-bitars ARGB-färgen

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Hämtar eller anger ett WMF ColorRef‑objekt ([MS-WMF] sektion 2.2.2.8). Tolkningen av detta fält beror på BrushStyle‑värdet, som visas i tabellen senare i detta avsnitt.

Värde: Den 32-bitars ARGB-färgen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


Hämtar eller anger penselns hakmönster. Definitionen av detta fält beror på BrushStyle‑värdet, som visas i tabellen senare i detta avsnitt.

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


Hämtar eller anger penselns hakmönster. Definitionen av detta fält beror på BrushStyle‑värdet, som visas i tabellen senare i detta avsnitt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getNumStyleEntities() {#getNumStyleEntities--}
```
public int getNumStyleEntities()
```


Hämtar antalet element i arrayen som specificeras i StyleEntry‑fältet. Detta värde BÖR vara noll om PenStyle inte specificerar PS\_USERSTYLE.

**Returns:**
int
### getStyleEntry() {#getStyleEntry--}
```
public int[] getStyleEntry()
```


Hämtar eller anger en valfri array av 32-bit osignerade heltal som definierar längderna på streck och mellanrum i den linje som pennan ritar, när värdet av PenStyle är PS\_USERSTYLE linjestil för pennan. Arrayen innehåller ett antal poster som specificeras av NumStyleEntries, men den används som om den upprepades oändligt. Den första posten i arrayen specificerar längden på det första strecket. Den andra posten specificerar längden på det första mellanrummet. Därefter alternerar längderna på streck och mellanrum. Om penntypen i PenStyle‑fältet är PS\_GEOMETRIC anges längderna i logiska enheter; annars anges de i enheter för enheten.

**Returns:**
int[]
### setStyleEntry(int[] value) {#setStyleEntry-int---}
```
public void setStyleEntry(int[] value)
```


Hämtar eller anger en valfri array av 32-bit osignerade heltal som definierar längderna på streck och mellanrum i den linje som pennan ritar, när värdet av PenStyle är PS\_USERSTYLE linjestil för pennan. Arrayen innehåller ett antal poster som specificeras av NumStyleEntries, men den används som om den upprepades oändligt. Den första posten i arrayen specificerar längden på det första strecket. Den andra posten specificerar längden på det första mellanrummet. Därefter alternerar längderna på streck och mellanrum. Om penntypen i PenStyle‑fältet är PS\_GEOMETRIC anges längderna i logiska enheter; annars anges de i enheter för enheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### getBrushDibPattern() {#getBrushDibPattern--}
```
public WmfDeviceIndependentBitmap getBrushDibPattern()
```


Hämtar eller anger penselns dib‑mönster.

Värde: brush dib-mönstret.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBrushDibPattern(WmfDeviceIndependentBitmap value) {#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBrushDibPattern(WmfDeviceIndependentBitmap value)
```


Hämtar eller anger penselns dib‑mönster.

Värde: brush dib-mönstret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

