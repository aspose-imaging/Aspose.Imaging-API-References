---
title: "TiffRationalType Klasse"
type: docs
weight: 100
url: /de/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/
---

**Summary:** The tiff rational type.

**Module:** [aspose.imaging.fileformats.tiff.tifftagtypes](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/)

**Full Name:** aspose.imaging.fileformats.tiff.tifftagtypes.TiffRationalType

**Inheritance:** TiffCommonArrayType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [TiffRationalType(tag_id)](#TiffRationalType_tag_id_1) | Initialisiert eine neue Instanz der [TiffRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/) Klasse. |
| [TiffRationalType(tag_id)](#TiffRationalType_tag_id_2) | Initialisiert eine neue Instanz der [TiffRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| count | int | r | Ermittelt die Anzahl der Elemente. |
| data_size | int | r | Ermittelt die Größe des Tag-Werts. |
| element_size | System.Byte | r | Ermittelt die Elementgröße in Bytes. |
| id | int | r | Ermittelt die Tag-ID als Zahl. |
| is_valid | bool | r | Ermittelt einen Wert, der angibt, ob Tag-Daten gültig sind. Der gültige Tag enthält Daten, die ggf. erhalten bleiben können. Der ungültige Tag kann nicht gespeichert werden. |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | r | Ermittelt die Tag-ID. |
| tag_type | [TiffDataTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffdatatypes/) | r | Ermittelt den Tag-Typ. |
| Wert | System.Object | r/w | Ermittelt oder setzt den Wert, den dieser Datentyp enthält. |
| values | [TiffRational[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffrational/) | r/w | Ermittelt oder setzt die Werte. |
| values_container | System.Array | r | Ermittelt den Werte-Container. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Vergleicht die aktuelle Instanz mit einem anderen Objekt desselben Typs und gibt einen Integer zurück, der angibt, ob die aktuelle Instanz dem anderen Objekt vorausgeht, ihm folgt oder an derselben Position in der Sortierreihenfolge wie das andere Objekt steht. |
| [create_with_tag(tag_id)](#create_with_tag_tag_id_2) | Initialisiert eine neue Instanz der [TiffRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/) Klasse. |
| [create_with_tag_id(tag_id)](#create_with_tag_id_tag_id_3) | Initialisiert eine neue Instanz der [TiffRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/) Klasse. |
| [deep_clone()](#deep_clone__4) | Führt eine tiefe Kopie dieser Instanz aus. |
| [get_additional_data_size(size_of_tag_value)](#get_additional_data_size_size_of_tag_value_5) | Ermittelt die zusätzliche Tag‑Wertgröße in Bytes (falls das Tag den gesamten Tag‑Wert nicht aufnehmen kann). |
| [get_aligned_data_size(size_of_tag_value)](#get_aligned_data_size_size_of_tag_value_6) | Ermittelt die Datenmenge, ausgerichtet an einer 4‑Byte‑(int)‑ oder 8‑Byte‑(long)‑Grenze. |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_7) | Liest die Tag‑Daten. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_8) | Schreibt die zusätzlichen Tag‑Daten. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_9) | Schreibt den Tag‑Wert oder den zusätzlichen Offset. |


### Constructor: TiffRationalType(tag_id) {#TiffRationalType_tag_id_1}


```
 TiffRationalType(tag_id) 
```

Initialisiert eine neue Instanz der [TiffRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Die Tag‑ID. |

### Constructor: TiffRationalType(tag_id) {#TiffRationalType_tag_id_2}


```
 TiffRationalType(tag_id) 
```

Initialisiert eine neue Instanz der [TiffRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag_id | int | Die Tag‑ID. |

### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

Vergleicht die aktuelle Instanz mit einem anderen Objekt desselben Typs und gibt einen Integer zurück, der angibt, ob die aktuelle Instanz dem anderen Objekt vorausgeht, ihm folgt oder an derselben Position in der Sortierreihenfolge wie das andere Objekt steht.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| obj | System.Object | Ein Objekt zum Vergleich mit dieser Instanz. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Ein 32‑Bit‑vorzeichenbehafteter Integer, der die relative Reihenfolge der zu vergleichenden Objekte angibt. Der Rückgabewert hat diese Bedeutungen:<br/>            Wert<br/>            Bedeutung<br/>            Kleiner als Null<br/>            Diese Instanz ist kleiner als _obj_.<br/>            Null<br/>            Diese Instanz ist gleich _obj_.<br/>            Größer als Null<br/>            Diese Instanz ist größer als _obj_. |


### Method: create_with_tag(tag_id)  [static] {#create_with_tag_tag_id_2}


```
 create_with_tag(tag_id) 
```

Initialisiert eine neue Instanz der [TiffRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Die Tag‑ID. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/) |  |


### Method: create_with_tag_id(tag_id)  [static] {#create_with_tag_id_tag_id_3}


```
 create_with_tag_id(tag_id) 
```

Initialisiert eine neue Instanz der [TiffRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag_id | int | Die Tag‑ID. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffRationalType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffrationaltype/) |  |


### Method: deep_clone() {#deep_clone__4}


```
 deep_clone() 
```

Führt eine tiefe Kopie dieser Instanz aus.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Eine tiefe Kopie der aktuellen Instanz. |


### Method: get_additional_data_size(size_of_tag_value) {#get_additional_data_size_size_of_tag_value_5}


```
 get_additional_data_size(size_of_tag_value) 
```

Ermittelt die zusätzliche Tag‑Wertgröße in Bytes (falls das Tag den gesamten Tag‑Wert nicht aufnehmen kann).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size_of_tag_value | System.Byte | Größe des Tag‑Werts: 4 oder 8 für BigTiff. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die zusätzliche Datenmenge in Bytes. |


### Method: get_aligned_data_size(size_of_tag_value) {#get_aligned_data_size_size_of_tag_value_6}


```
 get_aligned_data_size(size_of_tag_value) 
```

Ermittelt die Datenmenge, ausgerichtet an einer 4‑Byte‑(int)‑ oder 8‑Byte‑(long)‑Grenze.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| size_of_tag_value | System.Byte | Größe des Tag‑Werts. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die ausgerichtete Datenmenge in Bytes. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_7}


```
 read_tag(data_stream, position) 
```

Liest die Tag‑Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | Der Daten-Stream. |
| position | int | Die Tag‑Position. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Das gelesene Tag. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_8}


```
 write_additional_data(data_stream) 
```

Schreibt die zusätzlichen Tag‑Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Der Daten-Stream. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die tatsächlich geschriebenen Bytes. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_9}


```
 write_tag(data_stream, additional_data_offset) 
```

Schreibt den Tag‑Wert oder den zusätzlichen Offset.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Der Daten-Stream. |
| additional_data_offset | int | Der zusätzliche Daten‑Offset. |

