---
title: "EmfPlusTextureBrushData 类"
type: docs
weight: 680
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---

**Summary:** The EmfPlusTextureBrushData object specifies a texture image for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData__1) | 初始化 EmfPlusTextureBrushData 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | 获取或设置一个 32 位无符号整数，指定 OptionalData 字段中的数据。 <br/>            此值必须由 BrushData 标志（第 2.1.2.1 节）组成。 <br/>            以下标志与纹理画刷相关<br/>            BrushDataTransform<br/>            BrushDataIsGammaCorrected<br/>            BrushDataDoNotTransform |
| optional_data | [EmfPlusTextureBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/) | r/w | 获取或设置一个可选的 EmfPlusTextureBrushOptionalData 对象（第 2.2.2.46 节），<br/>            用于指定纹理画刷的附加数据。此字段的具体内容由 BrushDataFlags 字段的值决定 |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | 获取或设置来自 WrapMode 枚举（第 2.1.1.34 节）的 32 位有符号整数，<br/>            用于指定当图像小于填充区域时，如何在形状上重复纹理图像。 |


### Constructor: EmfPlusTextureBrushData() {#EmfPlusTextureBrushData__1}


```
 EmfPlusTextureBrushData() 
```

初始化 EmfPlusTextureBrushData 类的新实例

