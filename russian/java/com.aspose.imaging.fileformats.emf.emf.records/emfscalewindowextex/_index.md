---
title: "EmfScaleWindowExtex"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SCALEWINDOWEXTEX переопределяет окно для контекста воспроизведения устройства, используя отношения, образованные указанными множителями и делителями."
type: docs
weight: 114
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfScaleWindowExtex extends EmfStateRecordType
```

Запись EMR\_SCALEWINDOWEXTEX переопределяет окно для контекста устройства воспроизведения, используя отношения, образованные указанными множителями и делителями.

Размеры нельзя изменить, если контекст устройства использует режим отображения с фиксированным масштабом. Только MM\_ISOTROPIC и MM\_ANISOTROPIC не являются фиксированным масштабом. Размеры окна изменяются следующим образом. xNewWE = (xOldWE \* xNum) / xDenom yNewWE = (yOldWE \* yNum) / yDenom
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfScaleWindowExtex(EmfRecord source)](#EmfScaleWindowExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfScaleWindowExtex`. |
| [EmfScaleWindowExtex()](#EmfScaleWindowExtex--) | Инициализирует новый экземпляр класса [EmfScaleWindowExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex). |
## Методы

| Метод | Описание |
| --- | --- |
| [getXNum()](#getXNum--) | Получает или задает 32‑битное знаковое целое, которое определяет горизонтальный мультипликатор. |
| [setXNum(int value)](#setXNum-int-) | Получает или задает 32‑битное знаковое целое, которое определяет горизонтальный мультипликатор. |
| [getXDenom()](#getXDenom--) | Получает или задает 32‑битное знаковое целое, которое определяет горизонтальный делитель. |
| [setXDenom(int value)](#setXDenom-int-) | Получает или задает 32‑битное знаковое целое, которое определяет горизонтальный делитель. |
| [getYNum()](#getYNum--) | Получает или задает 32‑битное знаковое целое, которое определяет вертикальный мультипликатор. |
| [setYNum(int value)](#setYNum-int-) | Получает или задает 32‑битное знаковое целое, которое определяет вертикальный мультипликатор. |
| [getYDenom()](#getYDenom--) | Получает или задает 32‑битное знаковое целое, которое определяет вертикальный делитель. |
| [setYDenom(int value)](#setYDenom-int-) | Получает или задает 32‑битное знаковое целое, которое определяет вертикальный делитель. |
### EmfScaleWindowExtex(EmfRecord source) {#EmfScaleWindowExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfScaleWindowExtex(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfScaleWindowExtex`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfScaleWindowExtex() {#EmfScaleWindowExtex--}
```
public EmfScaleWindowExtex()
```


Инициализирует новый экземпляр класса [EmfScaleWindowExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex).

### getXNum() {#getXNum--}
```
public int getXNum()
```


Получает или задает 32‑битное знаковое целое, определяющее горизонтальный множитель. ДОЛЖНО быть ненулевым.

**Returns:**
int
### setXNum(int value) {#setXNum-int-}
```
public void setXNum(int value)
```


Получает или задает 32‑битное знаковое целое, определяющее горизонтальный множитель. ДОЛЖНО быть ненулевым.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getXDenom() {#getXDenom--}
```
public int getXDenom()
```


Получает или задает 32‑битное знаковое целое, определяющее горизонтальный делитель. ДОЛЖНО быть ненулевым.

**Returns:**
int
### setXDenom(int value) {#setXDenom-int-}
```
public void setXDenom(int value)
```


Получает или задает 32‑битное знаковое целое, определяющее горизонтальный делитель. ДОЛЖНО быть ненулевым.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getYNum() {#getYNum--}
```
public int getYNum()
```


Получает или задает 32‑битное знаковое целое, определяющее вертикальный множитель. ДОЛЖНО быть ненулевым.

**Returns:**
int
### setYNum(int value) {#setYNum-int-}
```
public void setYNum(int value)
```


Получает или задает 32‑битное знаковое целое, определяющее вертикальный множитель. ДОЛЖНО быть ненулевым.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getYDenom() {#getYDenom--}
```
public int getYDenom()
```


Получает или задает 32‑битное знаковое целое, определяющее вертикальный делитель. ДОЛЖНО быть ненулевым.

**Returns:**
int
### setYDenom(int value) {#setYDenom-int-}
```
public void setYDenom(int value)
```


Получает или задает 32‑битное знаковое целое, определяющее вертикальный делитель. ДОЛЖНО быть ненулевым.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

