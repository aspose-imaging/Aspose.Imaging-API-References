---
title: "RasterCachedImage.AutoBrightnessContrast"
second_title: "Aspose.Imaging for .NET API 参考"
description: "RasterCachedImage 方法。对整个图像执行自动自适应亮度和对比度归一化。"
type: docs
weight: 60
url: /zh/net/aspose.imaging/rastercachedimage/autobrightnesscontrast/
---
## RasterCachedImage.AutoBrightnessContrast method

对整幅图像执行自动自适应亮度和对比度归一化。

```csharp
public override void AutoBrightnessContrast()
```

## 备注

此方法应用一系列高级自适应滤波器（CLAHE、自适应白色拉伸和自动白平衡），通过增强对比度、局部亮度和色彩保真度来提升图像的视觉质量。

**Filter pipeline:**

1. 对比度受限自适应直方图均衡 (CLAHE) – 提高局部对比度并增强微弱细节。
2. 自适应白色拉伸 – 在保护暗部特征的同时提升有效白色水平。
3. 自动白平衡 – 通过平衡通道直方图来校正色偏。

**Note:**

* Each filter stage uses its default settings. For custom parameters, apply filters individually.
* The method is intended for use in automated normalization scenarios (e.g., scan preprocessing, document pipelines).

## 示例

```csharp
// 图像预处理中的示例用法：
image.AutoBrightnessContrast();
```

### 另请参见

* class [RasterCachedImage](../)
* namespace [Aspose.Imaging](../../rastercachedimage/)
* assembly [Aspose.Imaging](../../../)


