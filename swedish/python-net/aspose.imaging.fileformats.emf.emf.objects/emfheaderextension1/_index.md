---
title: "EmfHeaderExtension1-klass"
type: docs
weight: 90
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---

**Summary:** The HeaderExtension1 object defines the first extension to the EMF metafile header. <br/>            It adds support for a PixelFormatDescriptor object (section 2.2.22) and OpenGL <br/>            [OPENGL] records (section 2.3.9).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1

**Inheritance:** EmfHeaderObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1__1) | Initierar en ny instans av klassen EmfHeaderExtension1 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| b_open_gl | int | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som indikerar om OpenGL‑kommandon finns i metafilen.<br/>            0x00000000 OpenGL‑poster finns inte i metafilen.<br/>            0x00000001 OpenGL‑poster finns i metafilen. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som specificerar de rektangulära inklusiva gränserna i enhetsenheter för den minsta rektangel som kan ritas runt bilden som lagras i <br/>            metafilen |
| byte | int | r/w | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar storleken på metafilen, i byte. |
| cb_pixel_format | int | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar storleken på PixelFormatDescriptor‑objektet. <br/>            Detta MÅSTE vara 0x00000000 om inget pixelformat är angivet |
| device | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Hämtar eller anger ett WMF SizeL-objekt ([MS-WMF] avsnitt 2.2.2.22) som specificerar storleken på referensenheten, i pixlar |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett WMF RectL-objekt som specificerar de rektangulära inklusiva dimensionerna, i .01 millimeter <br/>            enheter, för en rektangel som omger bilden som lagras i metafilen |
| handles | int | r/w | Hämtar eller anger ett 16‑bit osignerat heltal som specificerar antalet grafikobjekt som kommer att användas under bearbetning av metafilen |
| millimeters | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Hämtar eller anger ett WMF SizeL-objekt som specificerar storleken på referensenheten, i millimeter |
| n_desription | int | r/w | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar antalet tecken i arrayen <br/>            som innehåller beskrivningen av metafilens innehåll. Detta är noll om det inte finns någon beskrivningssträng. |
| n_pal_entries | int | r/w | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar antalet poster i metafilens <br/>            palett. Paletten finns i EMR_EOF-posten |
| off_description | int | r/w | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar förskjutningen från början av denna <br/>            post till arrayen som innehåller beskrivningen av metafilens innehåll |
| off_pixel_format | int | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar förskjutningen till PixelFormatDescriptor‑objektet.<br/>            Detta MÅSTE vara 0x00000000 om inget pixelformat är angivet. |
| record_signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar postens signatur. Detta MÅSTE vara ENHMETA_SIGNATURE, <br/>            från FormatSignature‑enumerationen (avsnitt 2.1.14). |
| poster | int | r/w | Hämtar eller anger ett 32‑bit osignerat heltal som specificerar antalet poster i metafilen |
| reserverad | int | r/w | Hämtar eller anger ett 16‑bit osignerat heltal som MÅSTE vara 0x0000 och som MÅSTE ignoreras |
| valid | bool | r | Hämtar ett värde som indikerar om detta [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) är giltigt. |
| version | int | r/w | Hämtar eller anger Version (4 byte): En 32-bitars osignerad heltal som specificerar EMF-metafilinteroperabilitet. Detta BÖR vara 0x00010000 |


### Constructor: EmfHeaderExtension1() {#EmfHeaderExtension1__1}


```
 EmfHeaderExtension1() 
```

Initierar en ny instans av klassen EmfHeaderExtension1

