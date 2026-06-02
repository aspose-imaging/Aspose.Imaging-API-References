---
title: "Класс EmfPlusLevelsEffect"
type: docs
weight: 420
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---

**Summary:** The LevelsEffect object specifies adjustments to the highlights, midtones, and shadows of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLevelsEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect__1) | Инициализирует новый экземпляр класса EmfPlusLevelsEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| выделение | int | r/w | Получает или задает значение, указывающее, насколько осветлять блики изображения. Значения каналов цвета в верхней части диапазона интенсивности изменяются сильнее, чем значения, близкие к середине или нижнему концу, что позволяет осветлить изображение без потери контраста между более темными участками изображения.<br/>0 ≤ value &lt; Указывает, что блики с процентом интенсивности выше этого порога ДОЛЖНЫ быть увеличены до 100.<br/>100 Указывает, что блики НЕ ДОЛЖНЫ изменяться. |
| mid_tone | int | r/w | Получает или задает значение, указывающее, насколько осветлять или затемнять средние тона изображения. Значения каналов цвета в середине диапазона интенсивности изменяются сильнее, чем значения, близкие к верхнему или нижнему концу, что позволяет осветлять или затемнять изображение без потери контраста между самыми темными и самыми светлыми участками изображения.<br/>-100 ≤ value &lt; 0 Указывает, что средние тона делаются темнее.<br/>0 Указывает, что средние тона НЕ ДОЛЖНЫ изменяться.<br/>0 &lt; value ≤ 100 Указывает, что средние тона делаются светлее. |
| shadow | int | r/w | Получает или задает значение, указывающее, насколько затемнять тени изображения. Значения каналов цвета в нижней части диапазона интенсивности изменяются сильнее, чем значения, близкие к середине или верхнему концу, что позволяет затемнять изображение без потери контраста между более светлыми участками изображения.<br/>0 Указывает, что тени НЕ ДОЛЖНЫ изменяться.<br/>0 &lt; value ≤ 100 Указывает, что тени с процентом интенсивности ниже этого порога становятся темнее. |


### Constructor: EmfPlusLevelsEffect() {#EmfPlusLevelsEffect__1}


```
 EmfPlusLevelsEffect() 
```

Инициализирует новый экземпляр класса EmfPlusLevelsEffect

