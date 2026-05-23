---
title: "TiffSLongType Sınıf"
type: docs
weight: 130
url: /tr/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffslongtype/
---

**Summary:** The tiff signed long type.

**Module:** [aspose.imaging.fileformats.tiff.tifftagtypes](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/)

**Full Name:** aspose.imaging.fileformats.tiff.tifftagtypes.TiffSLongType

**Inheritance:** TiffCommonArrayType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [TiffSLongType(tag_id)](#TiffSLongType_tag_id_1) | Yeni bir [TiffSLongType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffslongtype/) sınıfının bir örneğini başlatır. |
| [TiffSLongType(tag_id)](#TiffSLongType_tag_id_2) | Yeni bir [TiffSLongType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffslongtype/) sınıfının bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| count | int | r | Eleman sayısını alır. |
| data_size | int | r | Etiket değerinin boyutunu alır. |
| element_size | System.Byte | r | Elemanın bayt cinsinden boyutunu alır. |
| id | int | r | Etiket kimliğini sayı olarak alır. |
| is_valid | bool | r | Etiket verisinin geçerli olup olmadığını gösteren bir değer alır. Geçerli etiket, korunabilecek verileri içerir. Geçersiz etiket depolanamaz. |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | r | Etiket kimliğini alır. |
| tag_type | [TiffDataTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffdatatypes/) | r | Etiket tipini alır. |
| değer | System.Object | r/w | Bu veri tipinin içerdiği değeri alır veya ayarlar. |
| values | int[] | r/w | Değerleri alır veya ayarlar. |
| values_container | System.Array | r | Değerler kapsayıcısını alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Geçerli örneği aynı türdeki başka bir nesneyle karşılaştırır ve geçerli örneğin diğer nesneye göre sıralama düzeninde önce mi, sonra mı yoksa aynı konumda mı olduğunu belirten bir tam sayı döndürür. |
| [create_with_tag(tag_id)](#create_with_tag_tag_id_2) | Yeni bir [TiffSLongType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffslongtype/) sınıfının bir örneğini başlatır. |
| [create_with_tag_id(tag_id)](#create_with_tag_id_tag_id_3) | Yeni bir [TiffSLongType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffslongtype/) sınıfının bir örneğini başlatır. |
| [deep_clone()](#deep_clone__4) | Bu örneğin derin bir kopyasını oluşturur. |
| [get_additional_data_size(size_of_tag_value)](#get_additional_data_size_size_of_tag_value_5) | Ek etiket değeri boyutunu bayt olarak alır (etiket tüm değerini sığdıramazsa). |
| [get_aligned_data_size(size_of_tag_value)](#get_aligned_data_size_size_of_tag_value_6) | Veri boyutunu 4 bayt (int) veya 8 bayt (long) sınırına hizalanmış olarak alır. |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_7) | Etiket verisini okur. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_8) | Ek etiket verisini yazar. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_9) | Etiket değerini veya ek ofseti yazar. |


### Constructor: TiffSLongType(tag_id) {#TiffSLongType_tag_id_1}


```
 TiffSLongType(tag_id) 
```

Yeni bir [TiffSLongType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffslongtype/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Etiket kimliği. |

### Constructor: TiffSLongType(tag_id) {#TiffSLongType_tag_id_2}


```
 TiffSLongType(tag_id) 
```

Yeni bir [TiffSLongType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffslongtype/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tag_id | int | Etiket kimliği. |

### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

Geçerli örneği aynı türdeki başka bir nesneyle karşılaştırır ve geçerli örneğin diğer nesneye göre sıralama düzeninde önce mi, sonra mı yoksa aynı konumda mı olduğunu belirten bir tam sayı döndürür.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| obj | System.Object | Bu örnekle karşılaştırılacak bir nesne. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | A 32-bit işaretli bir tam sayı, karşılaştırılan nesnelerin göreli sırasını gösterir. Döndürülen değer aşağıdaki anlamlara sahiptir:<br/>            Değer<br/>            Anlam<br/>            Sıfırdan küçük<br/>            Bu örnek _obj_'den küçüktür.<br/>            Sıfır<br/>            Bu örnek _obj_'e eşittir.<br/>            Sıfırdan büyük<br/>            Bu örnek _obj_'den büyüktür. |


### Method: create_with_tag(tag_id)  [static] {#create_with_tag_tag_id_2}


```
 create_with_tag(tag_id) 
```

Yeni bir [TiffSLongType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffslongtype/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | Etiket kimliği. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffSLongType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffslongtype/) |  |


### Method: create_with_tag_id(tag_id)  [static] {#create_with_tag_id_tag_id_3}


```
 create_with_tag_id(tag_id) 
```

Yeni bir [TiffSLongType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffslongtype/) sınıfının bir örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| tag_id | int | Etiket kimliği. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffSLongType](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffslongtype/) |  |


### Method: deep_clone() {#deep_clone__4}


```
 deep_clone() 
```

Bu örneğin derin bir kopyasını oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Geçerli örneğin derin bir kopyası. |


### Method: get_additional_data_size(size_of_tag_value) {#get_additional_data_size_size_of_tag_value_5}


```
 get_additional_data_size(size_of_tag_value) 
```

Ek etiket değeri boyutunu bayt olarak alır (etiket tüm değerini sığdıramazsa).

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size_of_tag_value | System.Byte | Etiket değeri boyutu: BigTiff için 4 veya 8. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Ek veri boyutu bayt cinsinden. |


### Method: get_aligned_data_size(size_of_tag_value) {#get_aligned_data_size_size_of_tag_value_6}


```
 get_aligned_data_size(size_of_tag_value) 
```

Veri boyutunu 4 bayt (int) veya 8 bayt (long) sınırına hizalanmış olarak alır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| size_of_tag_value | System.Byte | Etiket değeri boyutu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Hizalanmış veri boyutu bayt olarak. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_7}


```
 read_tag(data_stream, position) 
```

Etiket verisini okur.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | Veri akışı. |
| position | int | Etiket konumu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Okunan etiket. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_8}


```
 write_additional_data(data_stream) 
```

Ek etiket verisini yazar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Veri akışı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Gerçek yazılan baytlar. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_9}


```
 write_tag(data_stream, additional_data_offset) 
```

Etiket değerini veya ek ofseti yazar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Veri akışı. |
| additional_data_offset | int | Ek veri ofseti. |

