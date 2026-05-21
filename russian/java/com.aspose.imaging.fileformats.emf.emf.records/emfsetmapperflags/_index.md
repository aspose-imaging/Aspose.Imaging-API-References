---
title: "EmfSetMapperFlags"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SETMAPPERFLAGS определяет параметры процесса сопоставления логических шрифтов с физическими, который выполняется сопоставителем шрифтов."
type: docs
weight: 131
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetmapperflags/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetMapperFlags extends EmfStateRecordType
```

Запись EMR\_SETMAPPERFLAGS указывает параметры процесса сопоставления логических шрифтов физическим шрифтам, выполняемого сопоставителем шрифтов.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSetMapperFlags(EmfRecord source)](#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSetMapperFlags`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFlags()](#getFlags--) | Получает или задает 32‑битное беззнаковое целое, определяющее параметры процесса сопоставления шрифтов. |
| [setFlags(int value)](#setFlags-int-) | Получает или задает 32‑битное беззнаковое целое, определяющее параметры процесса сопоставления шрифтов. |
### EmfSetMapperFlags(EmfRecord source) {#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetMapperFlags(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSetMapperFlags`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Получает или задает 32‑битное беззнаковое целое, определяющее параметры процесса сопоставления шрифтов.

0x00000001 Сопоставитель шрифтов ДОЛЖЕН выбирать только шрифты, соответствующие соотношению сторон выходного устройства, как это в настоящее время определено в контексте воспроизведения устройства.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Получает или задает 32‑битное беззнаковое целое, определяющее параметры процесса сопоставления шрифтов.

0x00000001 Сопоставитель шрифтов ДОЛЖЕН выбирать только шрифты, соответствующие соотношению сторон выходного устройства, как это в настоящее время определено в контексте воспроизведения устройства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

