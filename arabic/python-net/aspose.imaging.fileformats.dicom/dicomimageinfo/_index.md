---
title: "فئة DicomImageInfo"
type: docs
weight: 30
url: /ar/python-net/aspose.imaging.fileformats.dicom/dicomimageinfo/
---

**Summary:** Contains all meta-information from Dicom file header

**Module:** [aspose.imaging.fileformats.dicom](/imaging/python-net/aspose.imaging.fileformats.dicom/)

**Full Name:** aspose.imaging.fileformats.dicom.DicomImageInfo

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| bits_allocated | int | r | يحصل على قيمة "bitsAllocated". |
| bits_stored | int | r | يحصل على عدد البتات المخزنة. |
| blues | System.Byte | r | يحصل على ألوان المصفوفة للون الأزرق |
| dicom_header_info_by_bytes | System.Byte | r | يحصل على معلومات رأس DICOM بالبايتات. |
| dicom_info | System.Collections.Generic.IList`1[[System.String]] | r | يحصل على معلومات الرأس لملف DICOM. |
| greens | System.Byte | r | يحصل على ألوان المصفوفة للون الأخضر |
| height | int | r | يحصل على الارتفاع. |
| is_little_endian | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه العينة little endian. |
| number_of_frames | int | r | يحصل على عدد الإطارات. |
| offset | int | r | يحصل على الإزاحة. |
| photo_interpretation | string | r | يحصل على قيمة "PhotoInterpretation". |
| pixel_representation | int | r | يحصل على قيمة البكسل "pixelRepresentation". |
| planar_configuration | int | r | يحصل على تكوين المستوى. |
| readonly_tags_list [static] | System.Collections.Generic.IList`1[[System.String]] | r | قائمة العلامات للقراءة فقط. سيتم إعادة تعيين قيم هذه العلامات وفقًا لبيانات الصورة الفعلية عند حفظ الصورة. |
| الأحمر | System.Byte | r | يحصل على ألوان المصفوفة للون الأحمر |
| rescale_intercept | float | r | يحصل على قيمة "rescaleIntercept". |
| rescale_slope | float | r | يحصل على قيمة "rescaleSlope". |
| samples_per_pixel | int | r | يحصل على قيمة "samplesPerPixel". |
| signed_image | bool | r | يحصل على قيمة تشير إلى ما إذا كان "signedImage". |
| width | int | r | يحصل على العرض. |
| window_centre | float | r | يحصل على مركز النافذة. |
| window_width | float | r | يحصل على عرض النافذة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_tag(tag_description, value)](#add_tag_tag_description_value_1) | أضف علامة Dicom جديدة. |
| [remove_tag_at(index)](#remove_tag_at_index_2) | أزل علامة موجودة. |
| [try_add_tag(tag_description, value)](#try_add_tag_tag_description_value_3) | أضف علامة Dicom جديدة. |
| [try_remove_tag_at(index)](#try_remove_tag_at_index_4) | أزل علامة موجودة. |
| [try_update_tag_at(index, new_value)](#try_update_tag_at_index_new_value_5) | حدّث علامة موجودة. |
| [update_tag_at(index, new_value)](#update_tag_at_index_new_value_6) | حدّث علامة موجودة. |


### Method: add_tag(tag_description, value) {#add_tag_tag_description_value_1}


```
 add_tag(tag_description, value) 
```

أضف علامة Dicom جديدة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| tag_description | string | وصف العلامة. لا يمكن أن يكون فارغًا أو مسافة بيضاء. |
| القيمة | System.Object | قيمة العلامة. لا يمكن أن تكون فارغة. |

### Method: remove_tag_at(index) {#remove_tag_at_index_2}


```
 remove_tag_at(index) 
```

أزل علامة موجودة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| index | int | فهرس العلامة التي سيتم تحديثها. |

### Method: try_add_tag(tag_description, value) {#try_add_tag_tag_description_value_3}


```
 try_add_tag(tag_description, value) 
```

أضف علامة Dicom جديدة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| tag_description | string | وصف العلامة. لا يمكن أن يكون فارغًا أو مسافة بيضاء. |
| القيمة | System.Object | قيمة العلامة. لا يمكن أن تكون فارغة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | نتيجة العملية. |


### Method: try_remove_tag_at(index) {#try_remove_tag_at_index_4}


```
 try_remove_tag_at(index) 
```

أزل علامة موجودة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| index | int | فهرس العلامة التي سيتم تحديثها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | نتيجة العملية. |


### Method: try_update_tag_at(index, new_value) {#try_update_tag_at_index_new_value_5}


```
 try_update_tag_at(index, new_value) 
```

حدّث علامة موجودة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| index | int | فهرس العلامة التي سيتم تحديثها. |
| new_value | System.Object | قيمة العلامة. لا يمكن أن تكون فارغة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | نتيجة العملية. |


### Method: update_tag_at(index, new_value) {#update_tag_at_index_new_value_6}


```
 update_tag_at(index, new_value) 
```

حدّث علامة موجودة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| index | int | فهرس العلامة التي سيتم تحديثها. |
| new_value | System.Object | قيمة العلامة. لا يمكن أن تكون فارغة. |

