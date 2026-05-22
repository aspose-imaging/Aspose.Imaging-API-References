---
title: "فئة DataStreamSupporter"
type: docs
weight: 1360
url: /ar/python-net/aspose.imaging/datastreamsupporter/
---

**Summary:** The data stream container.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.DataStreamSupporter

**Inheritance:** DisposableObject

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | يحصل على تدفق بيانات الكائن. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| is_cached | bool | r | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| cache_data() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل أي بيانات إضافية من [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/). |
| save() | يحفظ بيانات الكائن إلى [DataStreamSupporter](/imaging/python-net/aspose.imaging/datastreamsupporter/) الحالي. |
| [save(file_path)](#save_file_path_1) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [save(file_path, over_write)](#save_file_path_over_write_2) | يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [save(stream)](#save_stream_3) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [save_to_stream(stream)](#save_to_stream_stream_4) | يحفظ بيانات الكائن إلى الدفق المحدد. |


### Method: save(file_path) {#save_file_path_1}


```
 save(file_path) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الكائن فيه. |

### Method: save(file_path, over_write) {#save_file_path_over_write_2}


```
 save(file_path, over_write) 
```

يقوم بحفظ بيانات الكائن إلى موقع الملف المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الكائن فيه. |
| over_write | bool | إذا تم تعيينه إلى <c>true</c> سيكتب فوق محتويات الملف، وإلا سيحدث الإلحاق. |

### Method: save(stream) {#save_stream_3}


```
 save(stream) 
```

يحفظ بيانات الكائن إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | المجرى لحفظ بيانات الكائن إليه. |

### Method: save_to_stream(stream) {#save_to_stream_stream_4}


```
 save_to_stream(stream) 
```

يحفظ بيانات الكائن إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | المجرى لحفظ بيانات الكائن إليه. |

