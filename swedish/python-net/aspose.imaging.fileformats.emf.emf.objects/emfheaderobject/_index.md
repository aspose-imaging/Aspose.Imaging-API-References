---
title: "EmfHeaderObject-klass"
type: docs
weight: 110
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/
---

**Summary:** The Header object defines the EMF metafile header. It specifies properties of the device on which the image in the metafile was created.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfHeaderObject()](#EmfHeaderObject__1) | Initierar en ny instans av klassen [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar de rektangulära inklusiva gränserna i enhetsenheter för den minsta rektangel som kan ritas runt bilden som lagras i <br/>            metafilen |
| byte | int | r/w | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar storleken på metafilen, i byte. |
| device | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Hämtar eller anger ett WMF SizeL-objekt ([MS-WMF] avsnitt 2.2.2.22) som specificerar storleken på referensenheten, i pixlar |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett WMF RectL-objekt som specificerar de rektangulära inklusiva dimensionerna, i .01 millimeter <br/>            enheter, för en rektangel som omger bilden som lagras i metafilen |
| handles | int | r/w | Hämtar eller anger ett 16‑bit osignerat heltal som specificerar antalet grafikobjekt som kommer att användas under bearbetning av metafilen |
| millimeters | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Hämtar eller anger ett WMF SizeL-objekt som specificerar storleken på referensenheten, i millimeter |
| n_desription | int | r/w | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar antalet tecken i arrayen <br/>            som innehåller beskrivningen av metafilens innehåll. Detta är noll om det inte finns någon beskrivningssträng. |
| n_pal_entries | int | r/w | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar antalet poster i metafilens <br/>            palett. Paletten finns i EMR_EOF-posten |
| off_description | int | r/w | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar förskjutningen från början av denna <br/>            post till arrayen som innehåller beskrivningen av metafilens innehåll |
| record_signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar postens signatur. Detta MÅSTE vara ENHMETA_SIGNATURE, <br/>            från FormatSignature‑enumerationen (avsnitt 2.1.14). |
| poster | int | r/w | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar antalet poster i metafilen |
| reserverad | int | r/w | Hämtar eller anger ett 16‑bit osignerat heltal som MÅSTE vara 0x0000 och som MÅSTE ignoreras |
| valid | bool | r | Hämtar ett värde som indikerar om detta [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) är giltigt. |
| version | int | r/w | Hämtar eller anger Version (4 byte): En 32-bitars osignerad heltal som specificerar EMF-metafilinteroperabilitet. Detta BÖR vara 0x00010000 |


### Constructor: EmfHeaderObject() {#EmfHeaderObject__1}


```
 EmfHeaderObject() 
```

Initierar en ny instans av klassen [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/)

