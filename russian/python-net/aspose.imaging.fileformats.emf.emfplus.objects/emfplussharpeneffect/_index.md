---
title: "Класс EmfPlusSharpenEffect"
type: docs
weight: 630
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplussharpeneffect/
---

**Summary:** The SharpenEffect object specifies an increase in the difference in intensity between pixels in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusSharpenEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusSharpenEffect()](#EmfPlusSharpenEffect__1) | Инициализирует новый экземпляр класса EmfPlusSharpenEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| amount | float | r/w | Получает или задает 32-битное число с плавающей точкой, которое указывает разницу в интенсивности<br/>            между заданным пикселем и окружающими пикселями.<br/>            0 Указывает, что резкость НЕ ДОЛЖНА выполняться.<br/>            0 &lt; значение ≤ 100<br/>            По мере увеличения этого значения разница в интенсивности между пикселями ДОЛЖНА<br/>            увеличиваться. |
| радиус | float | r/w | Получает или задает 32-битное число с плавающей точкой, которое указывает радиус резкости в пикселях,<br/>            определяющий количество пикселей, участвующих в вычислении нового значения данного пикселя.<br/>            По мере увеличения этого значения количество пикселей, участвующих в расчёте, растёт, и<br/>            полученный битмап ДОЛЖЕН стать более резким. |


### Constructor: EmfPlusSharpenEffect() {#EmfPlusSharpenEffect__1}


```
 EmfPlusSharpenEffect() 
```

Инициализирует новый экземпляр класса EmfPlusSharpenEffect

