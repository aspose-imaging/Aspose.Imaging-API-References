---
title: "TiffDoubleType klass"
type: docs
weight: 40
url: /sv/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/
---

**Summary:** The tiff double type.

**Module:** [aspose.imaging.fileformats.tiff.tifftagtypes](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/)

**Full Name:** aspose.imaging.fileformats.tiff.tifftagtypes.TiffDoubleType

**Inheritance:** TiffCommonArrayType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffDoubleType(tag_id)](#TiffDoubleType_tag_id_1) | Initialiserar en ny instans av klassen [TiffDoubleType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/). |
| [TiffDoubleType(tag_id)](#TiffDoubleType_tag_id_2) | Initialiserar en ny instans av klassen [TiffDoubleType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r | Hämtar antalet element. |
| data_size | int | r | Hämtar storleken på taggvärdet. |
| element_size | System.Byte | r | Hämtar elementets storlek i byte. |
| id | int | r | Hämtar tagg‑id som nummer. |
| is_valid | bool | r | Hämtar ett värde som indikerar om taggdata är giltig. Den giltiga taggen innehåller data som kan bevaras. Den ogiltiga taggen kan inte lagras. |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | r | Hämtar tagg‑id. |
| tag_type | [TiffDataTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffdatatypes/) | r | Hämtar taggtypen. |
| värde | System.Object | r/w | Hämtar eller anger värdet som denna datatyp innehåller. |
| värden | float[] | r/w | Hämtar eller anger värdena. |
| values_container | System.Array | r | Hämtar värdebehållaren. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Jämför den aktuella instansen med ett annat objekt av samma typ och returnerar ett heltal som indikerar om den aktuella instansen föregår, följer eller hamnar på samma position i sorteringsordningen som det andra objektet. |
| [create_with_tag(tag_id)](#create_with_tag_tag_id_2) | Initialiserar en ny instans av klassen [TiffDoubleType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/). |
| [create_with_tag_id(tag_id)](#create_with_tag_id_tag_id_3) | Initialiserar en ny instans av klassen [TiffDoubleType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/). |
| [deep_clone()](#deep_clone__4) | Utför en djup kloning av denna instans. |
| [get_additional_data_size(size_of_tag_value)](#get_additional_data_size_size_of_tag_value_5) | Hämtar den extra taggvärdesstorleken i byte (om taggen inte kan rymma hela taggvärdet). |
| [get_aligned_data_size(size_of_tag_value)](#get_aligned_data_size_size_of_tag_value_6) | Hämtar datastorleken justerad till 4-byte (int) eller 8-byte (long) gräns. |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_7) | Läser taggdata. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_8) | Skriver den extra taggdata. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_9) | Skriver taggvärdet eller extra förskjutning. |


### Constructor: TiffDoubleType(tag_id) {#TiffDoubleType_tag_id_1}


```
 TiffDoubleType(tag_id) 
```

Initialiserar en ny instans av klassen [TiffDoubleType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Tagg‑id. |

### Constructor: TiffDoubleType(tag_id) {#TiffDoubleType_tag_id_2}


```
 TiffDoubleType(tag_id) 
```

Initialiserar en ny instans av klassen [TiffDoubleType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag_id | int | Tagg‑id. |

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


### Method: create_with_tag(tag_id)  [static] {#create_with_tag_tag_id_2}


```
 create_with_tag(tag_id) 
```

Initialiserar en ny instans av klassen [TiffDoubleType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Tagg‑id. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffDoubleType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/) |  |


### Method: create_with_tag_id(tag_id)  [static] {#create_with_tag_id_tag_id_3}


```
 create_with_tag_id(tag_id) 
```

Initialiserar en ny instans av klassen [TiffDoubleType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag_id | int | Tagg‑id. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffDoubleType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/) |  |


### Method: deep_clone() {#deep_clone__4}


```
 deep_clone() 
```

Utför en djup kloning av denna instans.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | En djup kloning av den aktuella instansen. |


### Method: get_additional_data_size(size_of_tag_value) {#get_additional_data_size_size_of_tag_value_5}


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


### Method: get_aligned_data_size(size_of_tag_value) {#get_aligned_data_size_size_of_tag_value_6}


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


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_7}


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


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_8}


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


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_9}


```
 write_tag(data_stream, additional_data_offset) 
```

Skriver taggvärdet eller extra förskjutning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Datastreamen. |
| additional_data_offset | int | Den extra dataförskjutningen. |

