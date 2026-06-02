---
title: "EmfPlusCompressedImage.CompressedImageData"
second_title: "Aspose.Imaging for .NET API 参考"
description: "EmfPlusCompressedImage 属性。获取或设置一个字节数组，指定压缩图像。压缩类型必须从数据本身确定。"
type: docs
weight: 20
url: /zh/net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompressedimage/compressedimagedata/
---
## EmfPlusCompressedImage.CompressedImageData property

获取或设置字节数组，以指定压缩图像。压缩类型必须从数据本身确定。

```csharp
public byte[] CompressedImageData { get; set; }
```

## 备注

位图由 EmfPlusBitmap 对象（第 2.2.2.2 节）指定。如果在其 Type 字段中指定了 BitmapDataTypeCompressed，则 EmfPlusBitmap 对象的 BitmapData 字段中必须存在 EmfPlusCompressedImage 对象。此对象是通用的，用于不同类型的压缩数据，包括： 可交换图像文件格式（EXIF），如 [EXIF] 所述； 图形交换格式（GIF），如 [GIF] 所述； 联合图像专家组（JPEG），如 [JFIF] 所述； 可移植网络图形（PNG），如 [RFC2083] 和 [W3C - PNG] 所述；以及  标记图像文件格式（TIFF），如 [RFC3302] 和 [TIFF] 所述。

### 另请参见

* class [EmfPlusCompressedImage](../)
* namespace [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../emfpluscompressedimage/)
* assembly [Aspose.Imaging](../../../)


