---
title: "EmfPlusTextureBrushOptionalData 类"
type: docs
weight: 690
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---

**Summary:** he EmfPlusTextureBrushOptionalData object specifies optional data for a texture brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData__1) | 初始化 EmfPlusTextureBrushOptionalData 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| image_object | [EmfPlusImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/) | r/w | 获取或设置 一个可选的 EmfPlusImage 对象（第 2.2.1.4 节），用于指定<br/> 画笔纹理。如果定义此纹理画笔的 EmfPlusObject 记录（第 2.3.5.1 节）的大小足以容纳一个 EmfPlusImage 对象，<br/> 除了 EmfPlusTextureBrushData 对象的必需字段外，还可选地包含一个 EmfPlusTransformMatrix 对象，则此字段必须存在。 |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置 一个可选的 EmfPlusTransformMatrix 对象（第 2.2.2.47 节）<br/> 指定纹理画笔的世界空间到设备空间的变换。如果在 EmfPlusTextureBrushData 对象的 BrushDataFlags 字段中设置了 BrushDataTransform 标志，则此字段必须存在。 |


### Constructor: EmfPlusTextureBrushOptionalData() {#EmfPlusTextureBrushOptionalData__1}


```
 EmfPlusTextureBrushOptionalData() 
```

初始化 EmfPlusTextureBrushOptionalData 类的新实例。

