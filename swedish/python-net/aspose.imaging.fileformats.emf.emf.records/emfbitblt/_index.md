---
title: "EmfBitBlt‑klass"
type: docs
weight: 70
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/
---

**Summary:** The EMR_BITBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            rectangle, optionally in combination with a brush pattern, according to a specified raster operation.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfBitBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfBitBlt(source)](#EmfBitBlt_source_1) | Initierar en ny instans av klassen [EmfBitBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bit_blt_raster_operation | [WmfTernaryRasterOperation](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/) | r/w | Hämtar eller anger ett 32‑bitars osignerat heltal som specificerar raster‑operationskoden <br/>            . Denna kod definierar hur färgdata från källrektangeln ska kombineras med <br/>            färgdata från destinationsrektangeln och eventuellt ett penselmönster, för att uppnå den slutgiltiga färgen. |
| bk_src_argb_32_color | int | r/w | Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar<br/>            bakgrundsfärgen för källbitmapen. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar <br/>            destinationsbegränsningsrektangeln i enhetsenheter. |
| cx_dest | int | r/w | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar den logiska bredden på käll‑ och <br/>            destinationsrektanglarna. |
| cy_dest | int | r/w | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar den logiska höjden på käll‑ och <br/>            destinationsrektanglarna. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Hämtar eller anger en buffert som innehåller källbitmapen, vilken inte behöver vara <br/>            sammanhängande med den fasta delen av EMR_BITBLT-posten. Följaktligen är fält i denna buffert <br/>            som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i <br/>            färgtabellen i källbitmapens huvud ska tolkas. Detta värde MÅSTE finnas i DIBColors‑enumerationen (avsnitt 2.1.9). |
| x_dest | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra <br/>            hörnet av destinationsrektangeln. |
| x_src | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra <br/>            hörnet av källrektangeln. |
| xform_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Hämtar eller anger ett XForm-objekt (avsnitt 2.2.28) som specificerar en transform från världsrummet till sidrymd som ska tillämpas på källbitmapen. |
| y_dest | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra <br/>            hörnet av destinationsrektangeln. |
| y_src | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra <br/>            hörnet av källrektangeln. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfBitBlt(source) {#EmfBitBlt_source_1}


```
 EmfBitBlt(source) 
```

Initierar en ny instans av klassen [EmfBitBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfbitblt/).

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


