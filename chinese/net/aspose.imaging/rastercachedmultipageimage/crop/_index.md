---
title: "RasterCachedMultipageImage.Crop"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterCachedMultipageImage 方法。裁剪图像。"
type: docs
weight: 220
url: /zh/net/aspose.imaging/rastercachedmultipageimage/crop/
---
## Crop(Rectangle) {#crop}

裁剪图像。

```csharp
public override void Crop(Rectangle rectangle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩形 | Rectangle | 矩形。 |

### 另请参见

* struct [Rectangle](../../rectangle/)
* class [RasterCachedMultipageImage](../)
* namespace [Aspose.Imaging](../../rastercachedmultipageimage/)
* assembly [Aspose.Imaging](../../../)

---

## Crop(int, int, int, int) {#crop_1}

使用位移裁剪图像。

```csharp
public override void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| leftShift | Int32 | 左移。 |
| rightShift | Int32 | 右移。 |
| topShift | Int32 | 上移。 |
| bottomShift | Int32 | 下移。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | 矩形不正确。- rectangle 或 Rectangle 必须位于图像边界内。- rectangle |
| [ImageException](../../../aspose.imaging.coreexceptions/imageexception/) | Can't crop image. Frame index: " + frameIndex or Can't crop image. |

### 另请参见

* class [RasterCachedMultipageImage](../)
* namespace [Aspose.Imaging](../../rastercachedmultipageimage/)
* assembly [Aspose.Imaging](../../../)


