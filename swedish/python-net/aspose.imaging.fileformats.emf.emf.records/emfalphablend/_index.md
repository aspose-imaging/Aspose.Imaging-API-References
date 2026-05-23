---
title: "EmfAlphaBlend Klass"
type: docs
weight: 20
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/
---

**Summary:** The EMR_ALPHABLEND record specifies a block transfer of pixels from a source bitmap to a <br/>            destination rectangle, including alpha transparency data, according to a specified blending operation.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfAlphaBlend

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfAlphaBlend(source)](#EmfAlphaBlend_source_1) | Initierar en ny instans av klassen [EmfAlphaBlend](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bk_src_argb_32_color | int | r/w | Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar<br/>            bakgrundsfärgen för källbitmapen. |
| blend_function | [EmfBlendFunction](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction/) | r/w | Hämtar eller anger en struktur som specificerar blandningsoperationerna för käll- och <br/>            destinationsbitmapar. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar <br/>            destinationsbegränsningsrektangeln i enhetsenheter. |
| cx_dest | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på destinationsrektangeln <br/>            . Detta värde MÅSTE vara större än noll. |
| cx_src | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på källrektangeln. <br/>            Detta värde MÅSTE vara större än noll. |
| cy_dest | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på destinationsrektangeln <br/>            . Detta värde MÅSTE vara större än noll. |
| cy_src | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på källrektangeln <br/>            . Detta värde MÅSTE vara större än noll. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Hämtar eller anger en buffert som innehåller källbitmapen, vilken inte behöver vara <br/>            sammanhängande med den fasta delen av EMR_ALPHABLEND‑posten. Följaktligen är fält i denna <br/>            buffert som är märkta \"UndefinedSpace\" valfria och MÅSTE ignoreras. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i <br/>            färgtabellen i källbitmapens huvud ska tolkas. Detta värde MÅSTE finnas i DIBColors‑enumerationen (avsnitt 2.1.9). |
| x_dest | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra <br/>            hörnet av destinationsrektangeln. |
| x_src | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra <br/>            hörnet av källrektangeln. |
| xform_sr | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Hämtar eller anger ett XForm-objekt (avsnitt 2.2.28) som specificerar en transform från världsrummet till sidrymd som ska tillämpas på källbitmapen. |
| y_dest | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra <br/>            hörnet av destinationsrektangeln. |
| y_src | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra <br/>            hörnet av källrektangeln. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfAlphaBlend(source) {#EmfAlphaBlend_source_1}


```
 EmfAlphaBlend(source) 
```

Initierar en ny instans av klassen [EmfAlphaBlend](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfalphablend/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Källan. |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | Källan. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | Posttypen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


