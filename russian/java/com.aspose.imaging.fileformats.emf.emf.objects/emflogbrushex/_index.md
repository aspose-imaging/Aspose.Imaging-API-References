---
title: "EmfLogBrushEx"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект LogBrushEx определяет стиль, цвет и узор независимой от устройства кисти."
type: docs
weight: 21
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfLogBrushEx extends EmfObject
```

Объект LogBrushEx определяет стиль, цвет и узор независимой от устройства кисти.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfLogBrushEx()](#EmfLogBrushEx--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getBrushStyle()](#getBrushStyle--) | Получает или задает 32‑битное беззнаковое целое, которое определяет стиль кисти. |
| [setBrushStyle(int value)](#setBrushStyle-int-) | Получает или задает 32‑битное беззнаковое целое, которое определяет стиль кисти. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Получает или задает 32‑битный объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет цвет. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Получает или задает 32‑битный объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет цвет. |
| [getBrushHatch()](#getBrushHatch--) | Получает или задает 32‑битное беззнаковое поле, которое содержит данные штриха кисти. |
| [setBrushHatch(int value)](#setBrushHatch-int-) | Получает или задает 32‑битное беззнаковое поле, которое содержит данные штриха кисти. |
### EmfLogBrushEx() {#EmfLogBrushEx--}
```
public EmfLogBrushEx()
```


### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


Получает или задает 32‑битное беззнаковое целое, которое определяет стиль кисти. Значение ДОЛЖНО быть элементом перечисления WMF BrushStyle ([MS-WMF] раздел 2.1.1.4). Значения стилей, поддерживаемые в этой структуре, перечислены позже в этом разделе. Стиль BS\_NULL ДОЛЖЕН использоваться для указания кисти, не оказывающей влияния.

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое определяет стиль кисти. Значение ДОЛЖНО быть элементом перечисления WMF BrushStyle ([MS-WMF] раздел 2.1.1.4). Значения стилей, поддерживаемые в этой структуре, перечислены позже в этом разделе. Стиль BS\_NULL ДОЛЖЕН использоваться для указания кисти, не оказывающей влияния.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Получает или задает 32‑битный объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет цвет. Интерпретация этого поля зависит от значения BrushStyle, как объясняется в следующей таблице.

Значение: 32-битный цвет ARGB

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Получает или задает 32‑битный объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), который определяет цвет. Интерпретация этого поля зависит от значения BrushStyle, как объясняется в следующей таблице.

Значение: 32-битный цвет ARGB

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


Получает или задает 32‑битное беззнаковое поле, которое содержит данные штриха кисти. Его интерпретация зависит от значения BrushStyle,

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


Получает или задает 32‑битное беззнаковое поле, которое содержит данные штриха кисти. Его интерпретация зависит от значения BrushStyle,

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

