---
title: "EmfUniversalFontId 类"
type: docs
weight: 280
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---

**Summary:** The UniversalFontId object defines a mechanism for identifying fonts in EMF metafiles.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfUniversalFontId()](#EmfUniversalFontId__1) | 初始化 EmfUniversalFontId 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| checksum | int | r/w | 获取或设置一个 32 位无符号整数，作为字体的校验和。<br/>            校验和值具有以下含义。<br/>            0x00000000  该对象是设备字体。 <br/>            0x00000001  该对象是已安装在客户端机器上的 Type 1 字体，并且<br/>            被 PostScript 打印机驱动程序枚举为设备字体。 <br/>            0x00000002  该对象不是字体，而是 Type 1 光栅化器。 <br/>            3 ≤ value   该对象是位图、矢量或 TrueType 字体，或由 Type 1 光栅化器创建的 Type 1 光栅化字体。 |
| index | int | r/w | 获取或设置一个 32 位无符号整数，作为与字体对象关联的索引。<br/>            此字段的含义由字体类型决定。 |


### Constructor: EmfUniversalFontId() {#EmfUniversalFontId__1}


```
 EmfUniversalFontId() 
```

初始化 EmfUniversalFontId 类的新实例

