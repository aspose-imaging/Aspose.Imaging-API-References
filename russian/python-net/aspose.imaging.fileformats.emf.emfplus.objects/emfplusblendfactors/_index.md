---
title: "Класс EmfPlusBlendFactors"
type: docs
weight: 90
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/
---

**Summary:** The EmfPlusBlendFactors object specifies positions and factors for the blend pattern of a gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendFactors

**Inheritance:** EmfPlusBlendBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBlendFactors()](#EmfPlusBlendFactors__1) | Инициализирует новый экземпляр класса EmfPlusBlendFactors |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend_factors | float[] | r/w | Получает или задает массив 32-битных значений с плавающей запятой PositionCount, которые <br/>            определяют пропорции цветов в позициях, заданных в поле BlendPositions. <br/>            Каждое значение ДОЛЖНО быть числом в диапазоне от 0.0 до 1.0 включительно. |
| blend_positions | float[] | r/w | Получает или задает позиции смешивания<br/>            Массив 32-битных значений с плавающей запятой PositionCount<br/>             определяющих пропорции расстояния вдоль линии градиента.<br/>            Каждый элемент ДОЛЖЕН быть числом в диапазоне от 0.0 до 1.0 включительно. <br/>            Для линейной кисти градиента 0.0 представляет начальную точку <br/>            и 1.0 представляет конечную точку. Для кисти градиента по пути <br/>            0.0 представляет середину, а 1.0 — конечную точку. |


### Constructor: EmfPlusBlendFactors() {#EmfPlusBlendFactors__1}


```
 EmfPlusBlendFactors() 
```

Инициализирует новый экземпляр класса EmfPlusBlendFactors

