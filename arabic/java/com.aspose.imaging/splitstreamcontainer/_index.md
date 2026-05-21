---
title: "SplitStreamContainer"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يمثل حاوية تدفق مقسمة تحتوي على التدفق وتوفر روتينات معالجة التدفق."
type: docs
weight: 108
url: /ar/java/com.aspose.imaging/splitstreamcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.StreamContainer](../../com.aspose.imaging/streamcontainer)
```
public class SplitStreamContainer extends StreamContainer
```

يمثل حاوية تدفق مقسمة تحتوي على التدفق وتوفر روتينات معالجة التدفق.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [SplitStreamContainer(InputStream stream)](#SplitStreamContainer-java.io.InputStream-) | يُنشئ مثيلاً جديدًا من الفئة `SplitStreamContainer`. |
| [SplitStreamContainer(InputStream stream, boolean disposeStream)](#SplitStreamContainer-java.io.InputStream-boolean-) | يُنشئ مثيلاً جديدًا من الفئة `SplitStreamContainer`. |
| [SplitStreamContainer(StreamContainer stream, boolean disposeStream)](#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-) | يُنشئ مثيلاً جديدًا من الفئة `SplitStreamContainer`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |
| [getPosition()](#getPosition--) | يحصل على الموضع الحالي داخل الدفق. |
| [setPosition(long value)](#setPosition-long-) | يضبط الموضع الحالي داخل الدفق. |
| [getLength()](#getLength--) | يحصل على طول الدفق بالبايتات. |
| [setLength(long value)](#setLength-long-) | يضبط طول الدفق بالبايتات. |
| [canRead()](#canRead--) | يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم القراءة. |
| [canSeek()](#canSeek--) | يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم السعي. |
| [canWrite()](#canWrite--) | يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم الكتابة. |
| [insert(int position, StreamContainer stream, boolean disposeStream)](#insert-int-com.aspose.imaging.StreamContainer-boolean-) | يدرج حاوية الدفق في الموضع المحدد. |
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
### SplitStreamContainer(InputStream stream) {#SplitStreamContainer-java.io.InputStream-}
```
public SplitStreamContainer(InputStream stream)
```


يُنشئ مثيلاً جديدًا من الفئة `SplitStreamContainer`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | المجرى. |

### SplitStreamContainer(InputStream stream, boolean disposeStream) {#SplitStreamContainer-java.io.InputStream-boolean-}
```
public SplitStreamContainer(InputStream stream, boolean disposeStream)
```


يُنشئ مثيلاً جديدًا من الفئة `SplitStreamContainer`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| التدفق | java.io.InputStream | دفق البيانات. |
| disposeStream | boolean | إذا تم تعيينه إلى `true` سيتم التخلص من الدفق عندما يتم التخلص من الحاوية. |

### SplitStreamContainer(StreamContainer stream, boolean disposeStream) {#SplitStreamContainer-com.aspose.imaging.StreamContainer-boolean-}
```
public SplitStreamContainer(StreamContainer stream, boolean disposeStream)
```


يُنشئ مثيلاً جديدًا من الفئة `SplitStreamContainer`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | حاوية الدفق. |
| disposeStream | boolean | إذا تم تعيينه إلى `true` يتخلص من الدفق. |

### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن.

**Returns:**
java.lang.Object - الكائن الذي يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن.
### getPosition() {#getPosition--}
```
public long getPosition()
```


يحصل على الموضع الحالي داخل الدفق. تمثل هذه القيمة الإزاحة من موضع الدفق الابتدائي الممرّر في مُنشئ StreamContainer.

**Returns:**
long - موضع الدفق الحالي.
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


يضبط الموضع الحالي داخل الدفق. تمثل هذه القيمة الإزاحة من موضع الدفق الابتدائي الممرّر في مُنشئ StreamContainer.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long | موضع الدفق الحالي. |

### getLength() {#getLength--}
```
public long getLength()
```


يحصل على طول الدفق بالبايتات. هذه القيمة أقل من `System.IO.Stream.Length` بمقدار موضع الدفق الابتدائي الممرّر في مُنشئ StreamContainer.

**Returns:**
long - طول الدفق.
### setLength(long value) {#setLength-long-}
```
public void setLength(long value)
```


يضبط طول الدفق بالبايتات. هذه القيمة أقل من `System.IO.Stream.Length` بمقدار موضع الدفق الابتدائي الممرّر في مُنشئ StreamContainer.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long | طول الدفق. |

### canRead() {#canRead--}
```
public boolean canRead()
```


يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم القراءة.

**Returns:**
boolean - `true` إذا كان الدفق يدعم القراءة؛ وإلا `false`.
### canSeek() {#canSeek--}
```
public boolean canSeek()
```


يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم السعي.

**Returns:**
boolean - `true` إذا كان الدفق يدعم السعي؛ وإلا `false`.
### canWrite() {#canWrite--}
```
public boolean canWrite()
```


يحصل على قيمة تشير إلى ما إذا كان الدفق يدعم الكتابة.

**Returns:**
boolean - `true` إذا كان الدفق يدعم الكتابة؛ وإلا `false`.
### insert(int position, StreamContainer stream, boolean disposeStream) {#insert-int-com.aspose.imaging.StreamContainer-boolean-}
```
public void insert(int position, StreamContainer stream, boolean disposeStream)
```


يدرج حاوية الدفق في الموضع المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | int | الموضع الذي سيتم الإدراج إليه. |
| stream | [StreamContainer](../../com.aspose.imaging/streamcontainer) | حاوية الدفق التي سيتم الإدراج فيها. |
| disposeStream | boolean | إذا تم تعيينه إلى `true` يتخلص من الدفق. |

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

