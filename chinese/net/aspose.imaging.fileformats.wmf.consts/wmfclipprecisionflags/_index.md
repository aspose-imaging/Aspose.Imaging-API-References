---
title: "枚举 WmfClipPrecisionFlags"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Wmf.Consts.WmfClipPrecisionFlags 枚举。ClipPrecision 标志指定裁剪精度，用于定义如何裁剪部分位于裁剪区域外的字符。这些标志可以组合以指定多个选项。"
type: docs
weight: 8310
url: /zh/net/aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---
## WmfClipPrecisionFlags enumeration

ClipPrecision 标志指定剪裁精度，该精度定义如何剪裁部分位于剪裁区域外的字符。这些标志可以组合以指定多个选项。

```csharp
[Flags]
public enum WmfClipPrecisionFlags : byte
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Default | `0` | 指定必须使用默认裁剪。 |
| Character | `1` | 不应使用此值。 |
| Stroke | `2` | 在枚举光栅化、TrueType 和矢量字体时，可能返回此值。[33]（Windows NT 3.1、Windows NT 3.5、Windows NT 3.51、Windows NT 4.0、Windows 2000 和 Windows XP：枚举字体时始终返回此值。） |
| LhAngles | `10` | 此值用于控制字体旋转，具体如下：- 如果设置，则所有字体的旋转应由坐标系的方向决定，即左手坐标系或右手坐标系。- 如果未设置，设备字体应逆时针旋转，但其他字体的旋转应由坐标系的方向决定。 |
| TtAlways | `20` | 不应使用此值[34]。[34] 在以下 Windows 版本中此值被忽略：- Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2 |
| DfaDisable | `40` | 此值指定应关闭字体关联[35]。[35] 此值在 Windows 95、Windows 98 和 Windows Millennium Edition 中不受支持。字体关联在 Windows 2000、Windows XP 和 Windows Server 2003 中已关闭。此值在以下 Windows 版本中被忽略：- Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2 |
| Embedded | `80` | 此值指定必须使用字体嵌入来渲染文档内容；嵌入的字体为只读。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


