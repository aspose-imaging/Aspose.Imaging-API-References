---
title: "EmfSelectClipPath"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SELECTCLIPPATH определяет текущий путь как область отсечения для контекста воспроизведения устройства, объединяя новую область с любой существующей областью отсечения с использованием указанного режима."
type: docs
weight: 115
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfSelectClipPath extends EmfClippingRecordType
```

Запись EMR\_SELECTCLIPPATH определяет текущий путь как область отсечения для контекста устройства воспроизведения, объединяя новую область с любой существующей областью отсечения с использованием указанного режима.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSelectClipPath(EmfRecord source)](#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSelectClipPath`. |
| [EmfSelectClipPath()](#EmfSelectClipPath--) | Инициализирует новый экземпляр класса `EmfSelectClipPath`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getRegionMode()](#getRegionMode--) | Получает или задает 32‑битное беззнаковое целое, определяющее способ использования пути. |
| [setRegionMode(int value)](#setRegionMode-int-) | Получает или задает 32‑битное беззнаковое целое, определяющее способ использования пути. |
### EmfSelectClipPath(EmfRecord source) {#EmfSelectClipPath-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectClipPath(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSelectClipPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfSelectClipPath() {#EmfSelectClipPath--}
```
public EmfSelectClipPath()
```


Инициализирует новый экземпляр класса `EmfSelectClipPath`.

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


Получает или задает 32‑битное беззнаковое целое, определяющее способ использования пути. Значение ДОЛЖНО принадлежать перечислению RegionMode (раздел 2.1.29).

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


Получает или задает 32‑битное беззнаковое целое, определяющее способ использования пути. Значение ДОЛЖНО принадлежать перечислению RegionMode (раздел 2.1.29).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

