---
title: "StreamContainer"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل حاوية تدفق تحتوي على التدفق وتوفر روتينات معالجة التدفق."
type: docs
weight: 109
url: /ar/java/com.aspose.imaging/streamcontainer/
---
**Inheritance:**
java.lang.Object، [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class StreamContainer extends DisposableObject implements ISynchronizable
```

يمثل حاوية تدفق تحتوي على التدفق وتوفر روتينات معالجة التدفق.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [StreamContainer(InputStream stream)](#StreamContainer-java.io.InputStream-) | يُنشئ مثيلًا جديدًا من الفئة `StreamContainer`. |
| [StreamContainer(System.IO.Stream stream)](#StreamContainer-com.aspose.ms.System.IO.Stream-) | يُنشئ مثيلًا جديدًا من الفئة `StreamContainer`. |
| [StreamContainer(InputStream stream, boolean disposeStream)](#StreamContainer-java.io.InputStream-boolean-) | يُنشئ مثيلًا جديدًا من الفئة `StreamContainer`. |
| [StreamContainer(System.IO.Stream stream, boolean disposeStream)](#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-) | يُنشئ مثيلًا جديدًا من الفئة `StreamContainer`. |
## الحقول

| حقل | الوصف |
| --- | --- |
| [READ_WRITE_BYTES_COUNT](#READ-WRITE-BYTES-COUNT) | يحدد عدد البايتات للقراءة والكتابة عند القراءة المتسلسلة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [to_Stream(StreamContainer streamContainer)](#to-Stream-com.aspose.imaging.StreamContainer-) | يُجري تحويلًا صريحًا من `com.aspose.imaging.StreamContainer` إلى `System.IO.Stream`. |
| [getSyncRoot()](#getSyncRoot--) | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |
| [getPosition()](#getPosition--) | يحصل أو يعيّن الموضع الحالي داخل الدفق. |
| [setPosition(long value)](#setPosition-long-) | يحصل أو يعيّن الموضع الحالي داخل الدفق. |
| [getStream()](#getStream--) | يحصل على دفق البيانات. |
| [isStreamDisposedOnClose()](#isStreamDisposedOnClose--) | يحصل على قيمة تشير إلى ما إذا كان هذا الدفق يتم التخلص منه عند الإغلاق. |
| [getLength()](#getLength--) | يحصل أو يعيّن طول الدفق بالبايت. |
| [setLength(long value)](#setLength-long-) | يحصل أو يعيّن طول الدفق بالبايت. |
| [canRead()](#canRead--) | يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم القراءة. |
| [canSeek()](#canSeek--) | يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم السعي. |
| [canWrite()](#canWrite--) | يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم الكتابة. |
| [flush()](#flush--) | يمسح جميع المخازن المؤقتة لهذا الدفق ويتسبب في كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي. |
| [write(byte[] bytes)](#write-byte---) | يكتب جميع البايتات المحددة إلى الدفق. |
| [writeByte(byte value)](#writeByte-byte-) | يكتب بايتًا إلى الموضع الحالي في الدفق ويقدم الموضع داخل الدفق بمقدار بايت واحد. |
| [read(byte[] bytes)](#read-byte---) | يقرأ بايتات لملء مخزن البايتات المحدد. |
| [toBytes()](#toBytes--) | يحول بيانات الدفق إلى مصفوفة `byte`. |
| [toBytes(long position, long bytesCount)](#toBytes-long-long-) | يحول بيانات الدفق إلى مصفوفة `byte`. |
| [read(byte[] buffer, int offset, int count)](#read-byte---int-int-) | يقرأ تسلسلًا من البايتات من الدفق الحالي ويُحَرِّك الموضع داخل الدفق بعدد البايتات المقروءة. |
| [readByte()](#readByte--) | يقرأ بايتًا واحدًا من الدفق ويُحَرِّك الموضع داخل الدفق بايتًا واحدًا، أو يُرجِع -1 إذا كان عند نهاية الدفق. |
| [seek(long offset, int origin)](#seek-long-int-) | يضبط الموضع داخل الدفق الحالي. |
| [seekBegin()](#seekBegin--) | يضبط موضع الدفق إلى بداية الدفق. |
| [write(byte[] buffer, int offset, int count)](#write-byte---int-int-) | يكتب تسلسلًا من البايتات إلى الدفق الحالي ويُحَرِّك الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة. |
| [save(OutputStream destinationStream)](#save-java.io.OutputStream-) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [save(OutputStream destinationStream, int bufferSize)](#save-java.io.OutputStream-int-) | يحفظ (ينسخ) جميع بيانات الدفق إلى الدفق المحدد. |
| [save(OutputStream destinationStream, int bufferSize, long length)](#save-java.io.OutputStream-int-long-) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [save(String filePath)](#save-java.lang.String-) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [save(String filePath, int bufferSize)](#save-java.lang.String-int-) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [save(String filePath, int bufferSize, long length)](#save-java.lang.String-int-long-) | يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. |
| [writeTo(StreamContainer streamContainer)](#writeTo-com.aspose.imaging.StreamContainer-) | ينسخ البيانات المحتواة إلى `StreamContainer` آخر. |
| [writeTo(StreamContainer streamContainer, long length)](#writeTo-com.aspose.imaging.StreamContainer-long-) | ينسخ البيانات المحتواة إلى `StreamContainer` آخر. |
### StreamContainer(InputStream stream) {#StreamContainer-java.io.InputStream-}
```
public StreamContainer(InputStream stream)
```


يُنشئ مثيلًا جديدًا من الفئة `StreamContainer`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | المجرى. |

### StreamContainer(System.IO.Stream stream) {#StreamContainer-com.aspose.ms.System.IO.Stream-}
```
public StreamContainer(System.IO.Stream stream)
```


يُنشئ مثيلًا جديدًا من الفئة `StreamContainer`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | com.aspose.ms.System.IO.Stream | المجرى. |

### StreamContainer(InputStream stream, boolean disposeStream) {#StreamContainer-java.io.InputStream-boolean-}
```
public StreamContainer(InputStream stream, boolean disposeStream)
```


يُنشئ مثيلًا جديدًا من الفئة `StreamContainer`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | دفق البيانات. |
| disposeStream | boolean | إذا تم تعيينه إلى `true` سيتم التخلص من الدفق عندما يتم التخلص من الحاوية. |

### StreamContainer(System.IO.Stream stream, boolean disposeStream) {#StreamContainer-com.aspose.ms.System.IO.Stream-boolean-}
```
public StreamContainer(System.IO.Stream stream, boolean disposeStream)
```


يُنشئ مثيلًا جديدًا من الفئة `StreamContainer`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | com.aspose.ms.System.IO.Stream | دفق البيانات. |
| disposeStream | boolean | إذا تم تعيينه إلى `true` سيتم التخلص من الدفق عندما يتم التخلص من الحاوية. |

### READ_WRITE_BYTES_COUNT {#READ-WRITE-BYTES-COUNT}
```
public static final int READ_WRITE_BYTES_COUNT
```


يحدد عدد البايتات للقراءة والكتابة عند القراءة المتسلسلة.

### to_Stream(StreamContainer streamContainer) {#to-Stream-com.aspose.imaging.StreamContainer-}
```
public static System.IO.Stream to_Stream(StreamContainer streamContainer)
```


يُجري تحويلًا صريحًا من `com.aspose.imaging.StreamContainer` إلى `System.IO.Stream`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | حاوية الدفق. |

**Returns:**
com.aspose.ms.System.IO.Stream - نتيجة التحويل.
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن.

القيمة: الكائن الذي يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن.

**Returns:**
java.lang.Object
### getPosition() {#getPosition--}
```
public long getPosition()
```


يحصل أو يعيّن الموضع الحالي داخل الدفق. تمثل هذه القيمة الإزاحة من موضع بدء الدفق الذي تم تمريره في مُنشئ StreamContainer.

القيمة: موضع الدفق الحالي.

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


يحصل أو يعيّن الموضع الحالي داخل الدفق. تمثل هذه القيمة الإزاحة من موضع بدء الدفق الذي تم تمريره في مُنشئ StreamContainer.

القيمة: موضع الدفق الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### getStream() {#getStream--}
```
public InputStream getStream()
```


يحصل على دفق البيانات.

القيمة: دفق البيانات.

**Returns:**
java.io.InputStream
### isStreamDisposedOnClose() {#isStreamDisposedOnClose--}
```
public boolean isStreamDisposedOnClose()
```


يحصل على قيمة تشير إلى ما إذا كان هذا الدفق يتم التخلص منه عند الإغلاق.

القيمة: `true` إذا تم التخلص من الدفق عند الإغلاق؛ وإلا `false`.

**Returns:**
boolean
### getLength() {#getLength--}
```
public long getLength()
```


يحصل أو يعيّن طول الدفق بالبايت. هذه القيمة أقل من Stream\#getLength().getLength() بمقدار موضع بدء الدفق الذي تم تمريره في مُنشئ StreamContainer.

القيمة: طول الدفق.

**Returns:**
long
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


يحصل أو يعيّن طول الدفق بالبايت. هذه القيمة أقل من Stream\#getLength().getLength() بمقدار موضع بدء الدفق الذي تم تمريره في مُنشئ StreamContainer.

القيمة: طول الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### canRead() {#canRead--}
```
public boolean canRead()
```


يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم القراءة.

القيمة: `true` إذا كان الدفق يدعم القراءة؛ وإلا `false`.

**Returns:**
boolean
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم السعي.

القيمة: `true` إذا كان الدفق يدعم السعي؛ وإلا `false`.

**Returns:**
boolean
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم الكتابة.

القيمة: `true` إذا كان الدفق يدعم الكتابة؛ وإلا `false`.

**Returns:**
boolean
### flush() {#flush--}
```
public void flush()
```


يمسح جميع المخازن المؤقتة لهذا الدفق ويتسبب في كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي.

### write(byte[] bytes) {#write-byte---}
```
public void write(byte[] bytes)
```


يكتب جميع البايتات المحددة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بايتات | byte[] | البايتات التي سيتم كتابتها. |

### writeByte(byte value) {#writeByte-byte-}
```
public void writeByte(byte value)
```


يكتب بايتًا إلى الموضع الحالي في الدفق ويقدم الموضع داخل الدفق بمقدار بايت واحد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte | البايت الذي سيتم كتابته إلى الدفق. |

### read(byte[] bytes) {#read-byte---}
```
public int read(byte[] bytes)
```


يقرأ بايتات لملء مخزن البايتات المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| بايتات | byte[] | البايتات لتعبئتها. |

**Returns:**
int - عدد البايتات المقروءة. يمكن أن تكون هذه القيمة أقل من عدد البايتات في المخزن المؤقت إذا لم يكن هناك ما يكفي من البايتات في الدفق.
### toBytes() {#toBytes--}
```
public byte[] toBytes()
```


يحول بيانات الدفق إلى مصفوفة `byte`.

**Returns:**
byte[] - بيانات الدفق محوّلة إلى مصفوفة `byte`.
### toBytes(long position, long bytesCount) {#toBytes-long-long-}
```
public byte[] toBytes(long position, long bytesCount)
```


يحول بيانات الدفق إلى مصفوفة `byte`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع لبدء قراءة البايتات منه. |
| bytesCount | long | عدد البايتات للقراءة. |

**Returns:**
byte[] - بيانات الدفق محوّلة إلى مصفوفة `byte`.
### read(byte[] buffer, int offset, int count) {#read-byte---int-int-}
```
public int read(byte[] buffer, int offset, int count)
```


يقرأ تسلسلًا من البايتات من الدفق الحالي ويُحَرِّك الموضع داخل الدفق بعدد البايتات المقروءة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| buffer | byte[] | مصفوفة من البايتات. عندما تعود هذه الطريقة، يحتوي buffer على مصفوفة البايت المحددة مع القيم بين `offset` و (`offset` + `count` - 1) المستبدلة بالبايتات المقروءة من المصدر الحالي. |
| offset | int | الإزاحة الصفرية للبايت في `buffer` التي يبدأ عندها تخزين البيانات المقروءة من الدفق الحالي. |
| count | int | الحد الأقصى لعدد البايتات التي سيتم قراءتها من الدفق الحالي. |

**Returns:**
int - إجمالي عدد البايتات المقروءة إلى buffer. قد تكون هذه أقل من عدد البايتات المطلوبة إذا لم تكن تلك البايتات متاحة حالياً، أو صفر (0) إذا تم الوصول إلى نهاية الدفق.
### readByte() {#readByte--}
```
public int readByte()
```


يقرأ بايتًا واحدًا من الدفق ويُحَرِّك الموضع داخل الدفق بايتًا واحدًا، أو يُرجِع -1 إذا كان عند نهاية الدفق.

**Returns:**
int - البايت غير الموقع محوّل إلى Int32، أو -1 إذا كان عند نهاية الدفق.
### seek(long offset, int origin) {#seek-long-int-}
```
public long seek(long offset, int origin)
```


يضبط الموضع داخل الدفق الحالي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| offset | long | إزاحة بايت نسبية إلى معامل `origin`. تمثل هذه القيمة الإزاحة من موضع بدء الدفق الذي تم تمريره في مُنشئ StreamContainer. |
| origin | int | قيمة من النوع `System.IO.SeekOrigin` تشير إلى نقطة المرجع المستخدمة للحصول على الموضع الجديد. |

**Returns:**
long - الموضع الجديد داخل الدفق الحالي.
### seekBegin() {#seekBegin--}
```
public void seekBegin()
```


يضبط موضع الدفق إلى بداية الدفق. تمثل هذه القيمة الإزاحة من موضع بدء الدفق الذي تم تمريره في مُنشئ StreamContainer.

### write(byte[] buffer, int offset, int count) {#write-byte---int-int-}
```
public void write(byte[] buffer, int offset, int count)
```


يكتب تسلسلًا من البايتات إلى الدفق الحالي ويُحَرِّك الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| buffer | byte[] | مصفوفة من البايتات. تقوم هذه الطريقة بنسخ `count` بايت من `buffer` إلى الدفق الحالي. |
| offset | int | الإزاحة الصفرية للبايت في `buffer` التي يبدأ عندها نسخ البايتات إلى الدفق الحالي. |
| count | int | عدد البايتات التي سيتم كتابتها إلى الدفق الحالي. |

### save(OutputStream destinationStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destinationStream)
```


يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي `ReadWriteBytesCount` وقيمة الدفق `Length`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | الدفق لحفظ البيانات إليه. |

### save(OutputStream destinationStream, int bufferSize) {#save-java.io.OutputStream-int-}
```
public void save(OutputStream destinationStream, int bufferSize)
```


يحفظ (ينسخ) جميع بيانات الدفق إلى الدفق المحدد. يستخدم قيمة الدفق `Length`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | الدفق لحفظ البيانات إليه. |
| bufferSize | int | المخزن المؤقت. |

### save(OutputStream destinationStream, int bufferSize, long length) {#save-java.io.OutputStream-int-long-}
```
public void save(OutputStream destinationStream, int bufferSize, long length)
```


يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| destinationStream | java.io.OutputStream | الدفق لحفظ البيانات إليه. |
| bufferSize | int | حجم المخزن المؤقت. يتم استخدام القيمة الافتراضية `ReadWriteBytesCount`. |
| length | long | طول بيانات الدفق للنسخ. بشكل افتراضي، يتم تعيين الطول إلى القيمة `Length`. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم حجم المخزن المؤقت الافتراضي `ReadWriteBytesCount` وقيمة الدفق `Length`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف لحفظ بيانات الدفق إليه. |

### save(String filePath, int bufferSize) {#save-java.lang.String-int-}
```
public void save(String filePath, int bufferSize)
```


يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد. يستخدم قيمة الدفق `Length`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف لحفظ بيانات الدفق إليه. |
| bufferSize | int | حجم المخزن المؤقت. يتم استخدام القيمة الافتراضية `ReadWriteBytesCount`. |

### save(String filePath, int bufferSize, long length) {#save-java.lang.String-int-long-}
```
public void save(String filePath, int bufferSize, long length)
```


يحفظ (ينسخ) بيانات الدفق إلى الدفق المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePath | java.lang.String | مسار الملف لحفظ بيانات الدفق إليه. |
| bufferSize | int | حجم المخزن المؤقت. يتم استخدام القيمة الافتراضية `ReadWriteBytesCount`. |
| length | long | طول بيانات الدفق للنسخ. بشكل افتراضي، يتم تعيين الطول إلى القيمة `Length`. |

### writeTo(StreamContainer streamContainer) {#writeTo-com.aspose.imaging.StreamContainer-}
```
public void writeTo(StreamContainer streamContainer)
```


ينسخ البيانات المحتواة إلى `StreamContainer` آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | حاوية الدفق للنسخ إليها. |

### writeTo(StreamContainer streamContainer, long length) {#writeTo-com.aspose.imaging.StreamContainer-long-}
```
public void writeTo(StreamContainer streamContainer, long length)
```


ينسخ البيانات المحتواة إلى `StreamContainer` آخر.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | حاوية الدفق للنسخ إليها. |
| length | long | عدد البايتات للكتابة. |

