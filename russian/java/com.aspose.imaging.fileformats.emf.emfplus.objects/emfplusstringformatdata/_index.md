---
title: "EmfPlusStringFormatData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusStringFormatData указывает позиции табуляции и символов для графической строки."
type: docs
weight: 75
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusStringFormatData extends EmfPlusStructureObjectType
```

Объект EmfPlusStringFormatData указывает позиции табуляции и символов для графической строки.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusStringFormatData()](#EmfPlusStringFormatData--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getTabStops()](#getTabStops--) | Получает или задает необязательный массив значений с плавающей точкой, который указывает расположение необязательных табуляций для этого объекта. |
| [setTabStops(float[] value)](#setTabStops-float---) | Получает или задает необязательный массив значений с плавающей точкой, который указывает расположение необязательных табуляций для этого объекта. |
| [getCharRange()](#getCharRange--) | Получает или задает необязательный массив объектов RangeCount EmfPlusCharacterRange, которые указывают диапазон позиций символов в строке текста. |
| [setCharRange(EmfPlusCharacterRange[] value)](#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---) | Получает или задает необязательный массив объектов RangeCount EmfPlusCharacterRange, которые указывают диапазон позиций символов в строке текста. |
### EmfPlusStringFormatData() {#EmfPlusStringFormatData--}
```
public EmfPlusStringFormatData()
```


### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Получает или задает необязательный массив значений с плавающей точкой, который указывает расположение необязательных табуляций для этого объекта. Каждое значение табуляции представляет количество пробелов между табуляциями или, для первой табуляции, количество пробелов между началом строки текста и первой табуляцией. Это поле ДОЛЖНО присутствовать, если значение поля TabStopCount в объекте EmfPlusStringFormat больше 0.

**Returns:**
float[]
### setTabStops(float[] value) {#setTabStops-float---}
```
public void setTabStops(float[] value)
```


Получает или задает необязательный массив значений с плавающей точкой, который указывает расположение необязательных табуляций для этого объекта. Каждое значение табуляции представляет количество пробелов между табуляциями или, для первой табуляции, количество пробелов между началом строки текста и первой табуляцией. Это поле ДОЛЖНО присутствовать, если значение поля TabStopCount в объекте EmfPlusStringFormat больше 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] |  |

### getCharRange() {#getCharRange--}
```
public EmfPlusCharacterRange[] getCharRange()
```


Получает или задает необязательный массив объектов RangeCount EmfPlusCharacterRange, которые указывают диапазон позиций символов в строке текста. Ограничивающая область определяется площадью дисплея, занятый группой символов, указанных диапазоном символов. Это поле ДОЛЖНО присутствовать, если значение поля RangeCount в объекте EmfPlusStringFormat больше 0.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange[]
### setCharRange(EmfPlusCharacterRange[] value) {#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---}
```
public void setCharRange(EmfPlusCharacterRange[] value)
```


Получает или задает необязательный массив объектов RangeCount EmfPlusCharacterRange, которые указывают диапазон позиций символов в строке текста. Ограничивающая область определяется площадью дисплея, занятый группой символов, указанных диапазоном символов. Это поле ДОЛЖНО присутствовать, если значение поля RangeCount в объекте EmfPlusStringFormat больше 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusCharacterRange\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscharacterrange) |  |

