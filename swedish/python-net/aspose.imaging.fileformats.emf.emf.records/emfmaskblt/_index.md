---
title: "EmfMaskBlt-klass"
type: docs
weight: 600
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/
---

**Summary:** The EMR_MASKBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            rectangle, optionally in combination with a brush pattern and with the application of a color mask <br/>            bitmap, according to specified foreground and background raster operations.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfMaskBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfMaskBlt(source)](#EmfMaskBlt_source_1) | Initierar en ny instans av klassen [EmfMaskBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_bk_color_src | int | r/w | Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8 som specificerar <br/>            bakgrundsfärgen för källbitmapen. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar <br/>            destinationsbegränsningsrektangeln i enhetsenheter. |
| cx_dest | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på destinationsrektangeln. |
| cy_dest | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på destinationsrektangeln. |
| mask_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Hämtar eller anger en buffert som innehåller mask-bitmapar, vilka inte <br/>            behöva vara sammanhängande med den fasta delen av EMR_MASKBLT-posten eller med varandra <br/>            . Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och <br/>            MÅSTE ignoreras. |
| rop4 | [EmfRop4](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrop4/) | r/w | Hämtar eller anger en kvartär rasteroperation, som specificerar ternära rasteroperationer för <br/>            förgrunds- och bakgrundsfärgerna i en bitmap. Dessa värden definierar hur färgdata från <br/>            källrektangeln ska kombineras med färgdata från destinationsrektangeln. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Hämtar eller anger en buffert som innehåller käll-bitmapar, vilka inte <br/>            behöva vara sammanhängande med den fasta delen av EMR_MASKBLT-posten eller med varandra <br/>            . Följaktligen är fält i denna buffert som är märkta "UndefinedSpace" valfria och <br/>            MÅSTE ignoreras. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
| usage_mask | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i <br/>            färgtabellen i mask-bitmapens header ska tolkas. Detta värde MÅSTE vara i DIBColors‑enumerationen. |
| usage_src | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i <br/>            färgtabellen i källbitmapens huvud ska tolkas. Detta värde MÅSTE finnas i DIBColors‑enumerationen (avsnitt 2.1.9). |
| x_dest | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra <br/>            hörnet av destinationsrektangeln. |
| x_mask | int | r/w | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar den logiska x‑koordinaten för maskens bitmap‑övre vänstra hörn. |
| x_src | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra <br/>            hörnet av källrektangeln. |
| xform_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Hämtar eller anger ett XForm-objekt (avsnitt 2.2.28) som specificerar en transform från världsrummet till sidrymd som ska tillämpas på källbitmapen. |
| y_dest | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra <br/>            hörnet av destinationsrektangeln. |
| y_mask | int | r/w | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar den logiska y‑koordinaten för maskens bitmap‑övre vänstra hörn. |
| y_src | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra <br/>            hörnet av källrektangeln. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfMaskBlt(source) {#EmfMaskBlt_source_1}


```
 EmfMaskBlt(source) 
```

Initierar en ny instans av klassen [EmfMaskBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmaskblt/).

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


