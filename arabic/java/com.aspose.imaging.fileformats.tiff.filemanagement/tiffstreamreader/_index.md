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
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | يُنشئ مثيلاً جديداً من الفئة `TiffStreamReader`. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | يُنشئ مثيلاً جديداً من الفئة `TiffStreamReader`. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | يُنشئ مثيلاً جديداً من الفئة `TiffStreamReader`. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.imaging.StreamContainer-) | يُنشئ مثيلاً جديداً من الفئة `TiffStreamReader`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getLength()](#getLength--) | يحصل على طول القارئ. |
| [getThrowExceptions()](#getThrowExceptions--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الاستثناءات تُرمى عند معالجة البيانات غير الصحيحة (القراءة أو الكتابة إلى الدفق). |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الاستثناءات تُرمى عند معالجة البيانات غير الصحيحة (القراءة أو الكتابة إلى الدفق). |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | يقرأ مصفوفة من قيم البايت من الدفق. |
| [readBytes(long position, long count)](#readBytes-long-long-) | يقرأ مصفوفة من قيم البايت غير الموقعة من الدفق. |
| [readDouble(long position)](#readDouble-long-) | يقرأ قيمة مزدوجة واحدة من الدفق. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | يقرأ مصفوفة من القيم المزدوجة من الدفق. |
| [readFloat(long position)](#readFloat-long-) | يقرأ قيمة عائمة واحدة من الدفق. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | يقرأ مصفوفة من القيم العائمة من الدفق. |
| [readRational(long position)](#readRational-long-) | يقرأ قيمة عدد كسرية واحدة من الدفق. |
| [readSRational(long position)](#readSRational-long-) | يقرأ قيمة عدد كسرية موقعة واحدة من الدفق. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | يقرأ مصفوفة من القيم الكسرية من الدفق. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | يقرأ مصفوفة من القيم الكسرية الموقعة من الدفق. |
| [readSByte(long position)](#readSByte-long-) | يقرأ بيانات بايت موقعة من الدفق. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | يقرأ مصفوفة من قيم البايت الموقعة من الدفق. |
| [readSInt(long position)](#readSInt-long-) | يقرأ قيمة عدد صحيح موقعة من الدفق. |
| [readSIntArray(long position, long count)](#readSIntArray-long-long-) | يقرأ مصفوفة من قيم الأعداد الصحيحة الموقعة من الدفق. |
| [readSShort(long position)](#readSShort-long-) | يقرأ قيمة عدد قصير موقعة من الدفق. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | يقرأ مصفوفة من القيم القصيرة الموقعة من الدفق. |
| [readUInt(long position)](#readUInt-long-) | اقرأ قيمة عدد صحيح غير موقعة من الدفق. |
| [readUIntArray(long position, long count)](#readUIntArray-long-long-) | يقرأ مصفوفة من القيم العددية الصحيحة غير الموقعة من الدفق. |
| [readUShort(long position)](#readUShort-long-) | اقرأ قيمة قصيرة غير موقعة من الدفق. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | يقرأ مصفوفة من القيم العددية الصحيحة غير الموقعة من الدفق. |
| [readLong(long position)](#readLong-long-) | اقرأ قيمة طويلة غير موقعة من الدفق. |
| [readLongArray(long position, long count)](#readLongArray-long-long-) | يقرأ مصفوفة من القيم الطويلة من الدفق. |
| [readULong(long position)](#readULong-long-) | اقرأ قيمة طويلة غير موقعة من الدفق. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | يقرأ مصفوفة من القيم غير الموقعة من نوع ulong من الدفق. |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | يحوّل البيانات الأساسية إلى حاوية الدفق. |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


يُنشئ مثيلاً جديداً من الفئة `TiffStreamReader`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | byte[] | بيانات مصفوفة البايت. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


يُنشئ مثيلاً جديداً من الفئة `TiffStreamReader`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | byte[] | بيانات مصفوفة البايت. |
| startIndex | int | فهرس البداية في `data`. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


يُنشئ مثيلاً جديداً من الفئة `TiffStreamReader`.

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


يُنشئ مثيلاً جديداً من الفئة `TiffStreamReader`.

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


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الاستثناءات تُرمى عند معالجة البيانات غير الصحيحة (القراءة أو الكتابة إلى الدفق).

القيمة: `true` إذا تم إلقاء الاستثناءات عند معالجة البيانات غير الصحيحة؛ وإلا، يتم تجاهل ظروف الخطأ بصمت.

**Returns:**
boolean
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


يحصل أو يعيّن قيمة تشير إلى ما إذا كانت الاستثناءات تُرمى عند معالجة البيانات غير الصحيحة (القراءة أو الكتابة إلى الدفق).

القيمة: `true` إذا تم إلقاء الاستثناءات عند معالجة البيانات غير الصحيحة؛ وإلا، يتم تجاهل ظروف الخطأ بصمت.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


يقرأ مصفوفة من قيم البايت من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| مصفوفة | byte[] | المصفوفة للتعبئة. |
| arrayIndex | int | فهرس المصفوفة للبدء بوضع القيم فيه. |
| position | long | موضع الدفق للقراءة منه. |
| count | long | عدد العناصر للقراءة. |

**Returns:**
long - مصفوفة قيم البايت.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


يقرأ مصفوفة من قيم البايت غير الموقعة من الدفق.

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


يقرأ قيمة مزدوجة واحدة من الدفق.

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


يقرأ مصفوفة من القيم المزدوجة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
double[] - مصفوفة القيم المزدوجة.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


يقرأ قيمة عائمة واحدة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
float - القيمة الفاصلة المفردة.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


يقرأ مصفوفة من القيم العائمة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
float[] - مصفوفة القيم الفاصلة.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


يقرأ قيمة عدد كسرية واحدة من الدفق.

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


يقرأ قيمة عدد كسرية موقعة واحدة من الدفق.

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


يقرأ مصفوفة من القيم الكسرية من الدفق.

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


يقرأ مصفوفة من القيم الكسرية الموقعة من الدفق.

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


يقرأ بيانات بايت موقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
byte - قيمة البايت الموقّعة.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


يقرأ مصفوفة من قيم البايت الموقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
byte[] - مصفوفة قيم البايت الموقّعة.
### readSInt(long position) {#readSInt-long-}
```
public int readSInt(long position)
```


يقرأ قيمة عدد صحيح موقعة من الدفق.

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


يقرأ مصفوفة من قيم الأعداد الصحيحة الموقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
int[] - مصفوفة قيم الأعداد الصحيحة الموقّعة.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


يقرأ قيمة عدد قصير موقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
short - قيمة short موقّعة.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


يقرأ مصفوفة من القيم القصيرة الموقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
short[] - مصفوفة قيم short الموقّعة.
### readUInt(long position) {#readUInt-long-}
```
public long readUInt(long position)
```


اقرأ قيمة عدد صحيح غير موقعة من الدفق.

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


يقرأ مصفوفة من القيم العددية الصحيحة غير الموقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
long[] - مصفوفة قيم الأعداد الصحيحة غير الموقّعة.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


اقرأ قيمة قصيرة غير موقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
int - قيمة short غير موقّعة.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


يقرأ مصفوفة من القيم العددية الصحيحة غير الموقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
int[] - مصفوفة قيم الأعداد الصحيحة غير الموقّعة.
### readLong(long position) {#readLong-long-}
```
public final long readLong(long position)
```


اقرأ قيمة طويلة غير موقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
long - قيمة short غير موقّعة.
### readLongArray(long position, long count) {#readLongArray-long-long-}
```
public final long[] readLongArray(long position, long count)
```


يقرأ مصفوفة من القيم الطويلة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
long[] - مصفوفة long.
### readULong(long position) {#readULong-long-}
```
public final long readULong(long position)
```


اقرأ قيمة طويلة غير موقعة من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |

**Returns:**
long - قيمة short غير موقّعة.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public final long[] readULongArray(long position, long count)
```


يقرأ مصفوفة من القيم غير الموقعة من نوع ulong من الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| position | long | الموضع للقراءة منه. |
| count | long | عدد العناصر. |

**Returns:**
long[] - مصفوفة long.
### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


يحوّل البيانات الأساسية إلى حاوية الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startPosition | long | موضع البداية للبدء بالتحويل من. |

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The `StreamContainer` with converted data.
