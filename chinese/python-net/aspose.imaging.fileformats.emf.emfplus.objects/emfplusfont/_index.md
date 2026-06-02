---
title: "EmfPlusFont 类"
type: docs
weight: 330
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfont/
---

**Summary:** The EmfPlusFont object specifies properties that determine the appearance of text, including<br/>            typeface, size, and style.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFont

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusFont()](#EmfPlusFont__1) | 初始化 EmfPlusFont 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| em_size | float | r/w | 获取或设置一个 32 位浮点值，指定字体的 em 大小，单位由 SizeUnit 字段指定 <br/>             |
| family_name | string | r/w | 获取或设置一个长度为 Length 的 Unicode 字符串，包含<br/>            字体系列的名称 |
| font_style_flags | [EmfPlusFontStyleFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusfontstyleflags/) | r/w | 获取或设置一个 32 位有符号整数，指定属性<br/>            字符字形，这些属性影响字体的外观，<br/>            如粗体和斜体。此值必须由<br/>            FontStyle 标志（第 2.1.2.4 节）组成。 |
| size_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | 获取或设置一个 32 位无符号整数，指定用于 <br/>            EmSize 字段的单位。这些通常是设计字体时使用的 <br/>            单位。该值必须位于 <br/>            UnitType 枚举（第 2.1.1.33 节）中。 |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | 获取或设置版本。 |


### Constructor: EmfPlusFont() {#EmfPlusFont__1}


```
 EmfPlusFont() 
```

初始化 EmfPlusFont 类的新实例

