---
title: "DicomImageInfo 类"
type: docs
weight: 30
url: /zh/python-net/aspose.imaging.fileformats.dicom/dicomimageinfo/
---

**Summary:** Contains all meta-information from Dicom file header

**Module:** [aspose.imaging.fileformats.dicom](/imaging/python-net/aspose.imaging.fileformats.dicom/)

**Full Name:** aspose.imaging.fileformats.dicom.DicomImageInfo

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| bits_allocated | int | r | 获取 "bitsAllocated" 的值。 |
| bits_stored | int | r | 获取已存储位的数量。 |
| blues | System.Byte | r | 获取蓝色的颜色数组。 |
| dicom_header_info_by_bytes | System.Byte | r | 按字节获取 DICOM 头信息。 |
| dicom_info | System.Collections.Generic.IList`1[[System.String]] | r | 获取 DICOM 文件的头信息。 |
| greens | System.Byte | r | 获取绿色的颜色数组。 |
| height | int | r | 获取高度。 |
| is_little_endian | bool | r | 获取一个值，指示此实例是否为小端序。 |
| number_of_frames | int | r | 获取帧的数量。 |
| offset | int | r | 获取偏移量。 |
| photo_interpretation | string | r | 获取 "PhotoInterpretation" 的值。 |
| pixel_representation | int | r | 获取像素 "pixelRepresentation" 的值。 |
| planar_configuration | int | r | 获取平面配置。 |
| readonly_tags_list [static] | System.Collections.Generic.IList`1[[System.String]] | r | 只读标签列表。这些标签值将在图像保存时根据实际图像数据重置。 |
| reds | System.Byte | r | 获取红色的数组颜色 |
| rescale_intercept | float | r | 获取 "rescaleIntercept" 的值。 |
| rescale_slope | float | r | 获取 "rescaleSlope" 的值。 |
| samples_per_pixel | int | r | 获取 "samplesPerPixel" 的值。 |
| signed_image | bool | r | 获取指示是否为 "signedImage" 的值。 |
| width | int | r | 获取宽度。 |
| window_centre | float | r | 获取窗口中心。 |
| window_width | float | r | 获取窗口的宽度。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add_tag(tag_description, value)](#add_tag_tag_description_value_1) | 添加新的 Dicom 标签。 |
| [remove_tag_at(index)](#remove_tag_at_index_2) | 删除现有的标签。 |
| [try_add_tag(tag_description, value)](#try_add_tag_tag_description_value_3) | 添加新的 Dicom 标签。 |
| [try_remove_tag_at(index)](#try_remove_tag_at_index_4) | 删除现有的标签。 |
| [try_update_tag_at(index, new_value)](#try_update_tag_at_index_new_value_5) | 更新现有的标签。 |
| [update_tag_at(index, new_value)](#update_tag_at_index_new_value_6) | 更新现有的标签。 |


### Method: add_tag(tag_description, value) {#add_tag_tag_description_value_1}


```
 add_tag(tag_description, value) 
```

添加新的 Dicom 标签。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tag_description | string | 标签描述。不能为空或仅包含空白。 |
| value | System.Object | 标签值。不能为空。 |

### Method: remove_tag_at(index) {#remove_tag_at_index_2}


```
 remove_tag_at(index) 
```

删除现有的标签。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| index | int | 要更新的标签的索引。 |

### Method: try_add_tag(tag_description, value) {#try_add_tag_tag_description_value_3}


```
 try_add_tag(tag_description, value) 
```

添加新的 Dicom 标签。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| tag_description | string | 标签描述。不能为空或仅包含空白。 |
| value | System.Object | 标签值。不能为空。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 操作结果。 |


### Method: try_remove_tag_at(index) {#try_remove_tag_at_index_4}


```
 try_remove_tag_at(index) 
```

删除现有的标签。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| index | int | 要更新的标签的索引。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 操作结果。 |


### Method: try_update_tag_at(index, new_value) {#try_update_tag_at_index_new_value_5}


```
 try_update_tag_at(index, new_value) 
```

更新现有的标签。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| index | int | 要更新的标签的索引。 |
| new_value | System.Object | 标签值。不能为空。 |

**Returns**

| Type | Description |
| :- | :- |
| bool | 操作结果。 |


### Method: update_tag_at(index, new_value) {#update_tag_at_index_new_value_6}


```
 update_tag_at(index, new_value) 
```

更新现有的标签。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| index | int | 要更新的标签的索引。 |
| new_value | System.Object | 标签值。不能为空。 |

