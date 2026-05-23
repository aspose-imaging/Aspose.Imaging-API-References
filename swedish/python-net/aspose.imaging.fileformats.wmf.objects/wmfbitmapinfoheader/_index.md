---
title: "WmfBitmapInfoHeader klass"
type: docs
weight: 70
url: /sv/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---

**Summary:** The BitmapInfoHeader Object contains information about the dimensions and color format of a device-independent<br/>                bitmap (DIB).

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfBitmapInfoHeader

**Inheritance:** WmfBitmapBaseHeader

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfBitmapInfoHeader()](#WmfBitmapInfoHeader__1) | Initierar en ny instans av WmfBitmapInfoHeader‑klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| STRUCTURE_SIZE [statisk] | int | r | Strukturens storlek |
| bit_count | [DibBitCount](/imaging/python-net/aspose.imaging.apsbuilder.dib/dibbitcount/) | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som definierar formatet för<br/>                varje pixel samt det maximala antalet färger i DIB. Detta värde<br/>                MÅSTE vara i [WmfBitmapBaseHeader.bit_count](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/)-enumerationen (avsnitt 2.1.1.3). |
| color_important | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som definierar antalet färgindex som krävs för att visa<br/>                DIB.<br/>                Om detta värde är noll krävs alla färgindex |
| color_used | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet index i färgtabellen som används av DIB, enligt<br/>                följande:<br/>                Om detta värde är noll använder DIB det maximala antalet färger som motsvarar BitCount‑värdet.<br/>                Om detta värde är icke‑noll och BitCount‑värdet är mindre än 16, specificerar detta värde antalet färger som används av<br/>                DIB.<br/>                Om detta värde är icke‑noll och BitCount‑värdet är 16 eller högre, specificerar detta värde storleken på färgtabellen<br/>                som används för att optimera prestandan för systempaletten.<br/>                OBS! Om detta värde är icke‑noll och större än den maximala möjliga storleken på färgtabellen baserat på BitCount‑värdet,<br/>                bör den maximala färgtabellens storlek antas. |
| compression | [WmfCompression](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfcompression/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som definierar komprimeringsläget för DIB. Detta värde MÅSTE finnas i<br/>                komprimeringsenumerationen (avsnitt 2.1.1.7).<br/>                Detta värde FÅR INTE ange ett komprimerat format om DIB är en top‑down‑bitmap, enligt Height‑värdet. |
| header_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som definierar storleken på detta<br/>                objekt, i byte. |
| height | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som definierar DIB:s höjd i pixlar. Detta värde FÅR INTE vara noll.<br/>                Om detta värde är positivt är DIB en bottom‑up‑bitmap och dess ursprung är det nedre vänstra hörnet.<br/>                Om detta värde är negativt är DIB en top‑down‑bitmap och dess ursprung är det övre vänstra hörnet. Top‑down‑bitmapar<br/>                stöder inte komprimering.<br/>                Detta fält BÖR specificera höjden på den dekomprimerade bildfilen om komprimeringsvärdet anger JPEG‑ eller PNG‑format. |
| image_size | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som definierar bildens storlek i byte.<br/>                Om komprimeringsvärdet är BI_RGB bör detta värde vara noll och MÅSTE ignoreras.<br/>                Om komprimeringsvärdet är BI_JPEG eller BI_PNG, MÅSTE detta värde ange storleken på JPEG‑ respektive PNG‑bildbufferten,<br/>                respektive. |
| planes | int | r/w | Hämtar eller anger ett 16-bitars osignerat heltal som definierar antalet<br/>                [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/) för mål enheten. Detta värde MÅSTE vara<br/>                0x0001. |
| width | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som definierar DIB:s bredd i pixlar. Detta värde MÅSTE vara positivt.<br/>                Detta fält BÖR specificera bredden på den dekomprimerade bildfilen om komprimeringsvärdet anger JPEG‑ eller PNG‑format. |
| x_pels_per_meter | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som definierar den horisontella upplösningen, i pixlar-per-meter, för mål‑<br/>                enheten för DIB |
| y_pels_per_meter | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som definierar den vertikala upplösningen, i pixlar-per-meter, för mål‑<br/>                enheten för DIB |


### Constructor: WmfBitmapInfoHeader() {#WmfBitmapInfoHeader__1}


```
 WmfBitmapInfoHeader() 
```

Initierar en ny instans av WmfBitmapInfoHeader‑klassen

