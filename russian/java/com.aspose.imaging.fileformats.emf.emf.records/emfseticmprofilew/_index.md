---
title: "EmfSetIcmProfileW"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SETICMPROFILEW определяет цветовой профиль в файле с именем, состоящим из символов Unicode для вывода графики."
type: docs
weight: 127
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmprofilew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmProfileW extends EmfStateRecordType
```

Запись EMR\_SETICMPROFILEW указывает цветовой профиль в файле с именем, состоящим из символов Unicode, для графического вывода.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSetIcmProfileW(EmfRecord source)](#EmfSetIcmProfileW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSetIcmProfileW`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getDwFlags()](#getDwFlags--) | Получает или задает 32-битное беззнаковое целое, содержащее флаги цветового профиля. |
| [setDwFlags(int value)](#setDwFlags-int-) | Получает или задает 32-битное беззнаковое целое, содержащее флаги цветового профиля. |
| [getCbName()](#getCbName--) | Получает или задаёт 32‑битное беззнаковое целое, которое указывает количество байт в имени профиля цвета в кодировке Unicode UTF16-LE. |
| [setCbName(int value)](#setCbName-int-) | Получает или задаёт 32‑битное беззнаковое целое, которое указывает количество байт в имени профиля цвета в кодировке Unicode UTF16-LE. |
| [getCbData()](#getCbData--) | Получает или задает 32‑битное беззнаковое целое, которое определяет размер данных цветового профиля, если они вложены. |
| [setCbData(int value)](#setCbData-int-) | Получает или задает 32‑битное беззнаковое целое, которое определяет размер данных цветового профиля, если они вложены. |
| [getData()](#getData--) | Получает или задает массив размером (cbName + cbData) в байтах, который указывает имя в кодировке UTF16-LE и необработанные данные желаемого цветового профиля. |
| [setData(byte[] value)](#setData-byte---) | Получает или задает массив размером (cbName + cbData) в байтах, который указывает имя в кодировке UTF16-LE и необработанные данные желаемого цветового профиля. |
| [getName()](#getName--) | Получает имя |
| [getRawData()](#getRawData--) | Получает необработанные данные |
### EmfSetIcmProfileW(EmfRecord source) {#EmfSetIcmProfileW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmProfileW(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSetIcmProfileW`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Получает или задает 32-битное беззнаковое целое, содержащее флаги цветового профиля.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Получает или задает 32-битное беззнаковое целое, содержащее флаги цветового профиля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


Получает или задаёт 32‑битное беззнаковое целое, которое указывает количество байт в имени профиля цвета в кодировке Unicode UTF16-LE.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


Получает или задаёт 32‑битное беззнаковое целое, которое указывает количество байт в имени профиля цвета в кодировке Unicode UTF16-LE.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Получает или задает 32‑битное беззнаковое целое, которое определяет размер данных цветового профиля, если они вложены.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое определяет размер данных цветового профиля, если они вложены.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Получает или задает массив размером (cbName + cbData) в байтах, который указывает имя в кодировке UTF16-LE и необработанные данные желаемого цветового профиля.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Получает или задает массив размером (cbName + cbData) в байтах, который указывает имя в кодировке UTF16-LE и необработанные данные желаемого цветового профиля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getName() {#getName--}
```
public String getName()
```


Получает имя

**Returns:**
java.lang.String
### getRawData() {#getRawData--}
```
public byte[] getRawData()
```


Получает необработанные данные

**Returns:**
byte[]
