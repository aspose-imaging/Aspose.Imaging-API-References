---
title: "TiffStreamReader"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تيار tiff لمعالجة تنسيق ملف tiff ذو النهاية الصغيرة."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker
```
public class TiffStreamReader extends TiffStreamSeeker
```

تيار tiff لمعالجة تنسيق ملف tiff ذو النهاية الصغيرة.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | ينشئ مثيلاً جديداً من الفئة `TiffStreamReader`. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | ينشئ مثيلاً جديداً من الفئة `TiffStreamReader`. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | ينشئ مثيلاً جديداً من الفئة `TiffStreamReader`. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.imaging.StreamContainer-) | ينشئ مثيلاً جديداً من الفئة `TiffStreamReader`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLength()](#getLength--) | يحصل على طول القارئ. |
| [getThrowExceptions()](#getThrowExceptions--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الاستثناءات تُرمى عند معالجة البيانات غير الصحيحة (القراءة أو الكتابة إلى التدفق). |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الاستثناءات تُرمى عند معالجة البيانات غير الصحيحة (القراءة أو الكتابة إلى التدفق). |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | يقرأ مصفوفة من قيم البايت من التدفق. |
| [readBytes(long position, long count)](#readBytes-long-long-) | يقرأ مصفوفة من قيم البايت غير الموقعة من التدفق. |
| [readDouble(long position)](#readDouble-long-) | يقرأ قيمة مزدوجة واحدة من التدفق. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | يقرأ مصفوفة من القيم المزدوجة من التدفق. |
| [readFloat(long position)](#readFloat-long-) | يقرأ قيمة عائمة واحدة من التدفق. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | يقرأ مصفوفة من القيم العائمة من التدفق. |
| [readRational(long position)](#readRational-long-) | يقرأ قيمة عدد نسبي واحد من التدفق. |
| [readSRational(long position)](#readSRational-long-) | يقرأ قيمة عدد نسبي موقّع واحد من التدفق. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | يقرأ مصفوفة من القيم النسبية من التدفق. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | يقرأ مصفوفة من القيم النسبية الموقعة من التدفق. |
| [readSByte(long position)](#readSByte-long-) | يقرأ بيانات بايت موقعة من التدفق. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | يقرأ مصفوفة من قيم البايت الموقعة من التدفق. |
| [readSInt(long position)](#readSInt-long-) | يقرأ قيمة عدد صحيح موقّع من التدفق. |
| [readSIntArray(long position, long count)](#readSIntArray-long-long-) | يقرأ مصفوفة من قيم الأعداد الصحيحة الموقعة من التدفق. |
| [readSShort(long position)](#readSShort-long-) | يقرأ قيمة قصير موقّع من التدفق. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | يقرأ مصفوفة من قيم القصير الموقعة من التدفق. |
| [readUInt(long position)](#readUInt-long-) | يقرأ قيمة عدد صحيح غير موقّع من التدفق. |
| [readUIntArray(long position, long count)](#readUIntArray-long-long-) | يقرأ مصفوفة من قيم الأعداد الصحيحة غير الموقعة من التدفق. |
| [readUShort(long position)](#readUShort-long-) | يقرأ قيمة قصير غير موقّع من التدفق. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | يقرأ مصفوفة من قيم الأعداد الصحيحة غير الموقعة من التدفق. |
| [readLong(long position)](#readLong-long-) | يقرأ قيمة عدد طويل غير موقّع من التدفق. |
| [readLongArray(long position, long count)](#readLongArray-long-long-) | يقرأ مصفوفة من قيم الأعداد الطويلة من التدفق. |
| [readULong(long position)](#readULong-long-) | يقرأ قيمة عدد طويل غير موقّع من التدفق. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | يقرأ مصفوفة من قيم الأعداد الطويلة غير الموقعة من التدفق. |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | يحوّل البيانات الأساسية إلى حاوية التدفق. |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


ينشئ مثيلاً جديداً من الفئة `TiffStreamReader`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | byte[] | بيانات مصفوفة البايت. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


ينشئ مثيلاً جديداً من الفئة `TiffStreamReader`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | byte[] | بيانات مصفوفة البايت. |
| startIndex | int | فهرس البداية في `data`. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


ينشئ مثيلاً جديداً من الفئة `TiffStreamReader`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | byte[] | بيانات مصفوفة البايت. |
| startIndex | int | فهرس البداية في `data`. |
| dataLength | int | طول البيانات. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.imaging.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


ينشئ مثيلاً جديداً من الفئة `TiffStreamReader`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | حاوية الدفق. |

### getLength() {#getLength--}
```
public long getLength()
```


يحصل على طول القارئ.

القيمة: طول القارئ.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الاستثناءات تُرمى عند معالجة البيانات غير الصحيحة (القراءة أو الكتابة إلى التدفق).

القيمة: `true` إذا تم رمي الاستثناءات عند معالجة البيانات غير الصحيحة؛ وإلا، يتم تجاهل حالات الخطأ بصمت.

**Returns:**
boolean
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الاستثناءات تُرمى عند معالجة البيانات غير الصحيحة (القراءة أو الكتابة إلى التدفق).

القيمة: `true` إذا تم رمي الاستثناءات عند معالجة البيانات غير الصحيحة؛ وإلا، يتم تجاهل حالات الخطأ بصمت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


يقرأ مصفوفة من قيم البايت من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مصفوفة | byte[] | المصفوفة للتعبئة. |
| arrayIndex | int | فهرس المصفوفة للبدء بوضع القيم. |
| position | long | موضع الدفق للقراءة منه. |
| count | long | عدد العناصر للقراءة. |

**Returns:**
long - مصفوفة قيم البايت.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


يقرأ مصفوفة من قيم البايت غير الموقعة من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
byte[] - مصفوفة قيم البايت غير الموقعة.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


يقرأ قيمة مزدوجة واحدة من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
double - القيمة المزدوجة المفردة.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


يقرأ مصفوفة من القيم المزدوجة من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
double[] - مصفوفة قيم مزدوجة.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


يقرأ قيمة عائمة واحدة من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
float - القيمة العائمة المفردة.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


يقرأ مصفوفة من القيم العائمة من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
float[] - مصفوفة قيم عائمة.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


يقرأ قيمة عدد نسبي واحد من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The rational number.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


يقرأ قيمة عدد نسبي موقّع واحد من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - The signed rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


يقرأ مصفوفة من القيم النسبية من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - مصفوفة القيم النسبية.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


يقرأ مصفوفة من القيم النسبية الموقعة من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffSRational[] - مصفوفة القيم النسبية الموقعة.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


يقرأ بيانات بايت موقعة من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
byte - قيمة البايت الموقعة.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


يقرأ مصفوفة من قيم البايت الموقعة من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
byte[] - مصفوفة قيم البايت الموقعة.
### readSInt(long position) {#readSInt-long-}
```
public int readSInt(long position)
```


يقرأ قيمة عدد صحيح موقّع من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
int - قيمة عدد صحيح موقّع.
### readSIntArray(long position, long count) {#readSIntArray-long-long-}
```
public int[] readSIntArray(long position, long count)
```


يقرأ مصفوفة من قيم الأعداد الصحيحة الموقعة من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
int[] - مصفوفة قيم عدد صحيح موقعة.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


يقرأ قيمة قصير موقّع من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
short - قيمة قصير موقّعة.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


يقرأ مصفوفة من قيم القصير الموقعة من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
short[] - مصفوفة قيم قصير موقعة.
### readUInt(long position) {#readUInt-long-}
```
public long readUInt(long position)
```


يقرأ قيمة عدد صحيح غير موقّع من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
long - قيمة عدد صحيح غير موقّع.
### readUIntArray(long position, long count) {#readUIntArray-long-long-}
```
public long[] readUIntArray(long position, long count)
```


يقرأ مصفوفة من قيم الأعداد الصحيحة غير الموقعة من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
long[] - مصفوفة قيم عدد صحيح غير موقعة.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


يقرأ قيمة قصير غير موقّع من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
int - قيمة قصيرة غير موقعة.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


يقرأ مصفوفة من قيم الأعداد الصحيحة غير الموقعة من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
int[] - مصفوفة من القيم الصحيحة غير الموقعة.
### readLong(long position) {#readLong-long-}
```
public final long readLong(long position)
```


يقرأ قيمة عدد طويل غير موقّع من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
long - قيمة قصيرة غير موقعة.
### readLongArray(long position, long count) {#readLongArray-long-long-}
```
public final long[] readLongArray(long position, long count)
```


يقرأ مصفوفة من قيم الأعداد الطويلة من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
long[] - مصفوفة ulong.
### readULong(long position) {#readULong-long-}
```
public final long readULong(long position)
```


يقرأ قيمة عدد طويل غير موقّع من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
long - قيمة قصيرة غير موقعة.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public final long[] readULongArray(long position, long count)
```


يقرأ مصفوفة من قيم الأعداد الطويلة غير الموقعة من التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
long[] - مصفوفة ulong.
### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


يحوّل البيانات الأساسية إلى حاوية التدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startPosition | long | موضع البداية للبدء في التحويل منه. |

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The `StreamContainer` with converted data.
