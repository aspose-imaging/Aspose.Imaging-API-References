---
title: "TiffDataType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Тип данных TIFF."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.tiff/tiffdatatype/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

Тип данных TIFF.
## Методы

| Метод | Описание |
| --- | --- |
| [getElementSize()](#getElementSize--) | Возвращает размер элемента в байтах. |
| [getDataSize()](#getDataSize--) | Возвращает размер значения тега. |
| [getCount()](#getCount--) | Возвращает количество элементов. |
| [getId()](#getId--) | Возвращает идентификатор тега как число. |
| [getTagId()](#getTagId--) | Возвращает идентификатор тега. |
| [getTagType()](#getTagType--) | Возвращает тип тега. |
| [getAlignedDataSize(byte sizeOfTagValue)](#getAlignedDataSize-byte-) | Возвращает размер данных, выровненный по границе 4‑байтов (int) или 8‑байтов (long). |
| [getAdditionalDataSize(byte sizeOfTagValue)](#getAdditionalDataSize-byte-) | Возвращает дополнительный размер значения тега в байтах (в случае, если тег не может вместить всё значение). |
| [getValue()](#getValue--) | Получает значение, содержащееся в этом типе данных. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Устанавливает значение, содержащееся в этом типе данных. |
| [isValid()](#isValid--) | Получает значение, указывающее, действительны ли данные тега. |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Читает данные тега. |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-) | Сравнивает текущий экземпляр с другим объектом того же типа и возвращает целое число, указывающее, предшествует ли текущий экземпляр, следует за ним или находится в той же позиции в порядке сортировки, что и другой объект. |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [deepClone()](#deepClone--) | Выполняет глубокое клонирование этого экземпляра. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Записывает данные тега. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Записывает дополнительные данные тега. |
| [toString()](#toString--) | Возвращает `System.String`, представляющий этот экземпляр. |
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Возвращает размер элемента в байтах.

**Returns:**
byte - размер элемента в байтах.
### getDataSize() {#getDataSize--}
```
public long getDataSize()
```


Возвращает размер значения тега.

**Returns:**
long - размер значения тега.
### getCount() {#getCount--}
```
public abstract long getCount()
```


Возвращает количество элементов.

Значение: количество элементов.

**Returns:**
long - количество элементов.
### getId() {#getId--}
```
public final int getId()
```


Возвращает идентификатор тега как число.

**Returns:**
int - идентификатор тега как число.
### getTagId() {#getTagId--}
```
public int getTagId()
```


Возвращает идентификатор тега.

**Returns:**
int - идентификатор тега.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Возвращает тип тега.

**Returns:**
int - тип тега.
### getAlignedDataSize(byte sizeOfTagValue) {#getAlignedDataSize-byte-}
```
public final long getAlignedDataSize(byte sizeOfTagValue)
```


Возвращает размер данных, выровненный по границе 4‑байтов (int) или 8‑байтов (long).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sizeOfTagValue | byte | Размер значения тега. |

**Returns:**
long - выровненный размер данных в байтах.
### getAdditionalDataSize(byte sizeOfTagValue) {#getAdditionalDataSize-byte-}
```
public long getAdditionalDataSize(byte sizeOfTagValue)
```


Возвращает дополнительный размер значения тега в байтах (в случае, если тег не может вместить всё значение).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sizeOfTagValue | byte | Размер значения тега: 4 или 8 для BigTiff. |

**Returns:**
long - размер дополнительных данных в байтах.
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Получает значение, содержащееся в этом типе данных.

**Returns:**
java.lang.Object - значение.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Устанавливает значение, содержащееся в этом типе данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object | Значение. |

### isValid() {#isValid--}
```
public boolean isValid()
```


Получает значение, указывающее, действительны ли данные тега. Действительный тег содержит данные, которые могут быть сохранены. Недействительный тег не может быть сохранён.

**Returns:**
boolean - `true`, если данные тега действительны; иначе `false`.
### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


Читает данные тега.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamreader) | Поток данных. |
| позиция | long | Позиция тега. |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The read tag.
### compareTo(TiffDataType obj) {#compareTo-com.aspose.imaging.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Сравнивает текущий экземпляр с другим объектом того же типа и возвращает целое число, указывающее, предшествует ли текущий экземпляр, следует за ним или находится в той же позиции в порядке сортировки, что и другой объект.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Объект для сравнения с этим экземпляром. |

**Returns:**
int - 32‑битное знаковое целое, указывающее относительный порядок сравниваемых объектов. Возвращаемое значение имеет следующие значения: Значение Описание Меньше нуля Этот экземпляр меньше `obj`. Ноль Этот экземпляр равен `obj`. Больше нуля Этот экземпляр больше `obj`.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Выполняет глубокое клонирование этого экземпляра.

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Записывает данные тега.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | Поток данных. |
| additionalDataOffset | long | Смещение, в которое записываются дополнительные данные. |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


Записывает дополнительные данные тега.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | Поток данных. |

**Returns:**
long - Фактически записанные байты.
### toString() {#toString--}
```
public String toString()
```


Возвращает `System.String`, представляющий этот экземпляр.

**Returns:**
java.lang.String - `System.String`, представляющая этот экземпляр.
