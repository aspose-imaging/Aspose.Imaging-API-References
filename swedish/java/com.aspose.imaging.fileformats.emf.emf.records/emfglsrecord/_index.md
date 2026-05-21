---
title: "EmfGlsRecord"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_GLSRECORD-posten specificerar en OpenGL-funktion."
type: docs
weight: 64
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfglsrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsRecord extends EmfOpenGlRecordType
```

Den EMR_GLSRECORD-posten specificerar en OpenGL-funktion.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfGlsRecord(EmfRecord source)](#EmfGlsRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfGlsRecord`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCbData()](#getCbData--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, på Data-fältet. |
| [setCbData(int value)](#setCbData-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken, i byte, på Data-fältet. |
| [getData()](#getData--) | Hämtar eller anger en valfri bytearray med längden cbData som specificerar data för OpenGL-funktionen. |
| [setData(byte[] value)](#setData-byte---) | Hämtar eller anger en valfri bytearray med längden cbData som specificerar data för OpenGL-funktionen. |
### EmfGlsRecord(EmfRecord source) {#EmfGlsRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsRecord(EmfRecord source)
```


Initierar en ny instans av klassen `EmfGlsRecord`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

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

