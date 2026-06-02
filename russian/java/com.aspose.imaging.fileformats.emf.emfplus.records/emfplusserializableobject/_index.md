---
title: "EmfPlusSerializableObject"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusSerializableObject определяет блок параметров эффектов изображения, который был сериализован в буфер данных."
type: docs
weight: 53
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusSerializableObject extends EmfPlusObjectRecordType
```

Запись EmfPlusSerializableObject определяет блок параметров эффектов изображения, который был сериализован в буфер данных.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusSerializableObject(EmfPlusRecord source)](#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusSerializableObject`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFlags()](#getFlags--) | Получает или задает 16-битное беззнаковое целое, которое не используется. |
| [setFlags(short value)](#setFlags-short-) | Получает или задает 16-битное беззнаковое целое, которое не используется. |
| [getObjectGuid()](#getObjectGuid--) | Получает или задает значение представления пакета GUID ([MS-DTYP] section 2.3.4.2) для эффекта изображения. |
| [setObjectGuid(GuidPacketRepresentation value)](#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-) | Получает или задает значение представления пакета GUID ([MS-DTYP] section 2.3.4.2) для эффекта изображения. |
| [getBufferSize()](#getBufferSize--) | Получает или задает 32-битное беззнаковое целое, которое указывает размер в байтах поля Buffer, выровненного по 32-битам. |
| [setBufferSize(int value)](#setBufferSize-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает размер в байтах поля Buffer, выровненного по 32-битам. |
| [getBuffer()](#getBuffer--) | Получает или задает массив из BufferSize байт, содержащий сериализованный блок параметров эффектов изображения, соответствующий GUID в поле ObjectGUID. |
| [setBuffer(byte[] value)](#setBuffer-byte---) | Получает или задает массив из BufferSize байт, содержащий сериализованный блок параметров эффектов изображения, соответствующий GUID в поле ObjectGUID. |
| [getImageEffect()](#getImageEffect--) | Получает или задает эффект изображения. |
| [setImageEffect(EmfPlusImageEffectsObjectType value)](#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-) | Получает или задает эффект изображения. |
### EmfPlusSerializableObject(EmfPlusRecord source) {#EmfPlusSerializableObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSerializableObject(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusSerializableObject`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getFlags() {#getFlags--}
```
public short getFlags()
```


Получает или задает 16-битное беззнаковое целое, которое не используется. Это поле SHOULD должно быть установлено в ноль и MUST игнорироваться при получении.

Значение: Флаги.

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Получает или задает 16-битное беззнаковое целое, которое не используется. Это поле SHOULD должно быть установлено в ноль и MUST игнорироваться при получении.

Значение: Флаги.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

### getObjectGuid() {#getObjectGuid--}
```
public GuidPacketRepresentation getObjectGuid()
```


Получает или задает значение представления пакета GUID ([MS-DTYP] section 2.3.4.2) для эффекта изображения. Это MUST соответствовать одному из идентификаторов ImageEffects (section 2.1.3.1).

**Returns:**
[GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation)
### setObjectGuid(GuidPacketRepresentation value) {#setObjectGuid-com.aspose.imaging.fileformats.emf.dtyp.commondatastructures.GuidPacketRepresentation-}
```
public void setObjectGuid(GuidPacketRepresentation value)
```


Получает или задает значение представления пакета GUID ([MS-DTYP] section 2.3.4.2) для эффекта изображения. Это MUST соответствовать одному из идентификаторов ImageEffects (section 2.1.3.1).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [GuidPacketRepresentation](../../com.aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation) |  |

### getBufferSize() {#getBufferSize--}
```
public int getBufferSize()
```


Получает или задает 32-битное беззнаковое целое, которое указывает размер в байтах поля Buffer, выровненного по 32-битам.

**Returns:**
int
### setBufferSize(int value) {#setBufferSize-int-}
```
public void setBufferSize(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает размер в байтах поля Buffer, выровненного по 32-битам.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBuffer() {#getBuffer--}
```
public byte[] getBuffer()
```


Получает или задает массив из BufferSize байт, содержащий сериализованный блок параметров эффектов изображения, соответствующий GUID в поле ObjectGUID. Это MUST быть одним из объектов Image Effects (section 2.2.3).

**Returns:**
byte[]
### setBuffer(byte[] value) {#setBuffer-byte---}
```
public void setBuffer(byte[] value)
```


Получает или задает массив из BufferSize байт, содержащий сериализованный блок параметров эффектов изображения, соответствующий GUID в поле ObjectGUID. Это MUST быть одним из объектов Image Effects (section 2.2.3).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getImageEffect() {#getImageEffect--}
```
public EmfPlusImageEffectsObjectType getImageEffect()
```


Получает или задает эффект изображения.

Значение: эффект изображения.

**Returns:**
[EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
### setImageEffect(EmfPlusImageEffectsObjectType value) {#setImageEffect-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType-}
```
public void setImageEffect(EmfPlusImageEffectsObjectType value)
```


Получает или задает эффект изображения.

Значение: эффект изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype) |  |

