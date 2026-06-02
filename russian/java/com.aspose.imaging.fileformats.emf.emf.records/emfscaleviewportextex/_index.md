---
title: "EmfScaleViewportExtex"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SCALEVIEWPORTEXTEX переопределяет область просмотра для контекста устройства, используя отношения, образованные указанными множителями и делителями."
type: docs
weight: 113
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfScaleViewportExtex extends EmfStateRecordType
```

Запись EMR\_SCALEVIEWPORTEXTEX переопределяет область просмотра для контекста устройства, используя отношения, образованные указанными множителями и делителями.

Размер нельзя изменить, если контекст устройства использует режим отображения с фиксированным масштабом. Только MM\_ISOTROPIC и MM\_ANISOTROPIC не являются фиксированным масштабом. Размеры области просмотра изменяются следующим образом. xNewWE = (xOldWE \* xNum) / xDenom yNewWE = (yOldWE \* yNum) / yDenom
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfScaleViewportExtex(EmfRecord source)](#EmfScaleViewportExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfScaleViewportExtex`. |
| [EmfScaleViewportExtex()](#EmfScaleViewportExtex--) | Инициализирует новый экземпляр класса [EmfScaleViewportExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex). |
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
### EmfScaleViewportExtex(EmfRecord source) {#EmfScaleViewportExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfScaleViewportExtex(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfScaleViewportExtex`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfScaleViewportExtex() {#EmfScaleViewportExtex--}
```
public EmfScaleViewportExtex()
```


Инициализирует новый экземпляр класса [EmfScaleViewportExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex).

### getXNum() {#getXNum--}
```
public int getXNum()
```


Получает или задает 32‑битное знаковое целое, которое определяет горизонтальный мультипликатор. Не может быть нулём.

**Returns:**
int
### setXNum(int value) {#setXNum-int-}
```
public void setXNum(int value)
```


Получает или задает 32‑битное знаковое целое, которое определяет горизонтальный мультипликатор. Не может быть нулём.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getXDenom() {#getXDenom--}
```
public int getXDenom()
```


Получает или задает 32‑битное знаковое целое, которое определяет горизонтальный делитель. Не может быть нулём.

**Returns:**
int
### setXDenom(int value) {#setXDenom-int-}
```
public void setXDenom(int value)
```


Получает или задает 32‑битное знаковое целое, которое определяет горизонтальный делитель. Не может быть нулём.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getYNum() {#getYNum--}
```
public int getYNum()
```


Получает или задает 32‑битное знаковое целое, которое определяет вертикальный мультипликатор. Не может быть нулём.

**Returns:**
int
### setYNum(int value) {#setYNum-int-}
```
public void setYNum(int value)
```


Получает или задает 32‑битное знаковое целое, которое определяет вертикальный мультипликатор. Не может быть нулём.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getYDenom() {#getYDenom--}
```
public int getYDenom()
```


Получает или задает 32‑битное знаковое целое, которое определяет вертикальный делитель. Не может быть нулём.

**Returns:**
int
### setYDenom(int value) {#setYDenom-int-}
```
public void setYDenom(int value)
```


Получает или задает 32‑битное знаковое целое, которое определяет вертикальный делитель. Не может быть нулём.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

