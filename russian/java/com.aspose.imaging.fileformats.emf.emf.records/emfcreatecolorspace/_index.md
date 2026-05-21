---
title: "EmfCreateColorSpace"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_CREATECOLORSPACE создает логический объект цветового пространства из цветового профиля с именем, состоящим из символов ASCII."
type: docs
weight: 36
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpace extends EmfObjectCreationRecordType
```

Запись EMR\_CREATECOLORSPACE создает объект логического цветового пространства из цветового профиля с именем, состоящим из символов ASCII.

Логический объект цветового пространства, определенный этой записью, может быть выбран в контекст устройства воспроизведения записью EMR\\_SETCOLORSPACE (раздел 2.3.8.7), которая определяет логическое цветовое пространство, используемое в последующих графических операциях.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfCreateColorSpace(EmfRecord source)](#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfCreateColorSpace`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getIhCS()](#getIhCS--) | Получает или задает 32-битное беззнаковое целое число, указывающее индекс логического объекта цветового пространства в таблице объектов EMF (раздел 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Получает или задает 32-битное беззнаковое целое число, указывающее индекс логического объекта цветового пространства в таблице объектов EMF (раздел 3.1.1.1). |
| [getLcs()](#getLcs--) | Получает или задает объект WMF LogColorSpace ([MS-WMF] раздел 2.2.2.11), который может указывать имя цветового профиля в символах ASCII. |
| [setLcs(WmfLogColorSpace value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-) | Получает или задает объект WMF LogColorSpace ([MS-WMF] раздел 2.2.2.11), который может указывать имя цветового профиля в символах ASCII. |
### EmfCreateColorSpace(EmfRecord source) {#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpace(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfCreateColorSpace`.

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
public WmfLogColorSpace getLcs()
```


Получает или задает объект WMF LogColorSpace ([MS-WMF] раздел 2.2.2.11), который может указывать имя цветового профиля в символах ASCII.

**Returns:**
[WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace)
### setLcs(WmfLogColorSpace value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-}
```
public void setLcs(WmfLogColorSpace value)
```


Получает или задает объект WMF LogColorSpace ([MS-WMF] раздел 2.2.2.11), который может указывать имя цветового профиля в символах ASCII.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace) |  |

