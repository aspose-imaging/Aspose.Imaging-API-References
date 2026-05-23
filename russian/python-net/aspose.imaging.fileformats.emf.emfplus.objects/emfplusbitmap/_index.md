---
title: "Класс EmfPlusBitmap"
type: docs
weight: 50
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/
---

**Summary:** The EmfPlusBitmap object specifies a bitmap that contains a graphics image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBitmap

**Inheritance:** EmfPlusBaseImageData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBitmap()](#EmfPlusBitmap__1) | Инициализирует новый экземпляр класса EmfPlusBitmap |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bitmap_data | [EmfPlusBaseBitmapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebitmapdata/) | r/w | Получает или задает данные битмапа<br/>            BitmapData (variable): Данные переменной длины, определяющие объект данных битмапа, указанный в поле Type. <br/>            Содержание и формат данных могут различаться для каждого типа битмапа. |
| height | int | r/w | Получает или задает высоту битмапа<br/>            Height (4 байта): 32‑битное знаковое целое, определяющее высоту в пикселях области, занимаемой битмапом.<br/>            Если изображение сжато, согласно полю Type, это значение неопределено и ДОЛЖНО игнорироваться. |
| pixel_format | [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) | r/w | Получает или задает формат пикселей<br/>            PixelFormat (4 байта): 32‑битное беззнаковое целое, определяющее формат пикселей, из которых состоит изображение битмапа.<br/>            Поддерживаемые форматы пикселей указаны в перечислении [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) (section 2.1.1.25).<br/>            Если изображение сжато, согласно полю Type, это значение неопределено и ДОЛЖНО игнорироваться. |
| stride | int | r/w | Получает или задает шаг (stride) изображения<br/>            Stride (4 байта): 32‑битное знаковое целое, определяющее смещение в байтах между началом одной строки сканирования и следующей. Это значение равно количеству байт на пиксель, указанному в поле PixelFormat, умноженному на ширину в пикселях, указанную в поле Width. Значение этого поля ДОЛЖНО быть кратным четырём.<br/>            Если изображение сжато, согласно полю Type, это значение неопределено и ДОЛЖНО игнорироваться. |
| type | [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) | r/w | Получает или задает тип изображения<br/>            Type (4 байта): 32‑битное беззнаковое целое, определяющее тип данных в поле BitmapData. Это значение ДОЛЖНО быть определено в перечислении [EmfPlusBitmapDataType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbitmapdatatype/) (section 2.1.1.2). |
| width | int | r/w | Получает или задает ширину изображения<br/>            Width (4 байта): 32‑битное знаковое целое, определяющее ширину в пикселях области, занимаемой битмапом.<br/>            Если изображение сжато, согласно полю Type, это значение неопределено и ДОЛЖНО игнорироваться. |


### Constructor: EmfPlusBitmap() {#EmfPlusBitmap__1}


```
 EmfPlusBitmap() 
```

Инициализирует новый экземпляр класса EmfPlusBitmap

