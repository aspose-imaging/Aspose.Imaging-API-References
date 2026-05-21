---
title: "TiffStreamWriter"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Записыватель потока Tiff."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter extends TiffStreamSeeker implements ISynchronizable
```

Записыватель потока Tiff.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.imaging.StreamContainer-) | Инициализирует новый экземпляр класса `TiffStreamWriter`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getSyncRoot()](#getSyncRoot--) | Получает объект, который может использоваться для синхронизации доступа к синхронизированному ресурсу. |
| [getPosition()](#getPosition--) | Получает или задает позицию потока. |
| [setPosition(long value)](#setPosition-long-) | Получает или задает позицию потока. |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | Записывает указанные данные. |
| [write(byte[] data)](#write-byte---) | Записывает указанные данные. |
| [writeDouble(double data)](#writeDouble-double-) | Записывает одно значение double в поток. |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | Записывает массив значений double в поток. |
| [writeFloat(float data)](#writeFloat-float-) | Записывает одно значение float в поток. |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | Записывает массив значений float в поток. |
| [writeRational(TiffRational data)](#writeRational-com.aspose.imaging.fileformats.tiff.TiffRational-) | Записывает одно рациональное число в поток. |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Записывает одно знаковое рациональное число в поток. |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.imaging.fileformats.tiff.TiffRational---) | Записывает массив беззнаковых рациональных значений в поток. |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.imaging.fileformats.tiff.TiffSRational---) | Записывает массив знаковых рациональных значений в поток. |
| [writeSByte(byte data)](#writeSByte-byte-) | Записывает одно знаковое байтовое значение в поток. |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | Записывает массив знаковых байтовых значений в поток. |
| [writeIntArray(int[] data)](#writeIntArray-int---) | Записывает массив целочисленных значений в поток. |
| [writeSShort(short data)](#writeSShort-short-) | Записывает одно значение типа short в поток. |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | Записывает массив значений типа short в поток. |
| [writeSInt(int data)](#writeSInt-int-) | Записывает одно целочисленное значение в поток. |
| [writeUByte(byte data)](#writeUByte-byte-) | Записывает одно байтовое значение в поток. |
| [writeUInt(long data)](#writeUInt-long-) | Записывает одно беззнаковое целочисленное значение в поток. |
| [writeUIntArray(long[] data)](#writeUIntArray-long---) | Записывает массив беззнаковых целочисленных значений в поток. |
| [writeUShort(int data)](#writeUShort-int-) | Записывает одно беззнаковое значение типа short в поток. |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | Записывает массив беззнаковых значений типа short в поток. |
| [writeSLong(long data)](#writeSLong-long-) | Записывает массив знаковых значений типа long в поток. |
| [writeSLongArray(long[] data)](#writeSLongArray-long---) | Записывает массив знаковых значений типа long в поток. |
| [writeULong(long data)](#writeULong-long-) | Записывает массив беззнаковых значений типа long в поток. |
| [writeULongArray(long[] data)](#writeULongArray-long---) | Записывает массив беззнаковых значений типа long в поток. |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.imaging.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


Инициализирует новый экземпляр класса `TiffStreamWriter`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Записывающий поток. |

### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Получает объект, который может использоваться для синхронизации доступа к синхронизированному ресурсу.

Значение: Объект, который может использоваться для синхронизации доступа к синхронизируемому ресурсу.

**Returns:**
java.lang.Object
### getPosition() {#getPosition--}
```
public long getPosition()
```


Получает или задает позицию потока.

Значение: позиция потока.

**Returns:**
long
### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


Получает или задает позицию потока.

Значение: позиция потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


Записывает указанные данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Данные для записи. |
| offset | int | Смещение данных. |
| dataLength | int | Длина данных для записи. |

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


Записывает указанные данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Данные для записи. |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


Записывает одно значение double в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | double | Значение для записи. |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


Записывает массив значений double в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | double[] | Массив для записи. |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


Записывает одно значение float в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | float | Значение для записи. |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


Записывает массив значений float в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | float[] | Массив для записи. |

### writeRational(TiffRational data) {#writeRational-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


Записывает одно рациональное число в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Значение для записи. |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


Записывает одно знаковое рациональное число в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) | Значение для записи. |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


Записывает массив беззнаковых рациональных значений в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) | Массив для записи. |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.imaging.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


Записывает массив знаковых рациональных значений в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffsrational) | Массив для записи. |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


Записывает одно знаковое байтовое значение в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte | Значение для записи. |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


Записывает массив знаковых байтовых значений в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Массив для записи. |

### writeIntArray(int[] data) {#writeIntArray-int---}
```
public void writeIntArray(int[] data)
```


Записывает массив целочисленных значений в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | int[] | Массив для записи. |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


Записывает одно значение типа short в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | short | Значение для записи. |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


Записывает массив значений типа short в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | short[] | Массив для записи. |

### writeSInt(int data) {#writeSInt-int-}
```
public void writeSInt(int data)
```


Записывает одно целочисленное значение в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | int | Значение для записи. |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


Записывает одно байтовое значение в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte | Значение для записи. |

### writeUInt(long data) {#writeUInt-long-}
```
public void writeUInt(long data)
```


Записывает одно беззнаковое целочисленное значение в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | long | Значение для записи. |

### writeUIntArray(long[] data) {#writeUIntArray-long---}
```
public void writeUIntArray(long[] data)
```


Записывает массив беззнаковых целочисленных значений в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | long[] | Массив для записи. |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


Записывает одно беззнаковое значение типа short в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | int | Значение для записи. |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


Записывает массив беззнаковых значений типа short в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | int[] | Массив для записи. |

### writeSLong(long data) {#writeSLong-long-}
```
public final void writeSLong(long data)
```


Записывает массив знаковых значений типа long в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | long | Массив для записи. |

### writeSLongArray(long[] data) {#writeSLongArray-long---}
```
public final void writeSLongArray(long[] data)
```


Записывает массив знаковых значений типа long в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | long[] | Массив для записи. |

### writeULong(long data) {#writeULong-long-}
```
public final void writeULong(long data)
```


Записывает массив беззнаковых значений типа long в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | long | Массив для записи. |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public final void writeULongArray(long[] data)
```


Записывает массив беззнаковых значений типа long в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | long[] | Массив для записи. |

