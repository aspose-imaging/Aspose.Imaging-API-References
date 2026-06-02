---
title: "Класс EmfLogBrushEx"
type: docs
weight: 120
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---

**Summary:** The LogBrushEx object defines the style, color, and pattern of a device-independent brush.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfLogBrushEx()](#EmfLogBrushEx__1) | Инициализирует новый экземпляр класса EmfLogBrushEx |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| argb_32_color_ref | int | r/w | Получает или задает 32-битный объект WMF ColorRef ([MS-WMF] раздел 2.2.2.8), определяющий <br/>            цвет. Интерпретация этого поля зависит от значения BrushStyle, как объяснено в <br/>            следующей таблице. |
| brush_hatch | [EmfHatchStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfhatchstyle/) | r/w | Получает или задает 32-битное беззнаковое поле, содержащее данные штриховки кисти. Его <br/>            интерпретация зависит от значения BrushStyle, |
| brush_style | [WmfBrushStyle](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfbrushstyle/) | r/w | Получает или задает 32-битное беззнаковое целое, определяющее стиль кисти. Значение ДОЛЖНО <br/>            быть элементом перечисления WMF BrushStyle ([MS-WMF] раздел 2.1.1.4). Значения стилей, поддерживаемые в этой структуре, перечислены позже в этом разделе. Стиль BS_NULL ДОЛЖЕН использоваться для указания кисти, не оказывающей влияния. |


### Constructor: EmfLogBrushEx() {#EmfLogBrushEx__1}


```
 EmfLogBrushEx() 
```

Инициализирует новый экземпляр класса EmfLogBrushEx

