---
title: "EmfMetafileHeader"
second_title: "Aspose.Imaging för Java API-referens"
description: "EMR_HEADER-posterna definierar startpunkterna för EMF-metafiler och specificerar egenskaperna för den enhet på vilken bilden i metafilen skapades."
type: docs
weight: 70
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public class EmfMetafileHeader extends EmfRecord
```

EMR\_HEADER-posterna definierar startpunkterna för EMF-metafiler och specificerar egenskaperna för den enhet på vilken bilden i metafilen skapades. Informationen i header-posten gör det möjligt för EMF-metafiler att vara oberoende av någon specifik utskriftsenhet. Värdet i Size-fältet kan användas för att särskilja mellan de olika EMR\_HEADER-posterna som listas tidigare i detta avsnitt. Det finns tre möjliga headers: Basheadern, som är EmfMetafileHeader-posten. Den faststorlekdel av denna header är 88 byte och den innehåller ett Header-objekt. Den första extensionsheadern, som är EmfMetafileHeaderExtension1-posten. Den faststorlekdel av denna header är 100 byte och den innehåller ett Header-objekt och ett HeaderExtension1-objekt (avsnitt 2.2.10). Den andra extensionsheadern, som är EmfMetafileHeaderExtension2-posten. Den faststorlekdel av denna header är 108 byte och den innehåller ett Header-objekt, ett HeaderExtension1-objekt och ett HeaderExtension2-objekt (avsnitt 2.2.11).
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfMetafileHeader(EmfRecord record)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfMetafileHeader`. |
| [EmfMetafileHeader()](#EmfMetafileHeader--) | Initierar en ny instans av klassen `EmfMetafileHeader`. |
| [EmfMetafileHeader(EmfMetafileHeader header)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Initierar en ny instans av klassen `EmfMetafileHeader`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEmfHeader()](#getEmfHeader--) | Hämtar ett Header-objekt (avsnitt 2.2.9), som innehåller information om innehållet och strukturen i metafilen |
| [setEmfHeader(EmfHeaderObject value)](#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-) | Ställer in ett Header-objekt (avsnitt 2.2.9), som innehåller information om innehållet och strukturen i metafilen |
| [getEmfHeaderRecordBuffer()](#getEmfHeaderRecordBuffer--) | Hämtar en valfri bytearray som innehåller resten av EMF-headerposten. |
| [setEmfHeaderRecordBuffer(byte[] value)](#setEmfHeaderRecordBuffer-byte---) | Ställer in en valfri bytearray som innehåller resten av EMF-headerposten. |
| [getEmfDescriptionBuffer()](#getEmfDescriptionBuffer--) | Hämtar EMF-beskrivningsbufferten En valfri bytearray som innehåller EMF-beskrivningssträngen, som inte behöver vara sammanhängande med den fasta delen av EmfMetafileHeader-posten. |
| [setEmfDescriptionBuffer(byte[] value)](#setEmfDescriptionBuffer-byte---) | Ställer in EMF-beskrivningsbufferten En valfri bytearray som innehåller EMF-beskrivningssträngen, som inte behöver vara sammanhängande med den fasta delen av EmfMetafileHeader-posten. |
| [getEmfDescription()](#getEmfDescription--) | Hämtar EMF-beskrivningen En valfri, nullterminerad Unicode UTF16-LE-sträng med godtycklig längd och innehåll. |
| [setEmfDescription(String value)](#setEmfDescription-java.lang.String-) | Ställer in EMF-beskrivningen En valfri, nullterminerad Unicode UTF16-LE-sträng med godtycklig längd och innehåll. |
### EmfMetafileHeader(EmfRecord record) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMetafileHeader(EmfRecord record)
```


Initierar en ny instans av klassen `EmfMetafileHeader`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Posten. |

### EmfMetafileHeader() {#EmfMetafileHeader--}
```
public EmfMetafileHeader()
```


Initierar en ny instans av klassen `EmfMetafileHeader`.

### EmfMetafileHeader(EmfMetafileHeader header) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeader(EmfMetafileHeader header)
```


Initierar en ny instans av klassen `EmfMetafileHeader`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | Rubriken. |

### getEmfHeader() {#getEmfHeader--}
```
public EmfHeaderObject getEmfHeader()
```


Hämtar ett Header-objekt (avsnitt 2.2.9), som innehåller information om innehållet och strukturen i metafilen

**Returns:**
[EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
### setEmfHeader(EmfHeaderObject value) {#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-}
```
public void setEmfHeader(EmfHeaderObject value)
```


Ställer in ett Header-objekt (avsnitt 2.2.9), som innehåller information om innehållet och strukturen i metafilen

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject) |  |

### getEmfHeaderRecordBuffer() {#getEmfHeaderRecordBuffer--}
```
public byte[] getEmfHeaderRecordBuffer()
```


Hämtar en valfri bytearray som innehåller resten av EMF-headerposten. Storleken på detta fält MÅSTE vara en multipel av 4 byte.

**Returns:**
byte[]
### setEmfHeaderRecordBuffer(byte[] value) {#setEmfHeaderRecordBuffer-byte---}
```
public void setEmfHeaderRecordBuffer(byte[] value)
```


Ställer in en valfri bytearray som innehåller resten av EMF-headerposten. Storleken på detta fält MÅSTE vara en multipel av 4 byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getEmfDescriptionBuffer() {#getEmfDescriptionBuffer--}
```
public byte[] getEmfDescriptionBuffer()
```


Hämtar EMF-beskrivningsbufferten En valfri bytearray som innehåller EMF-beskrivningssträngen, som inte behöver vara sammanhängande med den fasta delen av EmfMetafileHeader-posten. Följaktligen är fältet i denna buffer som är märkt "UndefinedSpace" valfritt och MÅSTE ignoreras.

**Returns:**
byte[]
### setEmfDescriptionBuffer(byte[] value) {#setEmfDescriptionBuffer-byte---}
```
public void setEmfDescriptionBuffer(byte[] value)
```


Ställer in EMF-beskrivningsbufferten En valfri bytearray som innehåller EMF-beskrivningssträngen, som inte behöver vara sammanhängande med den fasta delen av EmfMetafileHeader-posten. Följaktligen är fältet i denna buffer som är märkt "UndefinedSpace" valfritt och MÅSTE ignoreras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

### getEmfDescription() {#getEmfDescription--}
```
public String getEmfDescription()
```


Hämtar EMF-beskrivningen En valfri, nullterminerad Unicode UTF16-LE-sträng med godtycklig längd och innehåll. Dess placering i posten och antalet tecken specificeras av fälten offDescription respektive nDescription i EmfHeader. Om värdet för något av fälten är noll finns ingen beskrivningssträng.

**Returns:**
java.lang.String
### setEmfDescription(String value) {#setEmfDescription-java.lang.String-}
```
public void setEmfDescription(String value)
```


Ställer in EMF-beskrivningen En valfri, nullterminerad Unicode UTF16-LE-sträng med godtycklig längd och innehåll. Dess placering i posten och antalet tecken specificeras av fälten offDescription respektive nDescription i EmfHeader. Om värdet för något av fälten är noll finns ingen beskrivningssträng.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

