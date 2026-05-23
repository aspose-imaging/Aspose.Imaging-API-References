---
title: "EmfPlusBlendColors Class"
type: docs
weight: 80
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/
---

**Summary:** The EmfPlusBlendColors object specifies positions and colors for the blend pattern of a gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendColors

**Inheritance:** EmfPlusBlendBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBlendColors()](#EmfPlusBlendColors__1) | Инициализирует новый экземпляр класса EmfPlusBlendColors |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend_argb_32_colors | int[] | r/w | Получает или задает массив из PositionCount объектов EmfPlusARGB (раздел 2.2.2.1), который <br/>            определяет цвета в позициях, заданных в поле BlendPositions. |
| blend_positions | float[] | r/w | Получает или задает позиции смешивания<br/>            Массив 32-битных значений с плавающей запятой PositionCount<br/>             определяющих пропорции расстояния вдоль линии градиента.<br/>            Каждый элемент ДОЛЖЕН быть числом в диапазоне от 0.0 до 1.0 включительно. <br/>            Для линейной кисти градиента 0.0 представляет начальную точку <br/>            и 1.0 представляет конечную точку. Для кисти градиента по пути <br/>            0.0 представляет середину, а 1.0 — конечную точку. |


### Constructor: EmfPlusBlendColors() {#EmfPlusBlendColors__1}


```
 EmfPlusBlendColors() 
```

Инициализирует новый экземпляр класса EmfPlusBlendColors

