---
title: "EmfGlsBoundedRecord"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_GLSBOUNDEDRECORD-posten specificerar en OpenGL-funktion med en omgivande rektangel för utskrift."
type: docs
weight: 63
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfglsboundedrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsBoundedRecord extends EmfOpenGlRecordType
```

Den EMR_GLSBOUNDEDRECORD-posten specificerar en OpenGL-funktion med en avgränsande rektangel för utdata.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfGlsBoundedRecord(EmfRecord source)](#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfGlsBoundedRecord`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBounds()](#getBounds--) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar en omgivande rektangel, i enhetsenheter, för utskrift som produceras genom att köra OpenGL-funktionen. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar en omgivande rektangel, i enhetsenheter, för utskrift som produceras genom att köra OpenGL-funktionen. |
| [getCbData()](#getCbData--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, på Data-fältet. |
| [setCbData(int value)](#setCbData-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, på Data-fältet. |
| [getData()](#getData--) | Hämtar eller anger en valfri bytearray med längden cbData som specificerar data för OpenGL-funktionen. |
| [setData(byte[] value)](#setData-byte---) | Hämtar eller anger en valfri bytearray med längden cbData som specificerar data för OpenGL-funktionen. |
### EmfGlsBoundedRecord(EmfRecord source) {#EmfGlsBoundedRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsBoundedRecord(EmfRecord source)
```


Initierar en ny instans av klassen `EmfGlsBoundedRecord`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar en omgivande rektangel, i enhetsenheter, för utskrift som produceras genom att köra OpenGL-funktionen.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar en omgivande rektangel, i enhetsenheter, för utskrift som produceras genom att köra OpenGL-funktionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, på Data-fältet. Om detta värde är noll, bifogas ingen data till denna post.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, på Data-fältet. Om detta värde är noll, bifogas ingen data till denna post.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Hämtar eller anger en valfri bytearray med längden cbData som specificerar data för OpenGL-funktionen.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Hämtar eller anger en valfri bytearray med längden cbData som specificerar data för OpenGL-funktionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

