---
title: "EmfPlgBlt klass"
type: docs
weight: 750
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/
---

**Summary:** The EMR_PLGBLT record specifies a block transfer of pixels from a source bitmap to a destination <br/>            parallelogram, with the application of a color mask bitmap.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfPlgBlt

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlgBlt(source)](#EmfPlgBlt_source_1) | Initierar en ny instans av klassen [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| aptl_dest | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Hämtar eller anger en array med tre WMF PointL-objekt ([MS-WMF] avsnitt 2.2.2.15) som <br/>            specificerar tre hörn i ett parallellogram‑målområde för blocköverföringen.<br/>            Det övre vänstra hörnet av källrektangeln mappar till den första punkten i denna array, det <br/>            övre högra hörnet till den andra punkten, och det nedre vänstra hörnet till den tredje punkten. Det nedre högra hörnet av källrektangeln mappar till den implicita fjärde punkten i <br/>            parallellogrammet, som beräknas från de första tre punkterna (A, B och C) genom att behandla dem som <br/>            vektorer. <br/>            D = B + C A |
| bk_src_argb_32_color | int | r/w | Hämtar eller anger ett WMF ColorRef-objekt ([MS-WMF] avsnitt 2.2.2.8) som specificerar <br/>            bakgrundsfärgen för källbitmapen. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar den <br/>            avgränsande rektangeln, i enhetsenheter, för utdata till destinationen. |
| cx_src | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska bredden på källrektangeln. |
| cy_src | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska höjden på källrektangeln. |
| mask_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Hämtar eller anger en buffert som innehåller mask-bitmapen, vilken inte <br/>            krävs vara sammanhängande med den fasta delen av EMR_PLGBLT-posten eller med varandra. <br/>            Därför är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras. |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Hämtar eller anger en buffert som innehåller käll-bitmapen, vilken inte <br/>            krävs vara sammanhängande med den fasta delen av EMR_PLGBLT-posten eller med varandra. <br/>            Därför är fält i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
| usage_mask | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i <br/>            färgtabellen i mask-bitmapens header ska tolkas. Detta värde MÅSTE vara i DIBColors‑enumerationen. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i <br/>            färgtabellen i käll-bitmapens huvud ska tolkas. Detta värde MÅSTE finnas i DIBColors‑enumerationen |
| x_form_src | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Hämtar eller anger ett XForm-objekt (avsnitt 2.2.28) som specificerar en transform från världsrummet till sidrymd som ska tillämpas på källbitmapen. |
| x_mask | int | r/w | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar den logiska x‑koordinaten för maskens bitmap‑övre vänstra hörn. |
| x_src | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra <br/>            hörnet av källrektangeln. |
| y_mask | int | r/w | Hämtar eller anger ett 32‑bitars signerat heltal som specificerar den logiska y‑koordinaten för maskens bitmap‑övre vänstra hörn. |
| y_src | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra <br/>            hörnet av källrektangeln. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfPlgBlt(source) {#EmfPlgBlt_source_1}


```
 EmfPlgBlt(source) 
```

Initierar en ny instans av klassen [EmfPlgBlt](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfplgblt/).

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


