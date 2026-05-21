---
title: "EmfSetIcmProfileA"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SETICMPROFILEA указывает цветовой профиль в файле с именем, состоящим из символов ASCII, для графического вывода."
type: docs
weight: 126
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmProfileA extends EmfStateRecordType
```

Запись EMR\_SETICMPROFILEA указывает цветовой профиль в файле с именем, состоящим из символов ASCII, для графического вывода.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSetIcmProfileA(EmfRecord source)](#EmfSetIcmProfileA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSetIcmProfileA`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getDwFlags()](#getDwFlags--) | Получает или задает 32-битное беззнаковое целое, содержащее флаги цветового профиля. |
| [setDwFlags(int value)](#setDwFlags-int-) | Получает или задает 32-битное беззнаковое целое, содержащее флаги цветового профиля. |
| [getCbName()](#getCbName--) | Получает или задает 32-битное беззнаковое целое, указывающее количество байтов в ASCII‑имени требуемого цветового профиля. |
| [setCbName(int value)](#setCbName-int-) | Получает или задает 32-битное беззнаковое целое, указывающее количество байтов в ASCII‑имени требуемого цветового профиля. |
| [getCbData()](#getCbData--) | Получает или задает 32-битное беззнаковое целое, указывающее размер данных цветового профиля, если они находятся в поле Data. |
| [setCbData(int value)](#setCbData-int-) | Получает или задает 32-битное беззнаковое целое, указывающее размер данных цветового профиля, если они находятся в поле Data. |
| [getData()](#getData--) | Получает или задает массив размером (cbName + cbData) в байтах, который содержит ASCII‑имя и необработанные данные требуемого цветового профиля. |
| [setData(byte[] value)](#setData-byte---) | Получает или задает массив размером (cbName + cbData) в байтах, который содержит ASCII‑имя и необработанные данные требуемого цветового профиля. |
| [getName()](#getName--) | Получает имя |
| [getRawData()](#getRawData--) | Получает необработанные данные |
### EmfSetIcmProfileA(EmfRecord source) {#EmfSetIcmProfileA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmProfileA(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSetIcmProfileA`.

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


Получает или задает 32-битное беззнаковое целое, указывающее количество байтов в ASCII‑имени требуемого цветового профиля.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


Получает или задает 32-битное беззнаковое целое, указывающее количество байтов в ASCII‑имени требуемого цветового профиля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Получает или задает 32-битное беззнаковое целое, указывающее размер данных цветового профиля, если они находятся в поле Data.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Получает или задает 32-битное беззнаковое целое, указывающее размер данных цветового профиля, если они находятся в поле Data.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Получает или задает массив размером (cbName + cbData) в байтах, который содержит ASCII‑имя и необработанные данные требуемого цветового профиля.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Получает или задает массив размером (cbName + cbData) в байтах, который содержит ASCII‑имя и необработанные данные требуемого цветового профиля.

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
