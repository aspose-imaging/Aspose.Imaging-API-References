---
title: "EmfSetBkMode"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SETBKMODE задаёт режим смешивания фона в контексте устройства воспроизведения."
type: docs
weight: 120
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetBkMode extends EmfStateRecordType
```

Запись EMR\_SETBKMODE задаёт режим смешивания фона в контексте устройства воспроизведения. Режим смешивания фона используется с текстом, штриховыми кистями и стилями пера, которые не являются сплошными линиями.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSetBkMode(EmfRecord source)](#EmfSetBkMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSetBkMode`. |
| [EmfSetBkMode()](#EmfSetBkMode--) | Инициализирует новый экземпляр класса `EmfSetBkMode`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBackgroundMode()](#getBackgroundMode--) | Получает или задает 32-битное беззнаковое целое, которое определяет режим фона и ДОЛЖНО находиться в перечислении BackgroundMode (раздел 2.1.4). |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет режим фона и ДОЛЖНО находиться в перечислении BackgroundMode (раздел 2.1.4). |
### EmfSetBkMode(EmfRecord source) {#EmfSetBkMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetBkMode(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSetBkMode`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfSetBkMode() {#EmfSetBkMode--}
```
public EmfSetBkMode()
```


Инициализирует новый экземпляр класса `EmfSetBkMode`.

### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


Получает или задает 32-битное беззнаковое целое, которое определяет режим фона и ДОЛЖНО находиться в перечислении BackgroundMode (раздел 2.1.4).

**Returns:**
int
### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет режим фона и ДОЛЖНО находиться в перечислении BackgroundMode (раздел 2.1.4).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

