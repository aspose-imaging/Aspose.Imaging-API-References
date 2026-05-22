---
title: "EmfHeaderExtension1 类"
type: docs
weight: 90
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---

**Summary:** The HeaderExtension1 object defines the first extension to the EMF metafile header. <br/>            It adds support for a PixelFormatDescriptor object (section 2.2.22) and OpenGL <br/>            [OPENGL] records (section 2.3.9).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1

**Inheritance:** EmfHeaderObject

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1__1) | 初始化一个新的 EmfHeaderExtension1 类实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| b_open_gl | int | r/w | 获取或设置一个 32 位无符号整数，指示元文件中是否存在 OpenGL 命令。<br/>            0x00000000 元文件中不存在 OpenGL 记录。<br/>            0x00000001 元文件中存在 OpenGL 记录。 |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置一个 WMF RectL 对象（[MS-WMF] 第 2.2.2.19 节），指定以设备单位表示的矩形（包含边界）<br/>            的范围，即可围绕存储在 <br/>            元文件中的图像绘制的最小矩形 |
| 字节 | int | r/w | 获取或设置一个 32 位无符号整数，指定元文件的大小（字节）。 |
| cb_pixel_format | int | r/w | 获取或设置一个 32 位无符号整数，指定 PixelFormatDescriptor 对象的大小。 <br/>            如果未设置像素格式，则必须为 0x00000000 |
| device | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | 获取或设置一个 WMF SizeL 对象（[MS-WMF] 第 2.2.2.22 节），指定参考设备的尺寸（像素） |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置一个 WMF RectL 对象，指定以 0.01 毫米 <br/>            为单位的矩形（包含边界）尺寸，即围绕存储在元文件中的图像的矩形 |
| 句柄 | int | r/w | 获取或设置一个 16 位无符号整数，指定在处理元文件期间将使用的图形对象数量 |
| millimeters | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | 获取或设置一个 WMF SizeL 对象，指定参考设备的尺寸（毫米） |
| n_desription | int | r/w | 获取或设置一个 32 位无符号整数，指定包含元文件内容描述的数组中的字符数 <br/>            。如果没有描述字符串，则为零。 |
| n_pal_entries | int | r/w | 获取或设置一个 32 位无符号整数，指定元文件 <br/>            调色板中的条目数。调色板位于 EMR_EOF 记录中 |
| off_description | int | r/w | 获取或设置一个 32 位无符号整数，指定从此记录开始到包含元文件内容描述的数组的偏移量 <br/>             |
| off_pixel_format | int | r/w | 获取或设置一个 32 位无符号整数，指定指向 PixelFormatDescriptor 对象的偏移量。<br/>            如果未设置像素格式，则必须为 0x00000000。 |
| record_signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | 获取或设置一个 32 位无符号整数，指定记录签名。此值必须为 ENHMETA_SIGNATURE，<br/>            来自 FormatSignature 枚举（第 2.1.14 节）。 |
| 记录 | int | r/w | 获取或设置一个 32 位无符号整数，指定元文件中的记录数 |
| 保留 | int | r/w | 获取或设置一个 16 位无符号整数，该值必须为 0x0000 且必须被忽略 |
| valid | bool | r | 获取一个值，指示此 [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) 是否有效。 |
| 版本 | int | r/w | 获取或设置 Version（4 字节）：一个指定 EMF 元文件互操作性的 32 位无符号整数。该值应为 0x00010000。 |


### Constructor: EmfHeaderExtension1() {#EmfHeaderExtension1__1}


```
 EmfHeaderExtension1() 
```

初始化一个新的 EmfHeaderExtension1 类实例

