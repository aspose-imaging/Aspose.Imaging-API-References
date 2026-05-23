---
title: "Класс EmfPlusTextureBrushOptionalData"
type: docs
weight: 690
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---

**Summary:** he EmfPlusTextureBrushOptionalData object specifies optional data for a texture brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData__1) | Инициализирует новый экземпляр класса EmfPlusTextureBrushOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| image_object | [EmfPlusImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/) | r/w | Получает или задает необъект EmfPlusImage (раздел 2.2.1.4), который указывает<br/>            текстуру кисти. Это поле ДОЛЖНО присутствовать, если размер <br/>            записи EmfPlusObject (раздел 2.3.5.1), определяющей эту текстурную <br/>            кисть, достаточно велик, чтобы разместить объект EmfPlusImage <br/>            в дополнение к обязательным полям объекта EmfPlusTextureBrushData <br/>            и, при необходимости, объекту EmfPlusTransformMatrix. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Получает или задает необъект EmfPlusTransformMatrix (раздел 2.2.2.47) <br/>            который определяет преобразование из мирового пространства в пространство устройства для<br/>            текстурной кисти. Это поле ДОЛЖНО присутствовать, если флаг BrushDataTransform <br/>            установлен в поле BrushDataFlags объекта EmfPlusTextureBrushData. |


### Constructor: EmfPlusTextureBrushOptionalData() {#EmfPlusTextureBrushOptionalData__1}


```
 EmfPlusTextureBrushOptionalData() 
```

Инициализирует новый экземпляр класса EmfPlusTextureBrushOptionalData

