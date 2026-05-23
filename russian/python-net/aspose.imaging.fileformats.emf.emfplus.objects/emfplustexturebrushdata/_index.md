---
title: "Класс EmfPlusTextureBrushData"
type: docs
weight: 680
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---

**Summary:** The EmfPlusTextureBrushData object specifies a texture image for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData__1) | Инициализирует новый экземпляр класса EmfPlusTextureBrushData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает данные в поле OptionalData. <br/> Это значение ДОЛЖНО состоять из флагов BrushData (раздел 2.1.2.1). <br/> Следующие флаги относятся к кисти текстуры<br/> BrushDataTransform<br/> BrushDataIsGammaCorrected<br/> BrushDataDoNotTransform |
| optional_data | [EmfPlusTextureBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/) | r/w | Получает или задает необъект EmfPlusTextureBrushOptionalData (раздел 2.2.2.46), который <br/> указывает дополнительные данные для кисти текстуры. Конкретное содержание <br/> этого поля определяется значением поля BrushDataFlags. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Получает или задает 32-битное знаковое целое из перечисления WrapMode (раздел 2.1.1.34) <br/> которое указывает, как повторять изображение текстуры по форме, когда <br/> изображение меньше области заполнения. |


### Constructor: EmfPlusTextureBrushData() {#EmfPlusTextureBrushData__1}


```
 EmfPlusTextureBrushData() 
```

Инициализирует новый экземпляр класса EmfPlusTextureBrushData

