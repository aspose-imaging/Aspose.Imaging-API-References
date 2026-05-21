---
title: "EmfCreateColorSpaceW"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_CREATECOLORSPACEW создаёт логический объект цветового пространства из цветового профиля с именем, состоящим из символов Unicode."
type: docs
weight: 37
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpaceW extends EmfObjectCreationRecordType
```

Запись EMR\_CREATECOLORSPACEW создает объект логического цветового пространства из цветового профиля с именем, состоящим из символов Unicode.

Логический объект цветового пространства, определенный этой записью, может быть выбран в контекст устройства воспроизведения записью EMR\\_SETCOLORSPACE (раздел 2.3.8.7), которая определяет логическое цветовое пространство, используемое в последующих графических операциях.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfCreateColorSpaceW(EmfRecord source)](#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfCreateColorSpaceW`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getIhCS()](#getIhCS--) | Получает или задает 32-битное беззнаковое целое число, указывающее индекс логического объекта цветового пространства в таблице объектов EMF (раздел 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Получает или задает 32-битное беззнаковое целое число, указывающее индекс логического объекта цветового пространства в таблице объектов EMF (раздел 3.1.1.1). |
| [getLcs()](#getLcs--) | Получает или задает объект WMF LogColorSpaceW ([MS-WMF] раздел 2.2.2.12), который может указывать имя цветового профиля в символах Unicode UTF16-LE. |
| [setLcs(WmfLogColorSpaceW value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-) | Получает или задает объект WMF LogColorSpaceW ([MS-WMF] раздел 2.2.2.12), который может указывать имя цветового профиля в символах Unicode UTF16-LE. |
| [getDwFlags()](#getDwFlags--) | Получает или задает 32‑битное беззнаковое целое, которое предоставляет информацию о данных в этой записи. |
| [setDwFlags(int value)](#setDwFlags-int-) | Получает или задает 32‑битное беззнаковое целое, которое предоставляет информацию о данных в этой записи. |
| [getCbData()](#getCbData--) | Получает или задает 32-битное беззнаковое целое, которое указывает размер, в байтах, поля Data. |
| [setCbData(int value)](#setCbData-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает размер, в байтах, поля Data. |
| [getData()](#getData--) | Получает или задает необязательный массив байтов, который указывает данные цветового профиля. |
| [setData(byte[] value)](#setData-byte---) | Получает или задает необязательный массив байтов, который указывает данные цветового профиля. |
### EmfCreateColorSpaceW(EmfRecord source) {#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpaceW(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfCreateColorSpaceW`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


Получает или задает 32-битное беззнаковое целое число, указывающее индекс логического объекта цветового пространства в таблице объектов EMF (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранён, чтобы объект можно было повторно использовать или изменить.

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


Получает или задает 32-битное беззнаковое целое число, указывающее индекс логического объекта цветового пространства в таблице объектов EMF (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранён, чтобы объект можно было повторно использовать или изменить.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLcs() {#getLcs--}
```
public WmfLogColorSpaceW getLcs()
```


Получает или задает объект WMF LogColorSpaceW ([MS-WMF] раздел 2.2.2.12), который может указывать имя цветового профиля в символах Unicode UTF16-LE.

**Returns:**
[WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew)
### setLcs(WmfLogColorSpaceW value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-}
```
public void setLcs(WmfLogColorSpaceW value)
```


Получает или задает объект WMF LogColorSpaceW ([MS-WMF] раздел 2.2.2.12), который может указывать имя цветового профиля в символах Unicode UTF16-LE.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew) |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Получает или задает 32‑битное беззнаковое целое, которое предоставляет информацию о данных в этой записи.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое предоставляет информацию о данных в этой записи.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Получает или задает 32-битное беззнаковое целое, которое указывает размер, в байтах, поля Data.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает размер, в байтах, поля Data.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Получает или задает необязательный массив байтов, который указывает данные цветового профиля.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Получает или задает необязательный массив байтов, который указывает данные цветового профиля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

