---
title: "TiffStreamReader"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Поток tiff для обработки файлового формата tiff с порядком байтов little-endian."
type: docs
weight: 13
url: /ru/java/com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader/
---
**Inheritance:**
java.lang.Object, com.aspose.fileformats.fileformats.tiff.filemanagement.TiffStreamSeeker
```
public class TiffStreamReader extends TiffStreamSeeker
```

Поток tiff для обработки файлового формата tiff с порядком байтов little-endian.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | Инициализирует новый экземпляр класса `TiffStreamReader`. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | Инициализирует новый экземпляр класса `TiffStreamReader`. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | Инициализирует новый экземпляр класса `TiffStreamReader`. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.imaging.StreamContainer-) | Инициализирует новый экземпляр класса `TiffStreamReader`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getLength()](#getLength--) | Получает длину читателя. |
| [getThrowExceptions()](#getThrowExceptions--) | Получает или задает значение, указывающее, выбрасываются ли исключения при некорректной обработке данных (чтении или записи в поток). |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | Получает или задает значение, указывающее, выбрасываются ли исключения при некорректной обработке данных (чтении или записи в поток). |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | Читает массив значений байтов из потока. |
| [readBytes(long position, long count)](#readBytes-long-long-) | Читает массив значений беззнаковых байтов из потока. |
| [readDouble(long position)](#readDouble-long-) | Читает одно значение double из потока. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | Читает массив значений double из потока. |
| [readFloat(long position)](#readFloat-long-) | Читает одно значение float из потока. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | Читает массив значений float из потока. |
| [readRational(long position)](#readRational-long-) | Читает одно значение рационального числа из потока. |
| [readSRational(long position)](#readSRational-long-) | Читает одно значение знакового рационального числа из потока. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | Читает массив значений рациональных чисел из потока. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | Читает массив значений знаковых рациональных чисел из потока. |
| [readSByte(long position)](#readSByte-long-) | Читает данные знакового байта из потока. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | Читает массив значений знаковых байтов из потока. |
| [readSInt(long position)](#readSInt-long-) | Читает значение знакового целого числа из потока. |
| [readSIntArray(long position, long count)](#readSIntArray-long-long-) | Читает массив значений знаковых целых чисел из потока. |
| [readSShort(long position)](#readSShort-long-) | Читает значение знакового short из потока. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | Читает массив значений знаковых short из потока. |
| [readUInt(long position)](#readUInt-long-) | Читает значение беззнакового целого числа из потока. |
| [readUIntArray(long position, long count)](#readUIntArray-long-long-) | Читает массив значений беззнаковых целых чисел из потока. |
| [readUShort(long position)](#readUShort-long-) | Читает значение беззнакового short из потока. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | Читает массив значений беззнаковых целых чисел из потока. |
| [readLong(long position)](#readLong-long-) | Читает значение беззнакового long из потока. |
| [readLongArray(long position, long count)](#readLongArray-long-long-) | Читает массив значений long из потока. |
| [readULong(long position)](#readULong-long-) | Читает значение беззнакового long из потока. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | Читает массив значений ulong из потока. |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | Преобразует базовые данные в контейнер потока. |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


Инициализирует новый экземпляр класса `TiffStreamReader`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Данные массива байтов. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


Инициализирует новый экземпляр класса `TiffStreamReader`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Данные массива байтов. |
| startIndex | int | Начальный индекс в `data`. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


Инициализирует новый экземпляр класса `TiffStreamReader`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Данные массива байтов. |
| startIndex | int | Начальный индекс в `data`. |
| dataLength | int | Длина данных. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.imaging.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


Инициализирует новый экземпляр класса `TiffStreamReader`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Контейнер потока. |

### getLength() {#getLength--}
```
public long getLength()
```


Получает длину читателя.

Значение: Длина читателя.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


Получает или задает значение, указывающее, выбрасываются ли исключения при некорректной обработке данных (чтении или записи в поток).

Значение: `true`, если при некорректной обработке данных выбрасываются исключения; иначе условия ошибок игнорируются без сообщения.

**Returns:**
boolean
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


Получает или задает значение, указывающее, выбрасываются ли исключения при некорректной обработке данных (чтении или записи в поток).

Значение: `true`, если при некорректной обработке данных выбрасываются исключения; иначе условия ошибок игнорируются без сообщения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


Читает массив значений байтов из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| массив | byte[] | Массив для заполнения. |
| arrayIndex | int | Индекс массива, с которого начинать помещать значения. |
| позиция | long | Позиция потока для чтения. |
| count | long | Количество элементов для чтения. |

**Returns:**
long - Массив значений байтов.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


Читает массив значений беззнаковых байтов из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
byte[] - Массив беззнаковых значений байтов.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


Читает одно значение double из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |

**Returns:**
double - Одно значение double.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


Читает массив значений double из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
double[] - Массив значений double.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


Читает одно значение float из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |

**Returns:**
float - Одно значение float.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


Читает массив значений float из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
float[] - Массив значений float.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


Читает одно значение рационального числа из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) - The rational number.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


Читает одно значение знакового рационального числа из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) - The signed rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


Читает массив значений рациональных чисел из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[] - Массив рациональных значений.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


Читает массив значений знаковых рациональных чисел из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffSRational[] - Массив знаковых рациональных значений.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


Читает данные знакового байта из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |

**Returns:**
byte - Знаковое значение байта.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


Читает массив значений знаковых байтов из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
byte[] - Массив знаковых значений байтов.
### readSInt(long position) {#readSInt-long-}
```
public int readSInt(long position)
```


Читает значение знакового целого числа из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |

**Returns:**
int - Знаковое целочисленное значение.
### readSIntArray(long position, long count) {#readSIntArray-long-long-}
```
public int[] readSIntArray(long position, long count)
```


Читает массив значений знаковых целых чисел из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
int[] - Массив знаковых целочисленных значений.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


Читает значение знакового short из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |

**Returns:**
short - Знаковое значение short.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


Читает массив значений знаковых short из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
short[] - Массив знаковых значений short.
### readUInt(long position) {#readUInt-long-}
```
public long readUInt(long position)
```


Читает значение беззнакового целого числа из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |

**Returns:**
long - Беззнаковое целочисленное значение.
### readUIntArray(long position, long count) {#readUIntArray-long-long-}
```
public long[] readUIntArray(long position, long count)
```


Читает массив значений беззнаковых целых чисел из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
long[] - Массив беззнаковых целочисленных значений.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


Читает значение беззнакового short из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |

**Returns:**
int - Беззнаковое короткое значение.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


Читает массив значений беззнаковых целых чисел из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
int[] - Массив беззнаковых целочисленных значений.
### readLong(long position) {#readLong-long-}
```
public final long readLong(long position)
```


Читает значение беззнакового long из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |

**Returns:**
long - Беззнаковое короткое значение.
### readLongArray(long position, long count) {#readLongArray-long-long-}
```
public final long[] readLongArray(long position, long count)
```


Читает массив значений long из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
long[] - Массив ulong.
### readULong(long position) {#readULong-long-}
```
public final long readULong(long position)
```


Читает значение беззнакового long из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |

**Returns:**
long - Беззнаковое короткое значение.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public final long[] readULongArray(long position, long count)
```


Читает массив значений ulong из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| позиция | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
long[] - Массив ulong.
### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


Преобразует базовые данные в контейнер потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startPosition | long | Начальная позиция, с которой начинается преобразование. |

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - The `StreamContainer` with converted data.
