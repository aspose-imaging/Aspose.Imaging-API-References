---
title: "WmfBitmapInfoHeader"
second_title: "Aspose.Imaging för Java API-referens"
description: "BitmapInfoHeader-objektet innehåller information om dimensionerna och färgformatet för en enhetsoberoende bitmap DIB."
type: docs
weight: 16
url: /sv/java/com.aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfBitmapBaseHeader](../../com.aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader)
```
public class WmfBitmapInfoHeader extends WmfBitmapBaseHeader
```

BitmapInfoHeader-objektet innehåller information om dimensionerna och färgformatet för en enhetsoberoende bitmap (DIB).
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [WmfBitmapInfoHeader()](#WmfBitmapInfoHeader--) |  |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [STRUCTURE_SIZE](#STRUCTURE-SIZE) | Strukturens storlek |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWidth()](#getWidth--) | Hämtar eller anger ett 32-bitars signerat heltal som definierar bredden på DIB, i pixlar. |
| [setWidth(int value)](#setWidth-int-) | Hämtar eller anger ett 32-bitars signerat heltal som definierar bredden på DIB, i pixlar. |
| [getHeight()](#getHeight--) | Hämtar eller anger ett 32-bitars signerat heltal som definierar höjden på DIB, i pixlar. |
| [setHeight(int value)](#setHeight-int-) | Hämtar eller anger ett 32-bitars signerat heltal som definierar höjden på DIB, i pixlar. |
| [getCompression()](#getCompression--) | Hämtar eller anger ett 32-bitars osignerat heltal som definierar komprimeringsläget för DIB. |
| [setCompression(int value)](#setCompression-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som definierar komprimeringsläget för DIB. |
| [getImageSize()](#getImageSize--) | Hämtar eller anger ett 32-bitars osignerat heltal som definierar bildens storlek i byte. |
| [setImageSize(int value)](#setImageSize-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som definierar bildens storlek i byte. |
| [getXPelsPerMeter()](#getXPelsPerMeter--) | Hämtar eller anger ett 32-bitars signerat heltal som definierar den horisontella upplösningen, i pixlar per meter, för mål enheten för DIB. |
| [setXPelsPerMeter(int value)](#setXPelsPerMeter-int-) | Hämtar eller anger ett 32-bitars signerat heltal som definierar den horisontella upplösningen, i pixlar per meter, för mål enheten för DIB. |
| [getYPelsPerMeter()](#getYPelsPerMeter--) | Hämtar eller anger ett 32-bitars signerat heltal som definierar den vertikala upplösningen, i pixlar per meter, för mål enheten för DIB. |
| [setYPelsPerMeter(int value)](#setYPelsPerMeter-int-) | Hämtar eller anger ett 32-bitars signerat heltal som definierar den vertikala upplösningen, i pixlar per meter, för mål enheten för DIB. |
| [getColorUsed()](#getColorUsed--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet index i färgtabellen som används av DIB, enligt följande: Om detta värde är noll använder DIB det maximala antalet färger som motsvarar BitCount‑värdet. |
| [setColorUsed(int value)](#setColorUsed-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet index i färgtabellen som används av DIB, enligt följande: Om detta värde är noll använder DIB det maximala antalet färger som motsvarar BitCount‑värdet. |
| [getColorImportant()](#getColorImportant--) | Hämtar eller anger ett 32-bitars osignerat heltal som definierar antalet färgindex som krävs för att visa DIB. |
| [setColorImportant(int value)](#setColorImportant-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som definierar antalet färgindex som krävs för att visa DIB. |
### WmfBitmapInfoHeader() {#WmfBitmapInfoHeader--}
```
public WmfBitmapInfoHeader()
```


### STRUCTURE_SIZE {#STRUCTURE-SIZE}
```
public static final int STRUCTURE_SIZE
```


Strukturens storlek

### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar eller anger ett 32-bitars signerat heltal som definierar bredden på DIB, i pixlar. Detta värde MÅSTE vara positivt. Detta fält BÖR specificera bredden på den dekomprimerade bildfilen om komprimeringsvärdet anger JPEG‑ eller PNG‑format.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som definierar bredden på DIB, i pixlar. Detta värde MÅSTE vara positivt. Detta fält BÖR specificera bredden på den dekomprimerade bildfilen om komprimeringsvärdet anger JPEG‑ eller PNG‑format.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar eller anger ett 32-bitars signerat heltal som definierar höjden på DIB, i pixlar. Detta värde FÅR INTE vara noll. Om värdet är positivt är DIB en bottom‑up‑bitmap och dess ursprung är nedre vänstra hörnet. Om värdet är negativt är DIB en top‑down‑bitmap och dess ursprung är övre vänstra hörnet. Top‑down‑bitmaps stöder inte komprimering. Detta fält BÖR specificera höjden på den dekomprimerade bildfilen om komprimeringsvärdet anger JPEG‑ eller PNG‑format.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som definierar höjden på DIB, i pixlar. Detta värde FÅR INTE vara noll. Om värdet är positivt är DIB en bottom‑up‑bitmap och dess ursprung är nedre vänstra hörnet. Om värdet är negativt är DIB en top‑down‑bitmap och dess ursprung är övre vänstra hörnet. Top‑down‑bitmaps stöder inte komprimering. Detta fält BÖR specificera höjden på den dekomprimerade bildfilen om komprimeringsvärdet anger JPEG‑ eller PNG‑format.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


Hämtar eller anger ett 32-bitars osignerat heltal som definierar komprimeringsläget för DIB. Detta värde MÅSTE finnas i komprimeringsenumerationen (avsnitt 2.1.1.7). Detta värde FÅR INTE ange ett komprimerat format om DIB är en top‑down‑bitmap, enligt Height‑värdet.

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som definierar komprimeringsläget för DIB. Detta värde MÅSTE finnas i komprimeringsenumerationen (avsnitt 2.1.1.7). Detta värde FÅR INTE ange ett komprimerat format om DIB är en top‑down‑bitmap, enligt Height‑värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getImageSize() {#getImageSize--}
```
public int getImageSize()
```


Hämtar eller anger ett 32-bitars osignerat heltal som definierar bildens storlek i byte. Om komprimeringsvärdet är BI\_RGB bör detta värde vara noll och måste ignoreras. Om komprimeringsvärdet är BI\_JPEG eller BI\_PNG måste detta värde ange storleken på JPEG‑‑ eller PNG‑bildbufferten respektive.

**Returns:**
int
### setImageSize(int value) {#setImageSize-int-}
```
public void setImageSize(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som definierar bildens storlek i byte. Om komprimeringsvärdet är BI\_RGB bör detta värde vara noll och måste ignoreras. Om komprimeringsvärdet är BI\_JPEG eller BI\_PNG måste detta värde ange storleken på JPEG‑‑ eller PNG‑bildbufferten respektive.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getXPelsPerMeter() {#getXPelsPerMeter--}
```
public int getXPelsPerMeter()
```


Hämtar eller anger ett 32-bitars signerat heltal som definierar den horisontella upplösningen, i pixlar per meter, för mål enheten för DIB.

**Returns:**
int
### setXPelsPerMeter(int value) {#setXPelsPerMeter-int-}
```
public void setXPelsPerMeter(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som definierar den horisontella upplösningen, i pixlar per meter, för mål enheten för DIB.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getYPelsPerMeter() {#getYPelsPerMeter--}
```
public int getYPelsPerMeter()
```


Hämtar eller anger ett 32-bitars signerat heltal som definierar den vertikala upplösningen, i pixlar per meter, för mål enheten för DIB.

**Returns:**
int
### setYPelsPerMeter(int value) {#setYPelsPerMeter-int-}
```
public void setYPelsPerMeter(int value)
```


Hämtar eller anger ett 32-bitars signerat heltal som definierar den vertikala upplösningen, i pixlar per meter, för mål enheten för DIB.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getColorUsed() {#getColorUsed--}
```
public int getColorUsed()
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet index i färgtabellen som används av DIB, enligt följande: Om detta värde är noll använder DIB det maximala antalet färger som motsvarar BitCount‑värdet. Om värdet är skilt från noll och BitCount‑värdet är mindre än 16 specificerar värdet antalet färger som används av DIB. Om värdet är skilt från noll och BitCount‑värdet är 16 eller högre specificerar värdet storleken på färgtabellen som används för att optimera prestandan för systempaletten. Observera: Om värdet är skilt från noll och större än den maximalt möjliga storleken på färgtabellen baserat på BitCount‑värdet, bör den maximala färgtabellens storlek antas.

**Returns:**
int
### setColorUsed(int value) {#setColorUsed-int-}
```
public void setColorUsed(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet index i färgtabellen som används av DIB, enligt följande: Om detta värde är noll använder DIB det maximala antalet färger som motsvarar BitCount‑värdet. Om värdet är skilt från noll och BitCount‑värdet är mindre än 16 specificerar värdet antalet färger som används av DIB. Om värdet är skilt från noll och BitCount‑värdet är 16 eller högre specificerar värdet storleken på färgtabellen som används för att optimera prestandan för systempaletten. Observera: Om värdet är skilt från noll och större än den maximalt möjliga storleken på färgtabellen baserat på BitCount‑värdet, bör den maximala färgtabellens storlek antas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getColorImportant() {#getColorImportant--}
```
public int getColorImportant()
```


Hämtar eller anger ett 32-bitars osignerat heltal som definierar antalet färgindex som krävs för att visa DIB. Om detta värde är noll krävs alla färgindex.

**Returns:**
int
### setColorImportant(int value) {#setColorImportant-int-}
```
public void setColorImportant(int value)
```


Hämtar eller anger ett 32-bitars osignerat heltal som definierar antalet färgindex som krävs för att visa DIB. Om detta värde är noll krävs alla färgindex.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

