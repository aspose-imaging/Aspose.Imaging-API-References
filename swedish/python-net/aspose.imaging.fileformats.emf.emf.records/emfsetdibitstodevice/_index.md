---
title: "EmfSetDiBitsToDevice-klass"
type: docs
weight: 1150
url: /sv/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/
---

**Summary:** The EMR_SETDIBITSTODEVICE record specifies a block transfer of pixels from specified scan lines of <br/>            a source bitmap to a destination rectangle.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetDiBitsToDevice

**Inheritance:** EmfBitmapRecordType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfSetDiBitsToDevice(source)](#EmfSetDiBitsToDevice_source_1) | Initierar en ny instans av klassen [EmfSetDiBitsToDevice](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Hämtar eller anger ett WMF RectL-objekt ([MS-WMF] avsnitt 2.2.2.19) som definierar <br/>            destinationsbegränsningsrektangeln i enhetsenheter. |
| c_scans | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar antalet skanningsrader. |
| cx_src | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar bredden i pixlar för källrektangeln. |
| cy_src | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar höjden i pixlar för källrektangeln |
| storlek | int | r/w | Hämtar eller anger storleken på posten |
| source_bitmap | [WmfDeviceIndependentBitmap](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap/) | r/w | Hämtar eller anger en buffert som innehåller källbitmappen, vilken inte behöver vara <br/>            sammanhängande med den fasta delen av EMR_SETDIBITSTODEVICE-posten. Följaktligen är fält <br/>            i denna buffert som är märkta "UndefinedSpace" valfria och MÅSTE ignoreras. |
| start_scan | int | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar den första skanningsraden i arrayen. |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | Hämtar eller anger typen. |
| usage_src | [EmfDibColors](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/) | r/w | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar hur värden i <br/>            färgtabellen i källbitmapens huvud ska tolkas. Detta värde MÅSTE finnas i DIBColors‑enumerationen (avsnitt 2.1.9). |
| x_dest | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska x-koordinaten för det övre vänstra <br/>            hörnet av destinationsrektangeln. |
| x_src | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar x-koordinaten i pixlar för den nedre vänstra <br/>            hörnet av källrektangeln. |
| y_dest | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar den logiska y-koordinaten för det övre vänstra <br/>            hörnet av destinationsrektangeln. |
| y_src | int | r/w | Hämtar eller anger ett 32-bitars signerat heltal som specificerar y-koordinaten i pixlar för den nedre vänstra <br/>            hörnet av källrektangeln. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |
| [create_from_type(type)](#create_from_type_type_2) | Initierar en ny instans av klassen [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/). |


### Constructor: EmfSetDiBitsToDevice(source) {#EmfSetDiBitsToDevice_source_1}


```
 EmfSetDiBitsToDevice(source) 
```

Initierar en ny instans av klassen [EmfSetDiBitsToDevice](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetdibitstodevice/).

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


