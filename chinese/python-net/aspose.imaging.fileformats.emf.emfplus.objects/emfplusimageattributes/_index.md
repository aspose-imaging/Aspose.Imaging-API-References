---
title: "EmfPlusImageAttributes 类"
type: docs
weight: 390
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---

**Summary:** The EmfPlusImageAttributes object specifies how bitmap image<br/>            colors are manipulated during rendering.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageAttributes

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes__1) | 初始化 EmfPlusImageAttributes 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| clamp_argb_32_color | int | r/w | 获取或设置 EmfPlusARGB（第 2.2.2.1 节）对象，该对象指定在 WrapMode 值为 WrapModeClamp 时使用的边缘颜色。<br/>            当由 EmfPlusDrawImage（第 2.3.4.8 节）记录处理的源矩形大于图像本身时，此颜色可见。 |
| object_clamp | [EmfPlusObjectClamp](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjectclamp/) | r/w | 获取或设置指定对象夹持行为的 32 位有符号整数。<br/>            该值在此对象被应用于正在绘制的图像之前不会使用。此值必须是下表中定义的值之一。 |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | 获取或设置版本。 |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | 获取或设置一个 32 位无符号整数，用于指定如何使用 WrapMode 枚举（第 2.1.1.34 节）中的值处理边缘条件。 |


### Constructor: EmfPlusImageAttributes() {#EmfPlusImageAttributes__1}


```
 EmfPlusImageAttributes() 
```

初始化 EmfPlusImageAttributes 类的新实例

