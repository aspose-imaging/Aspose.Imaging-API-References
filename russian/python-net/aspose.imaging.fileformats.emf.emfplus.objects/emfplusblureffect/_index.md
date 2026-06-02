---
title: "Класс EmfPlusBlurEffect"
type: docs
weight: 100
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---

**Summary:** The BlurEffect object specifies a decrease in the difference in intensity between pixels in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlurEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect__1) | Инициализирует новый экземпляр класса EmfPlusBlurEffect |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blur_radius | float | r/w | Получает или задает 32-битное число с плавающей точкой, указывающее радиус размытия в пикселях,<br/>            определяющее количество пикселей, участвующих в вычислении нового значения данного пикселя.<br/>            Это значение ДОЛЖНО находиться в диапазоне от 0.0 до 255.0. |
| expand_edge | bool | r/w | Получает или задает 32-битное логическое значение, указывающее, расширяется ли растровое изображение на<br/>            величину, равную значению BlurRadius, для получения мягких краев. Это значение ДОЛЖНО быть<br/>            одним из следующих:<br/>            FALSE<br/>            0x00000000<br/>            Размер изображения НЕ ДОЛЖЕН изменяться, а его мягкие края ДОЛЖНЫ быть обрезаны до<br/>            размера BlurRadius.<br/>            TRUE<br/>            0x00000001<br/>            Размер изображения ДОЛЖЕН расширяться на величину, равную BlurRadius, для<br/>            получения мягких краев. |


### Constructor: EmfPlusBlurEffect() {#EmfPlusBlurEffect__1}


```
 EmfPlusBlurEffect() 
```

Инициализирует новый экземпляр класса EmfPlusBlurEffect

