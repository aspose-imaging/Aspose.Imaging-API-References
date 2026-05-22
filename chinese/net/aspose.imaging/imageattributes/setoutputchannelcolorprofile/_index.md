---
title: "ImageAttributes.SetOutputChannelColorProfile"
second_title: "Aspose.Imaging for .NET API 参考"
description: "ImageAttributes 方法。为默认类别设置输出通道的 colorprofile 文件。"
type: docs
weight: 180
url: /zh/net/aspose.imaging/imageattributes/setoutputchannelcolorprofile/
---
## SetOutputChannelColorProfile(string) {#setoutputchannelcolorprofile}

为默认类别设置输出通道的色彩配置文件。

```csharp
public void SetOutputChannelColorProfile(string colorProfileFilename)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| colorProfileFilename | String | color-profile 文件的路径名。如果该文件位于 %SystemRoot%\\System32\\Spool\\Drivers\\Color 目录中，此参数可以仅为文件名。否则，此参数必须是完整的路径名。 |

### 另请参见

* class [ImageAttributes](../)
* namespace [Aspose.Imaging](../../imageattributes/)
* assembly [Aspose.Imaging](../../../)

---

## SetOutputChannelColorProfile(string, ColorAdjustType) {#setoutputchannelcolorprofile_1}

为指定类别设置输出通道的色彩配置文件。

```csharp
public void SetOutputChannelColorProfile(string colorProfileFilename, ColorAdjustType type)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| colorProfileFilename | String | color-profile 文件的路径名。如果该文件位于 %SystemRoot%\\System32\\Spool\\Drivers\\Color 目录中，此参数可以仅为文件名。否则，此参数必须是完整的路径名。 |
| type | ColorAdjustType | [`ColorAdjustType`](../../coloradjusttype/) 的一个元素，指定为哪个类别设置输出通道的 color-profile 文件。 |

### 另请参见

* enum [ColorAdjustType](../../coloradjusttype/)
* class [ImageAttributes](../)
* namespace [Aspose.Imaging](../../imageattributes/)
* assembly [Aspose.Imaging](../../../)


