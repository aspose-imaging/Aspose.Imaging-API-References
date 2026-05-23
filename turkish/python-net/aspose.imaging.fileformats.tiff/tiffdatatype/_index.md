---
title: "TiffDataType Sınıfı"
type: docs
weight: 130
url: /tr/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/
---

**Summary:** The TIFF data type.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffDataType

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
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | Geçerli örneği aynı türdeki başka bir nesneyle karşılaştırır ve geçerli örneğin diğer nesneye göre sıralama düzeninde önce mi, sonra mı yoksa aynı konumda mı olduğunu belirten bir tam sayı döndürür. |
| [deep_clone()](#deep_clone__2) | Bu örneğin derin bir kopyasını oluşturur. |
| [get_additional_data_size(size_of_tag_value)](#get_additional_data_size_size_of_tag_value_3) | Ek etiket değeri boyutunu bayt olarak alır (etiket tüm değerini sığdıramazsa). |
| [get_aligned_data_size(size_of_tag_value)](#get_aligned_data_size_size_of_tag_value_4) | Veri boyutunu 4 bayt (int) veya 8 bayt (long) sınırına hizalanmış olarak alır. |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_5) | Etiket verisini okur. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_6) | Ek etiket verisini yazar. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_7) | Etiket verilerini yazar. |


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


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

Bu örneğin derin bir kopyasını oluşturur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | Geçerli örneğin derin bir kopyası. |


### Method: get_additional_data_size(size_of_tag_value) {#get_additional_data_size_size_of_tag_value_3}


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


### Method: get_aligned_data_size(size_of_tag_value) {#get_aligned_data_size_size_of_tag_value_4}


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


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_5}


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


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_6}


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


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_7}


```
 write_tag(data_stream, additional_data_offset) 
```

Etiket verilerini yazar.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | Veri akışı. |
| additional_data_offset | int | Ek veri yazılacak ofset. |

