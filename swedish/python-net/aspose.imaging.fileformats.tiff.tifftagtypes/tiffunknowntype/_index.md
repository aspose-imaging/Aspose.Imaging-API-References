---
title: "TiffUnknownType klass"
type: docs
weight: 180
url: /sv/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---

**Summary:** The unknown tiff type. In case the tiff tag cannot be recognized this type is instantinated.

**Module:** [aspose.imaging.fileformats.tiff.tifftagtypes](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/)

**Full Name:** aspose.imaging.fileformats.tiff.tifftagtypes.TiffUnknownType

**Inheritance:** TiffDataType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffUnknownType(stream, tag_type, tag_id, count, offset_or_value)](#TiffUnknownType_stream_tag_type_tag_id_count_offset_or_value_1) | Initierar en ny instans av [TiffUnknownType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r | Hämtar antalet element. |
| data_size | int | r | Hämtar storleken på taggvärdet. |
| element_size | System.Byte | r | Hämtar elementets storlek i byte. |
| id | int | r | Hämtar tagg‑id som nummer. |
| is_valid | bool | r | Hämtar ett värde som indikerar om taggdata är giltig. Den giltiga taggen innehåller data som kan bevaras. Den ogiltiga taggen kan inte lagras. |
| offset_or_value | int | r | Hämtar offsetvärdet för ytterligare data eller värdet självt om antalet är 1. |
| stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | r | Hämtar strömmen för att läsa ytterligare data från. |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | r | Hämtar tagg‑id. |
| tag_type | [TiffDataTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffdatatypes/) | r | Hämtar taggtypen. |
| värde | System.Object | r/w | Hämtar eller anger värdet som denna datatyp innehåller. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Jämför den aktuella instansen med ett annat objekt av samma typ och returnerar ett heltal som indikerar om den aktuella instansen föregår, följer eller hamnar på samma position i sorteringsordningen som det andra objektet. |
| [deep_clone()](#deep_clone__2) | Utför en djup kloning av denna instans. |
| [get_additional_data_size(size_of_tag_value)](#get_additional_data_size_size_of_tag_value_3) | Hämtar den extra taggvärdesstorleken i byte (om taggen inte kan rymma hela taggvärdet). |
| [get_aligned_data_size(size_of_tag_value)](#get_aligned_data_size_size_of_tag_value_4) | Hämtar datastorleken justerad till 4-byte (int) eller 8-byte (long) gräns. |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_5) | Läser taggdata. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_6) | Skriver den extra taggdata. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_7) | Skriver taggvärdet eller extra förskjutning. |


### Constructor: TiffUnknownType(stream, tag_type, tag_id, count, offset_or_value) {#TiffUnknownType_stream_tag_type_tag_id_count_offset_or_value_1}


```
 TiffUnknownType(stream, tag_type, tag_id, count, offset_or_value) 
```

Initierar en ny instans av [TiffUnknownType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | Strömmen att läsa från. |
| tag_type | int | Typ av taggen. |
| tag_id | int | Tagg‑id. |
| count | int | Antalvärdet. |
| offset_or_value | int | Offset eller värde. |

### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

Jämför den aktuella instansen med ett annat objekt av samma typ och returnerar ett heltal som indikerar om den aktuella instansen föregår, följer eller hamnar på samma position i sorteringsordningen som det andra objektet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| obj | System.Object | Ett objekt att jämföra med denna instans. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Ett 32-bitars signerat heltal som indikerar den relativa ordningen för de objekt som jämförs. Returvärdet har dessa betydelser:<br/>            Värde<br/>            Betydelse<br/>            Mindre än noll<br/>            Denna instans är mindre än _obj_.<br/>            Noll<br/>            Denna instans är lika med _obj_.<br/>            Större än noll<br/>            Denna instans är större än _obj_. |


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

Utför en djup kloning av denna instans.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | En djup kloning av den aktuella instansen. |


### Method: get_additional_data_size(size_of_tag_value) {#get_additional_data_size_size_of_tag_value_3}


```
 get_additional_data_size(size_of_tag_value) 
```

Hämtar den extra taggvärdesstorleken i byte (om taggen inte kan rymma hela taggvärdet).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size_of_tag_value | System.Byte | Storlek på taggvärde: 4 eller 8 för BigTiff. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Den extra datastorleken i byte. |


### Method: get_aligned_data_size(size_of_tag_value) {#get_aligned_data_size_size_of_tag_value_4}


```
 get_aligned_data_size(size_of_tag_value) 
```

Hämtar datastorleken justerad till 4-byte (int) eller 8-byte (long) gräns.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| size_of_tag_value | System.Byte | Storlek på taggvärde. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Den justerade datastorleken i byte. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_5}


```
 read_tag(data_stream, position) 
```

Läser taggdata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | Datastreamen. |
| position | int | Taggpositionen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Den lästa taggen. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_6}


```
 write_additional_data(data_stream) 
```

Skriver den extra taggdata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Datastreamen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | De faktiska skrivna byten. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_7}


```
 write_tag(data_stream, additional_data_offset) 
```

Skriver taggvärdet eller extra förskjutning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Datastreamen. |
| additional_data_offset | int | Den extra dataförskjutningen. |

