---
title: "EmfLogPenEx"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект LogPenEx определяет ширину стиля и цвет расширенного логического пера."
type: docs
weight: 28
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpenex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPenEx extends EmfBasePen
```

Объект LogPenEx указывает стиль, ширину и цвет расширенного логического пера.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfLogPenEx()](#EmfLogPenEx--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | Получает или задает стиль пера. |
| [setPenStyle(int value)](#setPenStyle-int-) | Получает или задает стиль пера. |
| [getWidth()](#getWidth--) | Получает или задает 32-битное беззнаковое целое, которое указывает ширину линии, рисуемой пером. |
| [setWidth(int value)](#setWidth-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает ширину линии, рисуемой пером. |
| [getBrushStyle()](#getBrushStyle--) | Получает или задает 32-битное беззнаковое целое, которое указывает стиль кисти для пера из перечисления WMF BrushStyle ([MS-WMF] раздел 2.1.1.4). |
| [setBrushStyle(int value)](#setBrushStyle-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает стиль кисти для пера из перечисления WMF BrushStyle ([MS-WMF] раздел 2.1.1.4). |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8). |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8). |
| [getBrushHatch()](#getBrushHatch--) | Получает или задает шаблон штриховки кисти. |
| [setBrushHatch(int value)](#setBrushHatch-int-) | Получает или задает шаблон штриховки кисти. |
| [getNumStyleEntities()](#getNumStyleEntities--) | Получает количество элементов в массиве, указанном в поле StyleEntry. |
| [getStyleEntry()](#getStyleEntry--) | Получает или задает необязательный массив 32‑битных беззнаковых целых, определяющий длины штрихов и промежутков в линии, рисуемой этим пером, когда значение PenStyle равно PS\_USERSTYLE. |
| [setStyleEntry(int[] value)](#setStyleEntry-int---) | Получает или задает необязательный массив 32‑битных беззнаковых целых, определяющий длины штрихов и промежутков в линии, рисуемой этим пером, когда значение PenStyle равно PS\_USERSTYLE. |
| [getBrushDibPattern()](#getBrushDibPattern--) | Получает или задает шаблон DIB кисти. |
| [setBrushDibPattern(WmfDeviceIndependentBitmap value)](#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Получает или задает шаблон DIB кисти. |
### EmfLogPenEx() {#EmfLogPenEx--}
```
public EmfLogPenEx()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


Получает или задает стиль пера.

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


Получает или задает стиль пера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает или задает 32‑битное беззнаковое целое, которое указывает ширину линии, рисуемой пером. Если тип пера в поле PenStyle равен PS\_GEOMETRIC, это значение представляет ширину в логических единицах; в противном случае ширина задаётся в единицах устройства. Если тип пера в поле PenStyle равен PS\_COSMETIC, это значение ДОЛЖНО быть 0x00000001.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое указывает ширину линии, рисуемой пером. Если тип пера в поле PenStyle равен PS\_GEOMETRIC, это значение представляет ширину в логических единицах; в противном случае ширина задаётся в единицах устройства. Если тип пера в поле PenStyle равен PS\_COSMETIC, это значение ДОЛЖНО быть 0x00000001.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


Получает или задает 32‑битное беззнаковое целое, которое указывает стиль кисти для пера из перечисления WMF BrushStyle ([MS-WMF] раздел 2.1.1.4). Если тип пера в поле PenStyle равен PS\_GEOMETRIC, это значение ДОЛЖНО быть либо BS\_SOLID, либо BS\_HATCHED. Значение этого поля может быть BS\_NULL, но только если стиль линии, указанный в PenStyle, равен PS\_NULL. Стиль BS\_NULL СЛЕДУЕТ использовать для указания кисти, не оказывающей влияния.

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое указывает стиль кисти для пера из перечисления WMF BrushStyle ([MS-WMF] раздел 2.1.1.4). Если тип пера в поле PenStyle равен PS\_GEOMETRIC, это значение ДОЛЖНО быть либо BS\_SOLID, либо BS\_HATCHED. Значение этого поля может быть BS\_NULL, но только если стиль линии, указанный в PenStyle, равен PS\_NULL. Стиль BS\_NULL СЛЕДУЕТ использовать для указания кисти, не оказывающей влияния.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8). Интерпретация этого поля зависит от значения BrushStyle, как показано в таблице позже в этом разделе.

Значение: 32-битный цвет ARGB

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Получает или задает объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8). Интерпретация этого поля зависит от значения BrushStyle, как показано в таблице позже в этом разделе.

Значение: 32-битный цвет ARGB

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


Получает или задает шаблон штриховки кисти. Определение этого поля зависит от значения BrushStyle, как показано в таблице позже в этом разделе.

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


Получает или задает шаблон штриховки кисти. Определение этого поля зависит от значения BrushStyle, как показано в таблице позже в этом разделе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getNumStyleEntities() {#getNumStyleEntities--}
```
public int getNumStyleEntities()
```


Получает количество элементов в массиве, указанном в поле StyleEntry. Это значение ДОЛЖНО быть нулём, если PenStyle не указывает PS\_USERSTYLE.

**Returns:**
int
### getStyleEntry() {#getStyleEntry--}
```
public int[] getStyleEntry()
```


Получает или задает необязательный массив 32‑битных беззнаковых целых, определяющий длины штрихов и промежутков в линии, рисуемой этим пером, когда значение PenStyle равно PS\_USERSTYLE. Массив содержит количество элементов, указанное в NumStyleEntries, но используется так, как будто повторяется бесконечно. Первый элемент массива задаёт длину первого штриха. Второй элемент задаёт длину первого промежутка. Далее длины штрихов и промежутков чередуются. Если тип пера в поле PenStyle равен PS\_GEOMETRIC, длины задаются в логических единицах; в противном случае — в единицах устройства.

**Returns:**
int[]
### setStyleEntry(int[] value) {#setStyleEntry-int---}
```
public void setStyleEntry(int[] value)
```


Получает или задает необязательный массив 32‑битных беззнаковых целых, определяющий длины штрихов и промежутков в линии, рисуемой этим пером, когда значение PenStyle равно PS\_USERSTYLE. Массив содержит количество элементов, указанное в NumStyleEntries, но используется так, как будто повторяется бесконечно. Первый элемент массива задаёт длину первого штриха. Второй элемент задаёт длину первого промежутка. Далее длины штрихов и промежутков чередуются. Если тип пера в поле PenStyle равен PS\_GEOMETRIC, длины задаются в логических единицах; в противном случае — в единицах устройства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |

### getBrushDibPattern() {#getBrushDibPattern--}
```
public WmfDeviceIndependentBitmap getBrushDibPattern()
```


Получает или задает шаблон DIB кисти.

Значение: шаблон кисти dib.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBrushDibPattern(WmfDeviceIndependentBitmap value) {#setBrushDibPattern-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBrushDibPattern(WmfDeviceIndependentBitmap value)
```


Получает или задает шаблон DIB кисти.

Значение: шаблон кисти dib.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

