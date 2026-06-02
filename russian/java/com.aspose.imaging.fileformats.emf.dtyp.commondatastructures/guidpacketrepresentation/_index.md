---
title: "GuidPacketRepresentation"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Версия пакета используется в блочных протоколах."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class GuidPacketRepresentation extends Struct<GuidPacketRepresentation>
```

Версия пакета используется в блочных протоколах. На следующей диаграмме GUID представлен как непрозрачная последовательность байтов. GUID, также известный как UUID, представляет собой 16-байтовую структуру, предназначенную служить уникальным идентификатором объекта. Существует три представления GUID, описанные в следующих разделах.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GuidPacketRepresentation()](#GuidPacketRepresentation--) |  |
| [GuidPacketRepresentation(int data1, short data2, short data3, long data4)](#GuidPacketRepresentation-int-short-short-long-) | Инициализирует новый экземпляр структуры `GuidPacketRepresentation`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getData1()](#getData1--) | Получает или задает значение члена Data1 (раздел 2.3.4) в порядке байтов little-endian. |
| [setData1(int value)](#setData1-int-) | Получает или задает значение члена Data1 (раздел 2.3.4) в порядке байтов little-endian. |
| [getData2()](#getData2--) | Получает или задает значение члена Data2 (раздел 2.3.4) в порядке байтов little-endian. |
| [setData2(short value)](#setData2-short-) | Получает или задает значение члена Data2 (раздел 2.3.4) в порядке байтов little-endian. |
| [getData3()](#getData3--) | Получает или задает значение члена Data3 (раздел 2.3.4) в порядке байтов little-endian. |
| [setData3(short value)](#setData3-short-) | Получает или задает значение члена Data3 (раздел 2.3.4) в порядке байтов little-endian. |
| [getData4()](#getData4--) | Получает или задает значение члена Data4 (раздел 2.3.4) в порядке байтов little-endian. |
| [setData4(long value)](#setData4-long-) | Получает или задает значение члена Data4 (раздел 2.3.4) в порядке байтов little-endian. |
| [toString()](#toString--) | Возвращает `System.String`, представляющий этот экземпляр. |
| [CloneTo(GuidPacketRepresentation that)](#CloneTo-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) |  |
| [Clone()](#Clone--) |  |
| [hashCode()](#hashCode--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2)](#isEquals-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) |  |
### GuidPacketRepresentation() {#GuidPacketRepresentation--}
```
public GuidPacketRepresentation()
```


### GuidPacketRepresentation(int data1, short data2, short data3, long data4) {#GuidPacketRepresentation-int-short-short-long-}
```
public GuidPacketRepresentation(int data1, short data2, short data3, long data4)
```


Инициализирует новый экземпляр структуры `GuidPacketRepresentation`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data1 | int | Поле data1. |
| data2 | short | Поле data2. |
| data3 | short | Поле data3. |
| data4 | long | Поле data4. |

### getData1() {#getData1--}
```
public int getData1()
```


Получает или задает значение члена Data1 (раздел 2.3.4) в порядке байтов little-endian.

Значение: поле data1.

**Returns:**
int
### setData1(int value) {#setData1-int-}
```
public void setData1(int value)
```


Получает или задает значение члена Data1 (раздел 2.3.4) в порядке байтов little-endian.

Значение: поле data1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getData2() {#getData2--}
```
public short getData2()
```


Получает или задает значение члена Data2 (раздел 2.3.4) в порядке байтов little-endian.

Значение: данные2.

**Returns:**
short
### setData2(short value) {#setData2-short-}
```
public void setData2(short value)
```


Получает или задает значение члена Data2 (раздел 2.3.4) в порядке байтов little-endian.

Значение: данные2.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getData3() {#getData3--}
```
public short getData3()
```


Получает или задает значение члена Data3 (раздел 2.3.4) в порядке байтов little-endian.

Значение: данные3.

**Returns:**
short
### setData3(short value) {#setData3-short-}
```
public void setData3(short value)
```


Получает или задает значение члена Data3 (раздел 2.3.4) в порядке байтов little-endian.

Значение: данные3.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getData4() {#getData4--}
```
public long getData4()
```


Получает или задает значение члена Data4 (раздел 2.3.4) в порядке байтов little-endian.

Значение: данные4.

**Returns:**
long
### setData4(long value) {#setData4-long-}
```
public void setData4(long value)
```


Получает или задает значение члена Data4 (раздел 2.3.4) в порядке байтов little-endian.

Значение: данные4.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает `System.String`, представляющий этот экземпляр.

**Returns:**
java.lang.String - `System.String`, представляющая этот экземпляр.
### CloneTo(GuidPacketRepresentation that) {#CloneTo-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public void CloneTo(GuidPacketRepresentation that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

### Clone() {#Clone--}
```
public GuidPacketRepresentation Clone()
```




**Returns:**
[GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation)
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
### isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2) {#isEquals-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public static boolean isEquals(GuidPacketRepresentation obj1, GuidPacketRepresentation obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |
| obj2 | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

**Returns:**
boolean
