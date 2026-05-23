---
title: "EmfPlusColorCurveEffect Class"
type: docs
weight: 180
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---

**Summary:** The ColorCurveEffect object specifies one of eight adjustments to the color curve of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusColorCurveEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect__1) | Инициализирует новый экземпляр класса EmfPlusColorCurveEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| adjustment_intensity | int | r/w | Получает или задает 32-битное знаковое целое, указывающее интенсивность коррекции кривой для цветового канала, указанного в CurveChannel. Диапазоны значимых значений для этого поля зависят от значения CurveAdjustment, как указано ниже:<br/>Диапазон коррекции экспозиции:<br/>-255 ≤ value &lt; 0 По мере уменьшения значения экспозиция изображения ДОЛЖНА уменьшаться.<br/>0 Значение 0 указывает, что экспозиция НЕ ДОЛЖНА изменяться.<br/>0 &lt; value ≤ 255 По мере увеличения значения экспозиция изображения ДОЛЖНА увеличиваться.<br/>Диапазон коррекции плотности:<br/>-255 ≤ value &lt; 0 По мере уменьшения значения плотность изображения ДОЛЖНА уменьшаться, что приводит к более темному изображению.<br/>0 Значение 0 указывает, что плотность НЕ ДОЛЖНА изменяться.<br/>0 &lt; value ≤ 255 По мере увеличения значения плотность изображения ДОЛЖНА увеличиваться.<br/>Диапазон коррекции контрастности:<br/>-100 ≤ value &lt; 0 По мере уменьшения значения контрастность изображения ДОЛЖНА уменьшаться.<br/>0 Значение 0 указывает, что контрастность НЕ ДОЛЖНА изменяться.<br/>0 &lt; value ≤ 100 По мере увеличения значения контрастность изображения ДОЛЖНА увеличиваться.<br/>Диапазон коррекции светлых участков:<br/>-100 ≤ value &lt; 0 По мере уменьшения значения светлые области изображения ДОЛЖНЫ становиться темнее.<br/>0 Значение 0 указывает, что светлые участки НЕ ДОЛЖНЫ изменяться.<br/>0 &lt; value ≤ 100 По мере увеличения значения светлые области изображения ДОЛЖНЫ становиться светлее.<br/>Диапазон коррекции теней:<br/>-100 ≤ value &lt; 0 По мере уменьшения значения темные области изображения ДОЛЖНЫ становиться темнее.<br/>0 Значение 0 указывает, что тени НЕ ДОЛЖНЫ изменяться.<br/>0 &lt; value ≤ 100 По мере увеличения значения темные области изображения ДОЛЖНЫ становиться светлее.<br/>Диапазон коррекции насыщенности белого:<br/>0 — 255 По мере увеличения значения верхний предел диапазона интенсивностей цветового канала увеличивается.<br/>Диапазон коррекции насыщенности черного:<br/>0 — 255 По мере увеличения значения нижний предел диапазона интенсивностей цветового канала увеличивается. |
| curve_adjustment | [EmfPlusCurveAdjustments](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/) | r/w | Получает или задает 32-битное беззнаковое целое, указывающее коррекцию кривой<br/>            применяемую к цветам в битмапе. Это значение ДОЛЖНО быть определено в перечислении CurveAdjustments<br/>            (section 2.1.1.7). |
| curve_channel | [EmfPlusCurveChannel](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurvechannel/) | r/w | Получает или задает 32-битное беззнаковое целое, указывающее цветовой канал, к которому применяется коррекция кривой. Это значение ДОЛЖНО быть определено в перечислении CurveChannel<br/>            (section 2.1.1.8). |


### Constructor: EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect__1}


```
 EmfPlusColorCurveEffect() 
```

Инициализирует новый экземпляр класса EmfPlusColorCurveEffect

