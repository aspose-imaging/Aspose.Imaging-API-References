---
title: "الفئة FileStreamContainer"
type: docs
weight: 4810
url: /ar/python-net/aspose.imaging/filestreamcontainer/
---

**Summary:** Helper for file stream processing.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.FileStreamContainer

**Inheritance:** StreamContainer

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| READ_WRITE_BYTES_COUNT [static] | int | r | يحدد عدد البايتات للقراءة والكتابة عند القراءة المتسلسلة. |
| can_read | bool | r | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم القراءة. |
| can_seek | bool | r | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم السعي. |
| can_write | bool | r | يحصل على قيمة تشير إلى ما إذا كان التدفق يدعم الكتابة. |
| تم التخلص | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه المثيلة تم التخلص منها. |
| file_path | string | r | يحصل على مسار الملف. |
| is_created | bool | r | يحصل على قيمة تشير إلى ما إذا تم إنشاء الدفق صراحةً. |
| is_stream_disposed_on_close | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا التدفق يتم التخلص منه عند الإغلاق. |
| is_temporal | bool | r/w | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الدفق مؤقتًا. |
| length | int | r/w | يحصل أو يضبط طول التدفق بالبايت. هذه القيمة أقل من الـ  بموقع بدء التدفق الممرر في مُنشئ StreamContainer. |
| position | int | r/w | يحصل أو يضبط الموضع الحالي داخل التدفق. هذه القيمة تمثل الإزاحة من موقع بدء التدفق الممرر في مُنشئ StreamContainer. |
| دفق | _io.BufferedRandom | r | يحصل على تدفق البيانات. |
| sync_root | System.Object | r | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_file_stream(file_location, is_temporal)](#create_file_stream_file_location_is_temporal_1) | ينشئ دفق ملف جديد. |
| flush() | يمسح جميع المخازن المؤقتة لهذا التدفق ويتسبب في كتابة أي بيانات مخزنة مؤقتاً إلى الجهاز الأساسي. |
| [open_file_stream(file_location)](#open_file_stream_file_location_2) | يفتح دفق ملف موجود. إذا لم يكن دفق الملف موجودًا يتم إلقاء الاستثناء المناسب. |
| [read(buffer, offset, count)](#read_buffer_offset_count_3) | يقرأ تسلسلاً من البايتات من التدفق الحالي ويقدم الموضع داخل التدفق بعدد البايتات المقروءة. |
| [read(bytes)](#read_bytes_4) | يقرأ بايتات لملء مخزن البايتات المحدد. |
| [read_byte()](#read_byte__5) | يقرأ بايتاً من التدفق ويقدم الموضع داخل التدفق بايتاً واحداً، أو يُعيد -1 إذا كان عند نهاية التدفق. |
| [save(destination_stream)](#save_destination_stream_6) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) وقيمة الدفق [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(destination_stream, buffer_size)](#save_destination_stream_buffer_size_7) | يحفظ (ينسخ) جميع بيانات الدفق إلى الدفق المحدد. يستخدم قيمة الدفق [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(destination_stream, buffer_size, length)](#save_destination_stream_buffer_size_length_8) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [save(file_path)](#save_file_path_9) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) وقيمة الدفق [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(file_path, buffer_size)](#save_file_path_buffer_size_10) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم قيمة الدفق [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save(file_path, buffer_size, length)](#save_file_path_buffer_size_length_11) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [save_to_stream(destination_stream)](#save_to_stream_destination_stream_12) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) وقيمة الدفق [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_to_stream_with_buf_size(destination_stream, buffer_size)](#save_to_stream_with_buf_size_destination_stream_buffer_size_13) | يحفظ (ينسخ) جميع بيانات الدفق إلى الدفق المحدد. يستخدم قيمة الدفق [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length)](#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_14) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [save_with_buf_size(file_path, buffer_size)](#save_with_buf_size_file_path_buffer_size_15) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم قيمة الدفق [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |
| [save_with_buf_size_and_len(file_path, buffer_size, length)](#save_with_buf_size_and_len_file_path_buffer_size_length_16) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [seek(offset, origin)](#seek_offset_origin_17) | يضبط الموضع داخل الدفق الحالي. |
| seek_begin() | يضبط موضع الدفق إلى بداية الدفق. تمثل هذه القيمة الإزاحة من موضع بدء الدفق الممرر في مُنشئ StreamContainer. |
| [to_bytes()](#to_bytes__18) | يحوّل بيانات الدفق إلى مصفوفة من الأعداد الصحيحة. |
| [to_bytes(position, bytes_count)](#to_bytes_position_bytes_count_19) | يحوّل بيانات الدفق إلى مصفوفة من الأعداد الصحيحة. |
| [write(buffer, offset, count)](#write_buffer_offset_count_20) | يكتب تسلسلًا من البايتات إلى الدفق الحالي ويقدّم الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة. |
| [write(bytes)](#write_bytes_21) | يكتب جميع البايتات المحددة إلى الدفق. |
| [write_byte(value)](#write_byte_value_22) | يكتب بايتًا إلى الموضع الحالي في الدفق ويقدّم الموضع داخل الدفق بايتًا واحدًا. |
| [write_to(stream_container)](#write_to_stream_container_23) | ينسخ البيانات المحتواة إلى [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) آخر. |
| [write_to(stream_container, length)](#write_to_stream_container_length_24) | ينسخ البيانات المحتواة إلى [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) آخر. |


### Method: create_file_stream(file_location, is_temporal)  [static] {#create_file_stream_file_location_is_temporal_1}


```
 create_file_stream(file_location, is_temporal) 
```

ينشئ دفق ملف جديد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_location | string | موقع الملف. |
| is_temporal | bool | إذا تم تعيينه إلى <c>true</c> فإن حاوية دفق الملف تكون مؤقتة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer/) | حاوية دفق الملف. |


### Method: open_file_stream(file_location)  [static] {#open_file_stream_file_location_2}


```
 open_file_stream(file_location) 
```

يفتح دفق ملف موجود. إذا لم يكن دفق الملف موجودًا يتم إلقاء الاستثناء المناسب.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_location | string | موقع الملف. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer/) | حاوية دفق الملف. |


### Method: read(buffer, offset, count) {#read_buffer_offset_count_3}


```
 read(buffer, offset, count) 
```

يقرأ تسلسلاً من البايتات من التدفق الحالي ويقدم الموضع داخل التدفق بعدد البايتات المقروءة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المخزن المؤقت | System.Byte | مصفوفة من البايتات. عند عودة هذه الطريقة، يحتوي المخزن المؤقت على مصفوفة البايتات المحددة مع القيم بين _offset_ و(_offset_ + _count_ - 1) المستبدلة بالبايتات المقروءة من المصدر الحالي. |
| offset | int | الإزاحة الصفرية للبايت في _buffer_ التي يبدأ عندها تخزين البيانات المقروءة من الدفق الحالي. |
| count | int | الحد الأقصى لعدد البايتات التي سيتم قراءتها من الدفق الحالي. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | إجمالي عدد البايتات المقروءة إلى المخزن المؤقت. قد يكون أقل من عدد البايتات المطلوبة إذا لم تتوفر تلك البايتات حاليًا، أو صفر (0) إذا تم الوصول إلى نهاية الدفق. |


### Method: read(bytes) {#read_bytes_4}


```
 read(bytes) 
```

يقرأ بايتات لملء مخزن البايتات المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| بايتات | System.Byte | البايتات للتعبئة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | عدد البايتات المقروءة. قد تكون هذه القيمة أقل من عدد البايتات في المخزن المؤقت إذا لم يتوفر ما يكفي من البايتات في الدفق. |


### Method: read_byte() {#read_byte__5}


```
 read_byte() 
```

يقرأ بايتاً من التدفق ويقدم الموضع داخل التدفق بايتاً واحداً، أو يُعيد -1 إذا كان عند نهاية التدفق.

**Returns**

| نوع | الوصف |
| :- | :- |
| int | البايت غير الموقّع يتم تحويله إلى Int32، أو -1 إذا كان في نهاية الدفق. |


### Method: save(destination_stream) {#save_destination_stream_6}


```
 save(destination_stream) 
```

يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) وقيمة الدفق [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | الدفق لحفظ البيانات إليه. |

### Method: save(destination_stream, buffer_size) {#save_destination_stream_buffer_size_7}


```
 save(destination_stream, buffer_size) 
```

يحفظ (ينسخ) جميع بيانات الدفق إلى الدفق المحدد. يستخدم قيمة الدفق [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | الدفق لحفظ البيانات إليه. |
| حجم_المخزن_المؤقت | int | المخزن المؤقت. |

### Method: save(destination_stream, buffer_size, length) {#save_destination_stream_buffer_size_length_8}


```
 save(destination_stream, buffer_size, length) 
```

يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | الدفق لحفظ البيانات إليه. |
| buffer_size | int | حجم المخزن المؤقت. بشكل افتراضي يتم استخدام قيمة [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | طول بيانات الدفق للنسخ. بشكل افتراضي يتم تعيين الطول إلى قيمة [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save(file_path) {#save_file_path_9}


```
 save(file_path) 
```

يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) وقيمة الدفق [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الدفق إليه. |

### Method: save(file_path, buffer_size) {#save_file_path_buffer_size_10}


```
 save(file_path, buffer_size) 
```

يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم قيمة الدفق [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الدفق إليه. |
| buffer_size | int | حجم المخزن المؤقت. بشكل افتراضي يتم استخدام قيمة [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save(file_path, buffer_size, length) {#save_file_path_buffer_size_length_11}


```
 save(file_path, buffer_size, length) 
```

يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الدفق إليه. |
| buffer_size | int | حجم المخزن المؤقت. بشكل افتراضي يتم استخدام قيمة [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | طول بيانات الدفق للنسخ. بشكل افتراضي يتم تعيين الطول إلى قيمة [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save_to_stream(destination_stream) {#save_to_stream_destination_stream_12}


```
 save_to_stream(destination_stream) 
```

يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/) وقيمة الدفق [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | الدفق لحفظ البيانات إليه. |

### Method: save_to_stream_with_buf_size(destination_stream, buffer_size) {#save_to_stream_with_buf_size_destination_stream_buffer_size_13}


```
 save_to_stream_with_buf_size(destination_stream, buffer_size) 
```

يحفظ (ينسخ) جميع بيانات الدفق إلى الدفق المحدد. يستخدم قيمة الدفق [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | الدفق لحفظ البيانات إليه. |
| حجم_المخزن_المؤقت | int | المخزن المؤقت. |

### Method: save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) {#save_to_stream_with_buf_size_and_len_destination_stream_buffer_size_length_14}


```
 save_to_stream_with_buf_size_and_len(destination_stream, buffer_size, length) 
```

يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| destination_stream | _io.BufferedRandom | الدفق لحفظ البيانات إليه. |
| buffer_size | int | حجم المخزن المؤقت. بشكل افتراضي يتم استخدام قيمة [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | طول بيانات الدفق للنسخ. بشكل افتراضي يتم تعيين الطول إلى قيمة [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save_with_buf_size(file_path, buffer_size) {#save_with_buf_size_file_path_buffer_size_15}


```
 save_with_buf_size(file_path, buffer_size) 
```

يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم قيمة الدفق [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الدفق إليه. |
| buffer_size | int | حجم المخزن المؤقت. بشكل افتراضي يتم استخدام قيمة [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: save_with_buf_size_and_len(file_path, buffer_size, length) {#save_with_buf_size_and_len_file_path_buffer_size_length_16}


```
 save_with_buf_size_and_len(file_path, buffer_size, length) 
```

يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الدفق إليه. |
| buffer_size | int | حجم المخزن المؤقت. بشكل افتراضي يتم استخدام قيمة [StreamContainer.READ_WRITE_BYTES_COUNT](/imaging/python-net/aspose.imaging/streamcontainer/). |
| length | int | طول بيانات الدفق للنسخ. بشكل افتراضي يتم تعيين الطول إلى قيمة [StreamContainer.length](/imaging/python-net/aspose.imaging/streamcontainer/). |

### Method: seek(offset, origin) {#seek_offset_origin_17}


```
 seek(offset, origin) 
```

يضبط الموضع داخل الدفق الحالي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| offset | int | إزاحة بايت نسبية إلى المعامل _origin_. تمثل هذه القيمة الإزاحة من موضع بدء الدفق الممرّر في مُنشئ StreamContainer. |
| origin | [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin/) | قيمة من نوع SeekOrigin تشير إلى نقطة المرجع المستخدمة للحصول على الموضع الجديد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| int | الموضع الجديد داخل الدفق الحالي. |


### Method: to_bytes() {#to_bytes__18}


```
 to_bytes() 
```

يحوّل بيانات الدفق إلى مصفوفة من الأعداد الصحيحة.

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Byte | بيانات الدفق محوّلة إلى مصفوفة int. |


### Method: to_bytes(position, bytes_count) {#to_bytes_position_bytes_count_19}


```
 to_bytes(position, bytes_count) 
```

يحوّل بيانات الدفق إلى مصفوفة من الأعداد الصحيحة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| position | int | الموضع لبدء قراءة البايتات منه. |
| bytes_count | int | عدد البايتات للقراءة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Byte | بيانات الدفق محوّلة إلى مصفوفة int. |


### Method: write(buffer, offset, count) {#write_buffer_offset_count_20}


```
 write(buffer, offset, count) 
```

يكتب تسلسلًا من البايتات إلى الدفق الحالي ويقدّم الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المخزن المؤقت | System.Byte | مصفوفة من البايتات. تقوم هذه الطريقة بنسخ _count_ بايت من _buffer_ إلى الدفق الحالي. |
| offset | int | إزاحة البايت الصفرية في _buffer_ التي يبدأ عندها نسخ البايتات إلى الدفق الحالي. |
| count | int | عدد البايتات التي سيتم كتابتها إلى الدفق الحالي. |

### Method: write(bytes) {#write_bytes_21}


```
 write(bytes) 
```

يكتب جميع البايتات المحددة إلى الدفق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| بايتات | System.Byte | البايتات للكتابة. |

### Method: write_byte(value) {#write_byte_value_22}


```
 write_byte(value) 
```

يكتب بايتًا إلى الموضع الحالي في الدفق ويقدّم الموضع داخل الدفق بايتًا واحدًا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| القيمة | System.Byte | البايت للكتابة إلى الدفق. |

### Method: write_to(stream_container) {#write_to_stream_container_23}


```
 write_to(stream_container) 
```

ينسخ البيانات المحتواة إلى [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) آخر.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | حاوية الدفق للنسخ إليها. |

### Method: write_to(stream_container, length) {#write_to_stream_container_length_24}


```
 write_to(stream_container, length) 
```

ينسخ البيانات المحتواة إلى [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) آخر.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | حاوية الدفق للنسخ إليها. |
| length | int | عدد البايتات للكتابة. |

