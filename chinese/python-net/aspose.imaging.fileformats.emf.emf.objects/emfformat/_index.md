---
title: "EmfFormat 类"
type: docs
weight: 60
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.objects/emfformat/
---

**Summary:** The EmrFormat object contains information that identifies the format of image data in an<br/>            EMR_COMMENT_MULTIFORMATS record(section 2.3.3.4.3).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfFormat

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfFormat()](#EmfFormat__1) | 初始化 EmfFormat 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| off_data | int | r/w | 获取或设置 32 位无符号整数，指定数据相对于 EMR_COMMENT_PUBLIC 记录中标识字段 <br/>            开始位置的偏移量（第 2.3.3.4 节）。<br/>            该偏移量必须是 32 位对齐的。 |
| signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | 获取或设置 32 位无符号整数，指定图像数据的格式。<br/>            该值必须属于 FormatSignature 枚举（第 2.1.14 节）。 |
| size_data | int | r/w | 获取或设置 32 位无符号整数，指定数据的字节大小 |
| 版本 | int | r/w | 获取或设置 32 位无符号整数，指定格式版本号。<br/>            如果 Signature 字段指定封装的 PostScript（EPS），<br/>            则该值必须为 0x00000001；否则，该值必须被忽略。 |


### Constructor: EmfFormat() {#EmfFormat__1}


```
 EmfFormat() 
```

初始化 EmfFormat 类的新实例

