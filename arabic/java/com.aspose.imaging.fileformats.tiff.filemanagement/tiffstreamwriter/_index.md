---
title: "TiffStreamWriter"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "كاتب تيار Tiff."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter extends TiffStreamSeeker implements ISynchronizable
```

كاتب تيار Tiff.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.imaging.StreamContainer-) | ينشئ مثيلاً جديداً من الفئة `TiffStreamWriter`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | يحصل على كائن يمكن استخدامه لمزامنة الوصول إلى المورد المتزامن. |
| [getPosition()](#getPosition--) | يسترجع أو يعيّن موضع الدفق. |
| [setPosition(long value)](#setPosition-long-) | يسترجع أو يعيّن موضع الدفق. |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | يكتب البيانات المحددة. |
| [write(byte[] data)](#write-byte---) | يكتب البيانات المحددة. |
| [writeDouble(double data)](#writeDouble-double-) | يكتب قيمة مزدوجة واحدة إلى الدفق. |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | يكتب مصفوفة من القيم المزدوجة إلى الدفق. |
| [writeFloat(float data)](#writeFloat-float-) | يكتب قيمة عائمة واحدة إلى الدفق. |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | يكتب مصفوفة من القيم العائمة إلى الدفق. |
| [writeRational(TiffRational data)](#writeRational-com.aspose.imaging.fileformats.tiff.TiffRational-) | يكتب قيمة عدد نسبي مفردة إلى الدفق. |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.imaging.fileformats.tiff.TiffSRational-) | يكتب قيمة عدد نسبي موقع مفردة إلى الدفق. |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.imaging.fileformats.tiff.TiffRational---) | يكتب مصفوفة من القيم العددية النسبية غير الموقعة إلى الدفق. |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.imaging.fileformats.tiff.TiffSRational---) | يكتب مصفوفة من القيم العددية النسبية الموقعة إلى الدفق. |
| [writeSByte(byte data)](#writeSByte-byte-) | يكتب قيمة بايت موقعة مفردة إلى الدفق. |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | يكتب مصفوفة من قيم البايت الموقعة إلى الدفق. |
| [writeIntArray(int[] data)](#writeIntArray-int---) | يكتب مصفوفة من قيم الأعداد الصحيحة إلى الدفق. |
| [writeSShort(short data)](#writeSShort-short-) | يكتب قيمة short مفردة إلى الدفق. |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | يكتب مصفوفة من قيم short إلى الدفق. |
| [writeSInt(int data)](#writeSInt-int-) | يكتب قيمة integer مفردة إلى الدفق. |
| [writeUByte(byte data)](#writeUByte-byte-) | يكتب قيمة byte مفردة إلى الدفق. |
| [writeUInt(long data)](#writeUInt-long-) | يكتب قيمة integer غير موقعة مفردة إلى الدفق. |
| [writeUIntArray(long[] data)](#writeUIntArray-long---) | يكتب مصفوفة من قيم integer غير موقعة إلى الدفق. |
| [writeUShort(int data)](#writeUShort-int-) | يكتب قيمة short غير موقعة مفردة إلى الدفق. |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | يكتب مصفوفة من قيم short غير موقعة إلى الدفق. |
| [writeSLong(long data)](#writeSLong-long-) | يكتب مصفوفة من قيم long موقعة إلى الدفق. |
| [writeSLongArray(long[] data)](#writeSLongArray-long---) | يكتب مصفوفة من قيم long موقعة إلى الدفق. |
| [writeULong(long data)](#writeULong-long-) | يكتب مصفوفة من قيم long غير موقعة إلى الدفق. |
| [writeULongArray(long[] data)](#writeULongArray-long---) | يكتب مصفوفة من قيم long غير موقعة إلى الدفق. |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.imaging.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


ينشئ مثيلاً جديداً من الفئة `TiffStreamWriter`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | كاتب الدفق. |

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


يسترجع أو يعيّن موضع الدفق.

القيمة: موضع الدفق.

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


يسترجع أو يعيّن موضع الدفق.

القيمة: موضع الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | long |  |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


يكتب البيانات المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | byte[] | البيانات للكتابة. |
| offset | int | إزاحة البيانات. |
| dataLength | int | طول البيانات للكتابة. |

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


يكتب البيانات المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | byte[] | البيانات للكتابة. |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


يكتب قيمة مزدوجة واحدة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | double | القيمة للكتابة. |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


يكتب مصفوفة من القيم المزدوجة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | double[] | المصفوفة للكتابة. |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


يكتب قيمة عائمة واحدة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | float | القيمة للكتابة. |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


يكتب مصفوفة من القيم العائمة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | float[] | المصفوفة للكتابة. |

### writeRational(TiffRational data) {#writeRational-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


يكتب قيمة عدد نسبي مفردة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | القيمة للكتابة. |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


يكتب قيمة عدد نسبي موقع مفردة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) | القيمة للكتابة. |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


يكتب مصفوفة من القيم العددية النسبية غير الموقعة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | المصفوفة للكتابة. |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.imaging.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


يكتب مصفوفة من القيم العددية النسبية الموقعة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffsrational) | المصفوفة للكتابة. |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


يكتب قيمة بايت موقعة مفردة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | byte | القيمة للكتابة. |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


يكتب مصفوفة من قيم البايت الموقعة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | byte[] | المصفوفة للكتابة. |

### writeIntArray(int[] data) {#writeIntArray-int---}
```
public void writeIntArray(int[] data)
```


يكتب مصفوفة من قيم الأعداد الصحيحة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | int[] | المصفوفة للكتابة. |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


يكتب قيمة short مفردة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | short | القيمة للكتابة. |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


يكتب مصفوفة من قيم short إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | short[] | المصفوفة للكتابة. |

### writeSInt(int data) {#writeSInt-int-}
```
public void writeSInt(int data)
```


يكتب قيمة integer مفردة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | int | القيمة للكتابة. |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


يكتب قيمة byte مفردة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | byte | القيمة للكتابة. |

### writeUInt(long data) {#writeUInt-long-}
```
public void writeUInt(long data)
```


يكتب قيمة integer غير موقعة مفردة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | long | القيمة للكتابة. |

### writeUIntArray(long[] data) {#writeUIntArray-long---}
```
public void writeUIntArray(long[] data)
```


يكتب مصفوفة من قيم integer غير موقعة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | long[] | المصفوفة للكتابة. |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


يكتب قيمة short غير موقعة مفردة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | int | القيمة للكتابة. |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


يكتب مصفوفة من قيم short غير موقعة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | int[] | المصفوفة للكتابة. |

### writeSLong(long data) {#writeSLong-long-}
```
public final void writeSLong(long data)
```


يكتب مصفوفة من قيم long موقعة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | long | المصفوفة للكتابة. |

### writeSLongArray(long[] data) {#writeSLongArray-long---}
```
public final void writeSLongArray(long[] data)
```


يكتب مصفوفة من قيم long موقعة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | long[] | المصفوفة للكتابة. |

### writeULong(long data) {#writeULong-long-}
```
public final void writeULong(long data)
```


يكتب مصفوفة من قيم long غير موقعة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | long | المصفوفة للكتابة. |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public final void writeULongArray(long[] data)
```


يكتب مصفوفة من قيم long غير موقعة إلى الدفق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| البيانات | long[] | المصفوفة للكتابة. |

