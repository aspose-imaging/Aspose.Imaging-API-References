---
title: "TiffUnknownType Classe"
type: docs
weight: 180
url: /fr/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---

**Summary:** The unknown tiff type. In case the tiff tag cannot be recognized this type is instantinated.

**Module:** [aspose.imaging.fileformats.tiff.tifftagtypes](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/)

**Full Name:** aspose.imaging.fileformats.tiff.tifftagtypes.TiffUnknownType

**Inheritance:** TiffDataType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffUnknownType(stream, tag_type, tag_id, count, offset_or_value)](#TiffUnknownType_stream_tag_type_tag_id_count_offset_or_value_1) | Initialise une nouvelle instance de la [TiffUnknownType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/) classe. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r | Obtient le nombre d'éléments. |
| data_size | int | r | Obtient la taille de la valeur du tag. |
| element_size | System.Byte | r | Obtient la taille de l'élément en octets. |
| id | int | r | Obtient l'identifiant du tag sous forme de nombre. |
| is_valid | bool | r | Obtient une valeur indiquant si les données du tag sont valides. Le tag valide contient des données qui peuvent être conservées. Le tag invalide ne peut pas être stocké. |
| offset_or_value | int | r | Obtient la valeur de décalage pour des données supplémentaires ou la valeur elle-même si le nombre est 1. |
| stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | r | Obtient le flux pour lire les données supplémentaires. |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | r | Obtient l'identifiant du tag. |
| tag_type | [TiffDataTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffdatatypes/) | r | Obtient le type du tag. |
| value | System.Object | r/w | Obtient ou définit la valeur que ce type de données contient. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Compare l'instance actuelle avec un autre objet du même type et renvoie un entier qui indique si l'instance actuelle précède, suit ou se trouve à la même position dans l'ordre de tri que l'autre objet. |
| [deep_clone()](#deep_clone__2) | Effectue une copie profonde de cette instance. |
| [get_additional_data_size(size_of_tag_value)](#get_additional_data_size_size_of_tag_value_3) | Obtient la taille supplémentaire de la valeur de l'étiquette en octets (au cas où l'étiquette ne pourrait pas contenir la valeur complète). |
| [get_aligned_data_size(size_of_tag_value)](#get_aligned_data_size_size_of_tag_value_4) | Obtient la taille des données alignée sur une frontière de 4 octets (int) ou de 8 octets (long). |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_5) | Lit les données de l'étiquette. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_6) | Écrit les données supplémentaires de l'étiquette. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_7) | Écrit la valeur de l'étiquette ou le décalage supplémentaire. |


### Constructor: TiffUnknownType(stream, tag_type, tag_id, count, offset_or_value) {#TiffUnknownType_stream_tag_type_tag_id_count_offset_or_value_1}


```
 TiffUnknownType(stream, tag_type, tag_id, count, offset_or_value) 
```

Initialise une nouvelle instance de la [TiffUnknownType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/) classe.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | Le flux à lire. |
| tag_type | int | Type du tag. |
| tag_id | int | L'identifiant de l'étiquette. |
| count | int | La valeur du compte. |
| offset_or_value | int | Le décalage ou la valeur. |

### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

Compare l'instance actuelle avec un autre objet du même type et renvoie un entier qui indique si l'instance actuelle précède, suit ou se trouve à la même position dans l'ordre de tri que l'autre objet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| obj | System.Object | Un objet à comparer avec cette instance. |

**Returns**

| Type | Description |
| :- | :- |
| int | Un entier signé de 32 bits qui indique l'ordre relatif des objets comparés. La valeur de retour a les significations suivantes :<br/>            Valeur<br/>            Signification<br/>            Inférieur à zéro<br/>            Cette instance est inférieure à _obj_.<br/>            Zéro<br/>            Cette instance est égale à _obj_.<br/>            Supérieur à zéro<br/>            Cette instance est supérieure à _obj_. |


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

Effectue une copie profonde de cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Une copie profonde de l'instance actuelle. |


### Method: get_additional_data_size(size_of_tag_value) {#get_additional_data_size_size_of_tag_value_3}


```
 get_additional_data_size(size_of_tag_value) 
```

Obtient la taille supplémentaire de la valeur de l'étiquette en octets (au cas où l'étiquette ne pourrait pas contenir la valeur complète).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size_of_tag_value | System.Byte | Taille de la valeur de l'étiquette : 4 ou 8 pour BigTiff. |

**Returns**

| Type | Description |
| :- | :- |
| int | La taille supplémentaire des données en octets. |


### Method: get_aligned_data_size(size_of_tag_value) {#get_aligned_data_size_size_of_tag_value_4}


```
 get_aligned_data_size(size_of_tag_value) 
```

Obtient la taille des données alignée sur une frontière de 4 octets (int) ou de 8 octets (long).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| size_of_tag_value | System.Byte | Taille de la valeur de l'étiquette. |

**Returns**

| Type | Description |
| :- | :- |
| int | La taille des données alignées en octets. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_5}


```
 read_tag(data_stream, position) 
```

Lit les données de l'étiquette.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | Le flux de données. |
| position | int | La position de l'étiquette. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | L'étiquette lue. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_6}


```
 write_additional_data(data_stream) 
```

Écrit les données supplémentaires de l'étiquette.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Le flux de données. |

**Returns**

| Type | Description |
| :- | :- |
| int | Le nombre réel d'octets écrits. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_7}


```
 write_tag(data_stream, additional_data_offset) 
```

Écrit la valeur de l'étiquette ou le décalage supplémentaire.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Le flux de données. |
| additional_data_offset | int | Le décalage supplémentaire des données. |

