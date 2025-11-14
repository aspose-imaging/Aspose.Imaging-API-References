---
title: DicomImageInfo Class
type: docs
weight: 30
url: /python-net/aspose.imaging.fileformats.dicom/dicomimageinfo/
---

**Summary:** Contains all meta-information from Dicom file header

**Module:** [aspose.imaging.fileformats.dicom](/imaging/python-net/aspose.imaging.fileformats.dicom/)

**Full Name:** aspose.imaging.fileformats.dicom.DicomImageInfo

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bits_allocated | int | r | Gets a value of the "bitsAllocated". |
| bits_stored | int | r | Gets the number of stored bits. |
| blues | System.Byte | r | Gets the array colors of the blue |
| dicom_header_info_by_bytes | System.Byte | r | Gets the dicom header information by bytes. |
| dicom_info | System.Collections.Generic.IList`1[[System.String]] | r | Gets the header information of the DICOM file. |
| greens | System.Byte | r | Gets the array colors of the green |
| height | int | r | Gets the height. |
| is_little_endian | bool | r | Gets a value indicating whether this instance is little endian. |
| number_of_frames | int | r | Gets the number of frames. |
| offset | int | r | Gets the offset. |
| photo_interpretation | string | r | Gets a value of the "PhotoInterpretation". |
| pixel_representation | int | r | Gets a value of the pixel "pixelRepresentation". |
| planar_configuration | int | r | Gets the planar configuration. |
| readonly_tags_list [static] | System.Collections.Generic.IList`1[[System.String]] | r | The read-only tags list. These tag values will be reset according to the actual image data upon image save. |
| reds | System.Byte | r | Gets the array colors of the red |
| rescale_intercept | float | r | Gets a value of the "rescaleIntercept". |
| rescale_slope | float | r | Gets a value of the "rescaleSlope". |
| samples_per_pixel | int | r | Gets a value of the "samplesPerPixel". |
| signed_image | bool | r | Gets a value indicating whether "signedImage". |
| width | int | r | Gets the width. |
| window_centre | float | r | Gets the window centre. |
| window_width | float | r | Gets the width of the window. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_tag(tag_description, value)](#add_tag_tag_description_value_1) | Add new Dicom tag. |
| [remove_tag_at(index)](#remove_tag_at_index_2) | Remove an existing tag. |
| [try_add_tag(tag_description, value)](#try_add_tag_tag_description_value_3) | Add new Dicom tag. |
| [try_remove_tag_at(index)](#try_remove_tag_at_index_4) | Remove an existing tag. |
| [try_update_tag_at(index, new_value)](#try_update_tag_at_index_new_value_5) | Update an existing tag. |
| [update_tag_at(index, new_value)](#update_tag_at_index_new_value_6) | Update an existing tag. |


### Method: add_tag(tag_description, value) {#add_tag_tag_description_value_1}


```
 add_tag(tag_description, value) 
```

Add new Dicom tag.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag_description | string | The tag description. Can not be null or whitespace. |
| value | System.Object | The tag value. Can not be null. |

### Method: remove_tag_at(index) {#remove_tag_at_index_2}


```
 remove_tag_at(index) 
```

Remove an existing tag.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The index of the tag to be updated. |

### Method: try_add_tag(tag_description, value) {#try_add_tag_tag_description_value_3}


```
 try_add_tag(tag_description, value) 
```

Add new Dicom tag.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag_description | string | The tag description. Can not be null or whitespace. |
| value | System.Object | The tag value. Can not be null. |

**Returns**

| Type | Description |
| :- | :- |
| bool | The operation result. |


### Method: try_remove_tag_at(index) {#try_remove_tag_at_index_4}


```
 try_remove_tag_at(index) 
```

Remove an existing tag.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The index of the tag to be updated. |

**Returns**

| Type | Description |
| :- | :- |
| bool | The operation result. |


### Method: try_update_tag_at(index, new_value) {#try_update_tag_at_index_new_value_5}


```
 try_update_tag_at(index, new_value) 
```

Update an existing tag.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The index of the tag to be updated. |
| new_value | System.Object | The tag value. Can not be null. |

**Returns**

| Type | Description |
| :- | :- |
| bool | The operation result. |


### Method: update_tag_at(index, new_value) {#update_tag_at_index_new_value_6}


```
 update_tag_at(index, new_value) 
```

Update an existing tag.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| index | int | The index of the tag to be updated. |
| new_value | System.Object | The tag value. Can not be null. |

