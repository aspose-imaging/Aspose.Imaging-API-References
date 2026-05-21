---
title: "EmfMetafileHeaderExtension1"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfMetafileHeaderExtension1-posten är huvudposten som används i den första utökningen av EMF-metafiler."
type: docs
weight: 71
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
```
public class EmfMetafileHeaderExtension1 extends EmfMetafileHeader
```

EmfMetafileHeaderExtension1-posten är huvudposten som används i den första utökningen av EMF-metafiler. Efter fältet EmfHeaderExtension1 är de återstående fälten valfria och kan förekomma i vilken ordning som helst.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfMetafileHeaderExtension1(EmfMetafileHeader header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Initierar en ny instans av klassen `EmfMetafileHeaderExtension1`. |
| [EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)](#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-) | Initierar en ny instans av klassen `EmfMetafileHeaderExtension1`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEmfHeaderExtension1()](#getEmfHeaderExtension1--) | Hämtar eller anger ett HeaderExtension1-objekt som specificerar ytterligare information om bilden i metafilen. |
| [setEmfHeaderExtension1(EmfHeaderExtension1 value)](#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-) | Hämtar eller anger ett HeaderExtension1-objekt som specificerar ytterligare information om bilden i metafilen. |
| [getEmfPixelFormatBuffer()](#getEmfPixelFormatBuffer--) | Hämtar eller anger en valfri bytearray som innehåller EMF-pixelformatbeskrivningen, vilken inte behöver vara sammanhängande med den fasta delen av EmfMetafileHeaderExtension1-posten eller med EMF‑beskrivningssträngen. |
| [setEmfPixelFormatBuffer(byte[] value)](#setEmfPixelFormatBuffer-byte---) | Hämtar eller anger en valfri bytearray som innehåller EMF-pixelformatbeskrivningen, vilken inte behöver vara sammanhängande med den fasta delen av EmfMetafileHeaderExtension1-posten eller med EMF‑beskrivningssträngen. |
### EmfMetafileHeaderExtension1(EmfMetafileHeader header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeader header)
```


Initierar en ny instans av klassen `EmfMetafileHeaderExtension1`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | Rubriken. |

### EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header) {#EmfMetafileHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeaderExtension1-}
```
public EmfMetafileHeaderExtension1(EmfMetafileHeaderExtension1 header)
```


Initierar en ny instans av klassen `EmfMetafileHeaderExtension1`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| header | [EmfMetafileHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheaderextension1) | Rubriken. |

### getEmfHeaderExtension1() {#getEmfHeaderExtension1--}
```
public EmfHeaderExtension1 getEmfHeaderExtension1()
```


Hämtar eller anger ett HeaderExtension1-objekt som specificerar ytterligare information om bilden i metafilen.

**Returns:**
[EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1)
### setEmfHeaderExtension1(EmfHeaderExtension1 value) {#setEmfHeaderExtension1-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1-}
```
public void setEmfHeaderExtension1(EmfHeaderExtension1 value)
```


Hämtar eller anger ett HeaderExtension1-objekt som specificerar ytterligare information om bilden i metafilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfHeaderExtension1](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1) |  |

### getEmfPixelFormatBuffer() {#getEmfPixelFormatBuffer--}
```
public byte[] getEmfPixelFormatBuffer()
```


Hämtar eller anger en valfri bytearray som innehåller EMF-pixelformatbeskrivningen, vilken inte behöver vara sammanhängande med den fasta delen av EmfMetafileHeaderExtension1-posten eller med EMF‑beskrivningssträngen. Följaktligen är fältet i denna buffer som är märkt "UndefinedSpace" valfritt och MÅSTE ignoreras.

**Returns:**
byte[]
### setEmfPixelFormatBuffer(byte[] value) {#setEmfPixelFormatBuffer-byte---}
```
public void setEmfPixelFormatBuffer(byte[] value)
```


Hämtar eller anger en valfri bytearray som innehåller EMF-pixelformatbeskrivningen, vilken inte behöver vara sammanhängande med den fasta delen av EmfMetafileHeaderExtension1-posten eller med EMF‑beskrivningssträngen. Följaktligen är fältet i denna buffer som är märkt "UndefinedSpace" valfritt och MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

