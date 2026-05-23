---
title: "Класс EmfPlusStringFormatData"
type: docs
weight: 660
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---

**Summary:** The EmfPlusStringFormatData object specifies tab stops and character positions for a graphics string.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormatData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusStringFormatData()](#EmfPlusStringFormatData__1) | Инициализирует новый экземпляр класса EmfPlusStringFormatData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| char_range | [EmfPlusCharacterRange[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscharacterrange/) | r/w | Получает или задает необязательный массив RangeCount объектов EmfPlusCharacterRange <br/>            , определяющих диапазон позиций символов <br/>            в строке текста. Ограничивающая область определяется<br/>            областью отображения, занятой группой <br/>            символов, указанных диапазоном символов.<br/>            Это поле ДОЛЖНО присутствовать, если значение поля RangeCount<br/>            в объекте EmfPlusStringFormat больше 0. |
| табуляции | float[] | r/w | Получает или задает необязательный массив значений с плавающей точкой, определяющих <br/>            расположения необязательных табуляций для этого объекта. Каждое значение табуляции представляет количество пробелов между табуляциями или, для первой табуляции, количество пробелов <br/>            между началом строки текста и первой табуляцией. <br/>            Это поле ДОЛЖНО присутствовать, если значение поля TabStopCount <br/>            в объекте EmfPlusStringFormat больше 0. |


### Constructor: EmfPlusStringFormatData() {#EmfPlusStringFormatData__1}


```
 EmfPlusStringFormatData() 
```

Инициализирует новый экземпляр класса EmfPlusStringFormatData

