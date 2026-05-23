---
title: "Класс EmfPlusPathGradientBrushData"
type: docs
weight: 500
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---

**Summary:** The EmfPlusPathGradientBrushData object specifies a path gradient for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData__1) | Инициализирует новый экземпляр класса EmfPlusPathGradientBrushData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| boundary_data | [EmfPlusBoundaryBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase/) | r/w | Получает или задает границу кисти градиента пути, которая задаётся либо путем, либо замкнутой кардинальной сплайной кривой. <br/>            Если флаг BrushDataPath установлен в поле BrushDataFlags, это поле ДОЛЖНО содержать объект EmfPlusBoundaryPathData (раздел 2.2.2.6); <br/>            в противном случае это поле ДОЛЖНО содержать объект EmfPlusBoundaryPointData (раздел 2.2.2.7). |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает данные в поле OptionalData.<br/>            Это значение ДОЛЖНО состоять из флагов BrushData (раздел 2.1.2.1). Следующие флаги относятся к кисти градиента пути: |
| center_argb_32_color | int | r/w | Получает или задает объект EmfPlusARGB (раздел 2.2.2.1), который определяет центральный цвет <br/>            кисти градиента пути, т.е. цвет, отображаемый в центральной точке кисти. <br/>            Цвет кисти постепенно меняется от цвета границы <br/>            к центральному цвету по мере перемещения от границы к центральной точке. |
| center_point_f | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Получает или задает объект EmfPlusARGB (раздел 2.2.2.1), который определяет центральный цвет кисти градиента пути, <br/>            т.е. цвет, отображаемый в центральной точке кисти. Цвет<br/>            кисти постепенно меняется от цвета границы к центральному цвету по мере перемещения<br/>            от границы к центральной точке. |
| optional_data | [EmfPlusPathGradientBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/) | r/w | Получает или задает необязательный объект EmfPlusPathGradientBrushOptionalData (раздел 2.2.2.30), который <br/>            определяет дополнительные данные для кисти градиента пути. <br/>            Конкретное содержание этого поля определяется значением поля BrushDataFlags. |
| surrounding_argb_32_colors | int[] | r/w | Получает или задает массив из SurroundingColorCount объектов EmfPlusARGB <br/>            которые определяют цвета для дискретных точек на границе кисти. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Получает или задает 32-битное знаковое целое из перечисления WrapMode (раздел 2.1.1.34), которое указывает<br/>            следует ли закрашивать область за пределами границы кисти. При закраске <br/>            за границей режим обтекания определяет, как повторяется цветовой градиент. |


### Constructor: EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData__1}


```
 EmfPlusPathGradientBrushData() 
```

Инициализирует новый экземпляр класса EmfPlusPathGradientBrushData

