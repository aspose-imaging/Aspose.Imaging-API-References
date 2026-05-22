---
title: "فئة TiffCommonArrayType"
type: docs
weight: 30
url: /ar/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffcommonarraytype/
---

**Summary:** The tiff common array type.

**Module:** [aspose.imaging.fileformats.tiff.tifftagtypes](/imaging/python-net/aspose.imaging.fileformats.tiff.tifftagtypes/)

**Full Name:** aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType

**Inheritance:** TiffDataType

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| count | int | r | يحصل على عدد العناصر. |
| data_size | int | r | يحصل على حجم قيمة العلامة. |
| element_size | System.Byte | r | يحصل على حجم العنصر بالبايت. |
| id | int | r | يحصل على معرف العلامة كرقم. |
| is_valid | bool | r | يحصل على قيمة تشير إلى ما إذا كانت بيانات العلامة صالحة. العلامة الصالحة تحتوي على بيانات يمكن حفظها. العلامة غير الصالحة لا يمكن تخزينها. |
| tag_id | [TiffTags](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tifftags/) | r | يحصل على معرف العلامة. |
| tag_type | [TiffDataTypes](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffdatatypes/) | r | يحصل على نوع العلامة. |
| القيمة | System.Object | r/w | يحصل أو يضبط القيمة التي يحتويها هذا النوع من البيانات. |
| values_container | System.Array | r | يحصل على حاوية القيم. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [compare_to(obj)](#compare_to_obj_1) | يقارن المثيل الحالي مع كائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كان المثيل الحالي يسبق أو يتبع أو يقع في نفس الموضع في ترتيب الفرز مثل الكائن الآخر. |
| [deep_clone()](#deep_clone__2) | ينفذ استنساخًا عميقًا لهذا المثيل. |
| [get_additional_data_size(size_of_tag_value)](#get_additional_data_size_size_of_tag_value_3) | يحصل على حجم قيمة العلامة الإضافية بالبايت (في حالة عدم قدرة العلامة على احتواء القيمة الكاملة للعلامة). |
| [get_aligned_data_size(size_of_tag_value)](#get_aligned_data_size_size_of_tag_value_4) | يحصل على حجم البيانات محاذيًا على حد 4 بايت (int) أو 8 بايت (long). |
| [read_tag(data_stream, position)](#read_tag_data_stream_position_5) | يقرأ بيانات العلامة. |
| [write_additional_data(data_stream)](#write_additional_data_data_stream_6) | يكتب بيانات العلامة الإضافية. |
| [write_tag(data_stream, additional_data_offset)](#write_tag_data_stream_additional_data_offset_7) | يكتب قيمة العلامة أو الإزاحة الإضافية. |


### Method: compare_to(obj) {#compare_to_obj_1}


```
 compare_to(obj) 
```

يقارن المثيل الحالي مع كائن آخر من نفس النوع ويعيد عددًا صحيحًا يشير إلى ما إذا كان المثيل الحالي يسبق أو يتبع أو يقع في نفس الموضع في ترتيب الفرز مثل الكائن الآخر.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| obj | System.Object | كائن للمقارنة مع هذا المثيل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | عدد صحيح موقع 32 بت يشير إلى الترتيب النسبي للكائنات التي يتم مقارنتها. قيمة الإرجاع لها هذه المعاني:<br/>            القيمة<br/>            المعنى<br/>            أقل من الصفر<br/>            هذا المثيل أصغر من _obj_.<br/>            صفر<br/>            هذا المثيل يساوي _obj_.<br/>            أكبر من الصفر<br/>            هذا المثيل أكبر من _obj_. |


### Method: deep_clone() {#deep_clone__2}


```
 deep_clone() 
```

ينفذ استنساخًا عميقًا لهذا المثيل.

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | استنساخ عميق للمثيل الحالي. |


### Method: get_additional_data_size(size_of_tag_value) {#get_additional_data_size_size_of_tag_value_3}


```
 get_additional_data_size(size_of_tag_value) 
```

يحصل على حجم قيمة العلامة الإضافية بالبايت (في حالة عدم قدرة العلامة على احتواء القيمة الكاملة للعلامة).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| size_of_tag_value | System.Byte | حجم قيمة العلامة: 4 أو 8 لـ BigTiff. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | حجم البيانات الإضافية بالبايت. |


### Method: get_aligned_data_size(size_of_tag_value) {#get_aligned_data_size_size_of_tag_value_4}


```
 get_aligned_data_size(size_of_tag_value) 
```

يحصل على حجم البيانات محاذيًا على حد 4 بايت (int) أو 8 بايت (long).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| size_of_tag_value | System.Byte | حجم قيمة العلامة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | حجم البيانات المحاذاة بالبايت. |


### Method: read_tag(data_stream, position)  [static] {#read_tag_data_stream_position_5}


```
 read_tag(data_stream, position) 
```

يقرأ بيانات العلامة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| data_stream | [TiffStreamReader](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/) | دفق البيانات. |
| position | int | موضع العلامة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [TiffDataType](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffdatatype/) | العلامة المقروءة. |


### Method: write_additional_data(data_stream) {#write_additional_data_data_stream_6}


```
 write_additional_data(data_stream) 
```

يكتب بيانات العلامة الإضافية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | دفق البيانات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | عدد البايتات الفعلية المكتوبة. |


### Method: write_tag(data_stream, additional_data_offset) {#write_tag_data_stream_additional_data_offset_7}


```
 write_tag(data_stream, additional_data_offset) 
```

يكتب قيمة العلامة أو الإزاحة الإضافية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| data_stream | [TiffStreamWriter](/imaging/python-net/aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/) | دفق البيانات. |
| additional_data_offset | int | إزاحة البيانات الإضافية. |

