---
title: "EmfFormat-klass"
type: docs
weight: 60
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.objects/emfformat/
---

**Summary:** The EmrFormat object contains information that identifies the format of image data in an<br/>            EMR_COMMENT_MULTIFORMATS record(section 2.3.3.4.3).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfFormat

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfFormat()](#EmfFormat__1) | Initierar en ny instans av klassen EmfFormat |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| off_data | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar förskjutningen till data från <br/>            början av identifierarfältet i en EMR_COMMENT_PUBLIC-post (avsnitt 2.3.3.4). <br/>            Förskjutningen MÅSTE vara 32-bitars justerad. |
| signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar formatet för bilddata. <br/>            Detta värde MÅSTE finnas i FormatSignature‑enumerationen (avsnitt 2.1.14). |
| size_data | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar storleken på data i byte |
| version | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar formatversionsnumret. <br/>            Om Signature‑fältet specificerar inbäddad PostScript (EPS), <br/>            måste detta värde vara 0x00000001; annars måste detta värde ignoreras. |


### Constructor: EmfFormat() {#EmfFormat__1}


```
 EmfFormat() 
```

Initierar en ny instans av klassen EmfFormat

