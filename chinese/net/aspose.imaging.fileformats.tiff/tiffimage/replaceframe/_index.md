---
title: "TiffImage.ReplaceFrame"
second_title: "Aspose.Imaging for .NET API 参考"
description: "TiffImage 方法。用另一个帧替换指定位置的帧，轻松实现图像序列中的动态帧管理。将此方法集成到您的应用程序中，以提升帧操作的灵活性和精确度，确保图像内容的最佳组织和呈现。"
type: docs
weight: 320
url: /zh/net/aspose.imaging.fileformats.tiff/tiffimage/replaceframe/
---
## TiffImage.ReplaceFrame method

在指定位置无缝替换为另一帧，促进图像序列中的动态帧管理。集成此方法可提升帧操作的灵活性和精度，确保应用程序内图像内容的最佳组织和呈现。

```csharp
public TiffFrame ReplaceFrame(int index, TiffFrame newFrame)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | Int32 | 基于零的帧位置。 |
| newFrame | TiffFrame | 要替换指定 *index* 处帧的帧。 |

### 返回值

已删除的帧。

## 备注

注意：如果您不打算将该帧添加到其他 TiffImage，请务必释放（Dispose）该帧。

### 另请参见

* class [TiffFrame](../../tiffframe/)
* class [TiffImage](../)
* namespace [Aspose.Imaging.FileFormats.Tiff](../../tiffimage/)
* assembly [Aspose.Imaging](../../../)


