---
title: "EmfForceUfiMapping"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_FORCEUFIMAPPING заставляет сопоставитель шрифтов выбирать шрифты на основе их UniversalFontId, предпочтительно перед информацией LogFont (section 2.2.13)."
type: docs
weight: 61
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfforceufimapping/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfForceUfiMapping extends EmfStateRecordType
```

Запись EMR\_FORCEUFIMAPPING заставляет сопоставитель шрифтов сопоставлять шрифты на основе их UniversalFontId, предпочитая эту информацию информации LogFont (раздел 2.2.13).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfForceUfiMapping(EmfRecord source)](#EmfForceUfiMapping-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfForceUfiMapping`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getUfi()](#getUfi--) | Получает или задает идентификатор шрифта, используемый в виде UniversalFontId (section 2.2.27). |
| [setUfi(EmfUniversalFontId value)](#setUfi-com.aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId-) | Получает или задает идентификатор шрифта, используемый в виде UniversalFontId (section 2.2.27). |
### EmfForceUfiMapping(EmfRecord source) {#EmfForceUfiMapping-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfForceUfiMapping(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfForceUfiMapping`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getUfi() {#getUfi--}
```
public EmfUniversalFontId getUfi()
```


Получает или задает идентификатор шрифта, используемый в виде UniversalFontId (section 2.2.27).

**Returns:**
[EmfUniversalFontId](../../com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid)
### setUfi(EmfUniversalFontId value) {#setUfi-com.aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId-}
```
public void setUfi(EmfUniversalFontId value)
```


Получает или задает идентификатор шрифта, используемый в виде UniversalFontId (section 2.2.27).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfUniversalFontId](../../com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid) |  |

