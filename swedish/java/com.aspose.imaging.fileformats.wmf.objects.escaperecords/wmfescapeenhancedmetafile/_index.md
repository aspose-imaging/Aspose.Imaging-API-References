---
title: "WmfEscapeEnhancedMetafile"
second_title: "Aspose.Imaging för Java API-referens"
description: "Escape Enhanced Meta file-posten."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescapeenhancedmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.escaperecords.WmfEscapeRecordBase](../../com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescaperecordbase)
```
public class WmfEscapeEnhancedMetafile extends WmfEscapeRecordBase
```

Escape Enhanced Meta file-posten.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfEscapeEnhancedMetafile()](#WmfEscapeEnhancedMetafile--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Hämtar eller anger kommentarsidentifieraren. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Hämtar eller anger kommentarsidentifieraren. |
| [getCommentType()](#getCommentType--) | Hämtar eller anger kommentartypen. |
| [setCommentType(int value)](#setCommentType-int-) | Hämtar eller anger kommentartypen. |
| [getVersion()](#getVersion--) | Hämtar eller anger versionen. |
| [setVersion(int value)](#setVersion-int-) | Hämtar eller anger versionen. |
| [getChecksum()](#getChecksum--) | Hämtar eller anger kontrollsumman. |
| [setChecksum(int value)](#setChecksum-int-) | Hämtar eller anger kontrollsumman. |
| [getFlags()](#getFlags--) | Hämtar eller anger flaggorna. |
| [setFlags(int value)](#setFlags-int-) | Hämtar eller anger flaggorna. |
| [getCommentRecordCount()](#getCommentRecordCount--) | Hämtar eller anger antalet kommentarsposter. |
| [setCommentRecordCount(int value)](#setCommentRecordCount-int-) | Hämtar eller anger antalet kommentarsposter. |
| [getCurrentRecordSize()](#getCurrentRecordSize--) | Hämtar eller anger storleken på den aktuella posten. |
| [setCurrentRecordSize(int value)](#setCurrentRecordSize-int-) | Hämtar eller anger storleken på den aktuella posten. |
| [getRemainingBytes()](#getRemainingBytes--) | Hämtar eller anger de återstående byten. |
| [setRemainingBytes(int value)](#setRemainingBytes-int-) | Hämtar eller anger de återstående byten. |
| [getEnhancedMetafileDataSize()](#getEnhancedMetafileDataSize--) | Hämtar eller anger storleken på den förbättrade metafildatan. |
| [setEnhancedMetafileDataSize(int value)](#setEnhancedMetafileDataSize-int-) | Hämtar eller anger storleken på den förbättrade metafildatan. |
| [getEnhancedMetafileData()](#getEnhancedMetafileData--) | Hämtar eller anger den förbättrade metafildatan. |
| [setEnhancedMetafileData(byte[] value)](#setEnhancedMetafileData-byte---) | Hämtar eller anger den förbättrade metafildatan. |
### WmfEscapeEnhancedMetafile() {#WmfEscapeEnhancedMetafile--}
```
public WmfEscapeEnhancedMetafile()
```


### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Hämtar eller anger kommentarsidentifieraren.

Värde: Ett 32-bitars osignerat heltal som definierar denna post som en WMF-kommentarpost. Detta värde MÅSTE vara 0x43464D57.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Hämtar eller anger kommentarsidentifieraren.

Värde: Ett 32-bitars osignerat heltal som definierar denna post som en WMF-kommentarpost. Detta värde MÅSTE vara 0x43464D57.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCommentType() {#getCommentType--}
```
public int getCommentType()
```


Hämtar eller anger kommentartypen.

Värde: Ett 32-bitars osignerat heltal som identifierar kommentartypen i denna post. Detta värde MÅSTE vara 0x00000001.

**Returns:**
int
### setCommentType(int value) {#setCommentType-int-}
```
public void setCommentType(int value)
```


Hämtar eller anger kommentartypen.

Värde: Ett 32-bitars osignerat heltal som identifierar kommentartypen i denna post. Detta värde MÅSTE vara 0x00000001.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Hämtar eller anger versionen.

Värde: Ett 32-bitars osignerat heltal som specificerar EMF-metafilinteroperabilitet. Detta BÖR vara 0x00010000.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Hämtar eller anger versionen.

Värde: Ett 32-bitars osignerat heltal som specificerar EMF-metafilinteroperabilitet. Detta BÖR vara 0x00010000.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Hämtar eller anger kontrollsumman.

Värde: Ett 16-bitars osignerat heltal som används för att validera korrektheten i den inbäddade EMF-strömmen. Detta värde MÅSTE vara ettkomplementet av resultatet av en XOR‑operation på alla WORD i EMF‑strömmen.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Hämtar eller anger kontrollsumman.

Värde: Ett 16-bitars osignerat heltal som används för att validera korrektheten i den inbäddade EMF-strömmen. Detta värde MÅSTE vara ettkomplementet av resultatet av en XOR‑operation på alla WORD i EMF‑strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Hämtar eller anger flaggorna.

Värde: Detta 32-bitars osignerade heltal används inte och MÅSTE sättas till noll.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Hämtar eller anger flaggorna.

Värde: Detta 32-bitars osignerade heltal används inte och MÅSTE sättas till noll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCommentRecordCount() {#getCommentRecordCount--}
```
public int getCommentRecordCount()
```


Hämtar eller anger antalet kommentarsposter.

Värde: Ett 32-bitars osignerat heltal som specificerar det totala antalet på varandra följande META\_ESCAPE\_ENHANCED\_METAFILE‑poster som innehåller den inbäddade EMF-metafilen.

**Returns:**
int
### setCommentRecordCount(int value) {#setCommentRecordCount-int-}
```
public void setCommentRecordCount(int value)
```


Hämtar eller anger antalet kommentarsposter.

Värde: Ett 32-bitars osignerat heltal som specificerar det totala antalet på varandra följande META\_ESCAPE\_ENHANCED\_METAFILE‑poster som innehåller den inbäddade EMF-metafilen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCurrentRecordSize() {#getCurrentRecordSize--}
```
public int getCurrentRecordSize()
```


Hämtar eller anger storleken på den aktuella posten.

Värde: Ett 32-bitars osignerat heltal som specificerar storleken, i byte, på fältet EnhancedMetafileData. Detta värde MÅSTE vara mindre än eller lika med 8 192.

**Returns:**
int
### setCurrentRecordSize(int value) {#setCurrentRecordSize-int-}
```
public void setCurrentRecordSize(int value)
```


Hämtar eller anger storleken på den aktuella posten.

Värde: Ett 32-bitars osignerat heltal som specificerar storleken, i byte, på fältet EnhancedMetafileData. Detta värde MÅSTE vara mindre än eller lika med 8 192.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRemainingBytes() {#getRemainingBytes--}
```
public int getRemainingBytes()
```


Hämtar eller anger de återstående byten.

Värde: Ett 32-bitars osignerat heltal som specificerar antalet byte i EMF‑strömmen som återstår att bearbetas efter denna post. Dessa extra EMF‑byte MÅSTE följa i EnhancedMetafileData‑fälten för efterföljande META\_ESCAPE\_ENHANDED\_METAFILE‑escape‑poster.

**Returns:**
int
### setRemainingBytes(int value) {#setRemainingBytes-int-}
```
public void setRemainingBytes(int value)
```


Hämtar eller anger de återstående byten.

Värde: Ett 32-bitars osignerat heltal som specificerar antalet byte i EMF‑strömmen som återstår att bearbetas efter denna post. Dessa extra EMF‑byte MÅSTE följa i EnhancedMetafileData‑fälten för efterföljande META\_ESCAPE\_ENHANDED\_METAFILE‑escape‑poster.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getEnhancedMetafileDataSize() {#getEnhancedMetafileDataSize--}
```
public int getEnhancedMetafileDataSize()
```


Hämtar eller anger storleken på den förbättrade metafildatan.

Värde: Ett 32-bitars osignerat heltal som specificerar den totala storleken på EMF‑strömmen som är inbäddad i denna sekvens av META\_ESCAPE\_ENHANCED\_METAFILE‑poster.

**Returns:**
int
### setEnhancedMetafileDataSize(int value) {#setEnhancedMetafileDataSize-int-}
```
public void setEnhancedMetafileDataSize(int value)
```


Hämtar eller anger storleken på den förbättrade metafildatan.

Värde: Ett 32-bitars osignerat heltal som specificerar den totala storleken på EMF‑strömmen som är inbäddad i denna sekvens av META\_ESCAPE\_ENHANCED\_METAFILE‑poster.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getEnhancedMetafileData() {#getEnhancedMetafileData--}
```
public byte[] getEnhancedMetafileData()
```


Hämtar eller anger den förbättrade metafildatan.

Värde: Ett segment av en EMF‑fil. Byte i på varandra följande META\_ESCAPE\_ENHANCED\_METAFILE‑poster MÅSTE konkateneras för att representera hela den inbäddade EMF‑filen.

**Returns:**
byte[]
### setEnhancedMetafileData(byte[] value) {#setEnhancedMetafileData-byte---}
```
public void setEnhancedMetafileData(byte[] value)
```


Hämtar eller anger den förbättrade metafildatan.

Värde: Ett segment av en EMF‑fil. Byte i på varandra följande META\_ESCAPE\_ENHANCED\_METAFILE‑poster MÅSTE konkateneras för att representera hela den inbäddade EMF‑filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] |  |

