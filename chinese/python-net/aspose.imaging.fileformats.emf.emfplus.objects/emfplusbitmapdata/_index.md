---
title: "EmfPlusBitmapData 类"
type: docs
weight: 60
url: /zh/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmapdata/
---

**Summary:** The EmfPlusBitmapData object specifies a bitmap image with pixel data.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBitmapData

**Inheritance:** EmfPlusBaseBitmapData

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfPlusBitmapData()](#EmfPlusBitmapData__1) | 初始化 EmfPlusBitmapData 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| colors | [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) | r/w | 获取或设置调色板颜色 <br/>            Colors（可变）：一个可选的 [EmfPlusPalette](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/) 对象（第 2.2.2.28 节），指定像素数据中使用的颜色调色板。<br/>            如果在 [EmfPlusBitmap](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap/) 对象的 PixelFormat 字段中设置了 I 标志，则此字段 必须存在。 |
| pixel_data | System.Byte | r/w | 获取或设置像素数据 <br/>            PixelData（可变）：一个字节数组，指定像素数据。此数据的大小和格式可以<br/>            从 EmfPlusBitmap 对象的字段中计算，包括来自<br/>            [EmfPlusPixelFormat](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/) 枚举（第 2.1.1.25 节）的像素格式。 |


### Constructor: EmfPlusBitmapData() {#EmfPlusBitmapData__1}


```
 EmfPlusBitmapData() 
```

初始化 EmfPlusBitmapData 类的新实例

