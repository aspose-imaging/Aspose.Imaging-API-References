---
title: "EmfPolyTextOutW"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_POLYTEXTOUTW выводит одну или несколько строк Unicode‑текста, используя текущий шрифт и цвета текста."
type: docs
weight: 98
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolytextoutw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyTextOutW extends EmfDrawingRecordType
```

Запись EMR_POLYTEXTOUTW рисует одну или несколько строк Unicode‑текста, используя текущий шрифт и цвета текста.

Шрифт и цвета текста, используемые для вывода, задаются свойствами в текущем состоянии контекста устройства воспроизведения. EMR\_POLYTEXTOUTW ДОЛЖЕН быть эмулирован серией записей EMR\_EXTTEXTOUTW (раздел 2.3.5.7), по одной на строку.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPolyTextOutW(EmfRecord source)](#EmfPolyTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfPolyTextOutW`. |
| [EmfPolyTextOutW()](#EmfPolyTextOutW--) | Инициализирует новый экземпляр класса `EmfPolyTextOutW`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBounds()](#getBounds--) | Получает или задаёт объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник в единицах устройства. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Получает или задаёт объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник в единицах устройства. |
| [getIGraphicsMode()](#getIGraphicsMode--) | Получает или задаёт 32‑битное беззнаковое целое, которое определяет текущий графический режим из перечисления GraphicsMode (раздел 2.1.16). |
| [setIGraphicsMode(int value)](#setIGraphicsMode-int-) | Получает или задаёт 32‑битное беззнаковое целое, которое определяет текущий графический режим из перечисления GraphicsMode (раздел 2.1.16). |
| [getExScale()](#getExScale--) | Получает или задаёт 32‑битное значение с плавающей точкой, которое определяет масштаб X от единиц страницы до .01 мм, если графический режим — GM\_COMPATIBLE. |
| [setExScale(float value)](#setExScale-float-) | Получает или задаёт 32‑битное значение с плавающей точкой, которое определяет масштаб X от единиц страницы до .01 мм, если графический режим — GM\_COMPATIBLE. |
| [getEyScale()](#getEyScale--) | Получает или задаёт 32‑битное значение с плавающей точкой, которое определяет масштаб Y от единиц страницы до .01 мм, если графический режим — GM\_COMPATIBLE. |
| [setEyScale(float value)](#setEyScale-float-) | Получает или задаёт 32‑битное значение с плавающей точкой, которое определяет масштаб Y от единиц страницы до .01 мм, если графический режим — GM\_COMPATIBLE. |
| [getWEmrText()](#getWEmrText--) | Получает или задаёт массив объектов EmrText (раздел 2.2.5), которые определяют строки вывода в 16‑битных символах Unicode UTF16‑LE с атрибутами текста и значениями интервалов. |
| [setWEmrText(EmfText[] value)](#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---) | Получает или задаёт массив объектов EmrText (раздел 2.2.5), которые определяют строки вывода в 16‑битных символах Unicode UTF16‑LE с атрибутами текста и значениями интервалов. |
### EmfPolyTextOutW(EmfRecord source) {#EmfPolyTextOutW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyTextOutW(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfPolyTextOutW`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfPolyTextOutW() {#EmfPolyTextOutW--}
```
public EmfPolyTextOutW()
```


Инициализирует новый экземпляр класса `EmfPolyTextOutW`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Получает или задаёт объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник в единицах устройства.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Получает или задаёт объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который определяет ограничивающий прямоугольник в единицах устройства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getIGraphicsMode() {#getIGraphicsMode--}
```
public int getIGraphicsMode()
```


Получает или задаёт 32‑битное беззнаковое целое, которое определяет текущий графический режим из перечисления GraphicsMode (раздел 2.1.16).

**Returns:**
int
### setIGraphicsMode(int value) {#setIGraphicsMode-int-}
```
public void setIGraphicsMode(int value)
```


Получает или задаёт 32‑битное беззнаковое целое, которое определяет текущий графический режим из перечисления GraphicsMode (раздел 2.1.16).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getExScale() {#getExScale--}
```
public float getExScale()
```


Получает или задаёт 32‑битное значение с плавающей точкой, которое определяет масштаб X от единиц страницы до .01 мм, если графический режим — GM\_COMPATIBLE.

**Returns:**
float
### setExScale(float value) {#setExScale-float-}
```
public void setExScale(float value)
```


Получает или задаёт 32‑битное значение с плавающей точкой, которое определяет масштаб X от единиц страницы до .01 мм, если графический режим — GM\_COMPATIBLE.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getEyScale() {#getEyScale--}
```
public float getEyScale()
```


Получает или задаёт 32‑битное значение с плавающей точкой, которое определяет масштаб Y от единиц страницы до .01 мм, если графический режим — GM\_COMPATIBLE.

**Returns:**
float
### setEyScale(float value) {#setEyScale-float-}
```
public void setEyScale(float value)
```


Получает или задаёт 32‑битное значение с плавающей точкой, которое определяет масштаб Y от единиц страницы до .01 мм, если графический режим — GM\_COMPATIBLE.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getWEmrText() {#getWEmrText--}
```
public EmfText[] getWEmrText()
```


Получает или задаёт массив объектов EmrText (раздел 2.2.5), которые определяют строки вывода в 16‑битных символах Unicode UTF16‑LE с атрибутами текста и значениями интервалов. Количество объектов EmrText задаётся параметром cStrings.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfText[]
### setWEmrText(EmfText[] value) {#setWEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---}
```
public void setWEmrText(EmfText[] value)
```


Получает или задаёт массив объектов EmrText (раздел 2.2.5), которые определяют строки вывода в 16‑битных символах Unicode UTF16‑LE с атрибутами текста и значениями интервалов. Количество объектов EmrText задаётся параметром cStrings.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfText\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

