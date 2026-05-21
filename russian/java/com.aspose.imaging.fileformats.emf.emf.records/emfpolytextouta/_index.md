---
title: "EmfPolyTextOutA"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_POLYTEXTOUTA выводит одну или несколько строк ASCII‑текста, используя текущий шрифт и цвета текста."
type: docs
weight: 97
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolytextouta/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPolyTextOutA extends EmfDrawingRecordType
```

Запись EMR_POLYTEXTOUTA рисует одну или несколько строк ASCII‑текста, используя текущий шрифт и цвета текста.

Шрифт и цвета текста, используемые для вывода, задаются свойствами в текущем состоянии контекста устройства воспроизведения. EMR\_POLYTEXTOUTA ДОЛЖЕН эмулироваться серией записей EMR\_EXTTEXTOUTW (раздел 2.3.5.7), по одной на строку. Это требует преобразования строки ASCII‑текста в каждом объекте EmrText в кодировку Unicode UTF16-LE.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPolyTextOutA(EmfRecord source)](#EmfPolyTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfPolyTextOutA`. |
| [EmfPolyTextOutA()](#EmfPolyTextOutA--) | Инициализирует новый экземпляр класса [EmfPolyTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolytextouta). |
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
| [getAEmrText()](#getAEmrText--) | Получает или задаёт массив объектов EmrText (раздел 2.2.5), которые определяют выводимые строки в 8‑битных ASCII‑символах, с атрибутами текста и значениями интервалов. |
| [setAEmrText(EmfText[] value)](#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---) | Получает или задаёт массив объектов EmrText (раздел 2.2.5), которые определяют выводимые строки в 8‑битных ASCII‑символах, с атрибутами текста и значениями интервалов. |
### EmfPolyTextOutA(EmfRecord source) {#EmfPolyTextOutA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyTextOutA(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfPolyTextOutA`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfPolyTextOutA() {#EmfPolyTextOutA--}
```
public EmfPolyTextOutA()
```


Инициализирует новый экземпляр класса [EmfPolyTextOutA](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolytextouta).

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

### getAEmrText() {#getAEmrText--}
```
public EmfText[] getAEmrText()
```


Получает или задаёт массив объектов EmrText (раздел 2.2.5), которые определяют выводимые строки в 8‑битных ASCII‑символах, с атрибутами текста и значениями интервалов. Количество объектов EmrText задаётся полем cStrings.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfText[]
### setAEmrText(EmfText[] value) {#setAEmrText-com.aspose.imaging.fileformats.emf.emf.objects.EmfText---}
```
public void setAEmrText(EmfText[] value)
```


Получает или задаёт массив объектов EmrText (раздел 2.2.5), которые определяют выводимые строки в 8‑битных ASCII‑символах, с атрибутами текста и значениями интервалов. Количество объектов EmrText задаётся полем cStrings.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfText\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftext) |  |

