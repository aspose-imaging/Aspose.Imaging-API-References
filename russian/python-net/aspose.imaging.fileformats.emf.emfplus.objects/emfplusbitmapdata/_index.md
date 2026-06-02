---
title: "Класс EmfPlusBitmapData"
type: docs
weight: 60
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/
---

**Summary:** The EmfPlusBitmapData object specifies a bitmap image with pixel data.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBitmapData

**Inheritance:** EmfPlusBaseBitmapData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBitmapData()](#EmfPlusBitmapData__1) | Инициализирует новый экземпляр класса EmfPlusBitmapData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| colors | [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) | r/w | Получает или задает цвета палитры <br/>            Colors (variable): Необязательный объект [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) (раздел 2.2.2.28), который определяет палитру<br/>            цветов, используемых в данных пикселей. Это поле ДОЛЖНО присутствовать, если флаг I установлен в поле PixelFormat объекта<br/>            [EmfPlusBitmap](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/). |
| pixel_data | System.Byte | r/w | Получает или задает данные пикселей <br/>            PixelData (variable): Массив байтов, определяющий данные пикселей. Размер и формат этих данных могут быть<br/>            вычислены из полей объекта EmfPlusBitmap, включая формат пикселей из<br/>            перечисления [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) (раздел 2.1.1.25). |


### Constructor: EmfPlusBitmapData() {#EmfPlusBitmapData__1}


```
 EmfPlusBitmapData() 
```

Инициализирует новый экземпляр класса EmfPlusBitmapData

