---
title: "类 FontSettings"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FontSettings 类。通用成像矢量格式渲染器的字体设置"
type: docs
weight: 9520
url: /zh/net/aspose.imaging/fontsettings/
---
## FontSettings class

通用成像矢量格式渲染器字体设置。

```csharp
public static class FontSettings
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [DefaultFontName](../../aspose.imaging/fontsettings/defaultfontname/) { get; set; } | 获取或设置字体的默认名称。 |
| static [GetSystemAlternativeFont](../../aspose.imaging/fontsettings/getsystemalternativefont/) { get; set; } | 获取或设置一个值，指示是否[获取替代字体]。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [GetDefaultFontsFolders](../../aspose.imaging/fontsettings/getdefaultfontsfolders/)() | 获取默认的字体文件夹。 |
| static [GetFontsFolders](../../aspose.imaging/fontsettings/getfontsfolders/)() | 获取包含 Aspose.Words 查找 TrueType 字体的文件夹列表的数组副本。 |
| static [Reset](../../aspose.imaging/fontsettings/reset/)() | 将字体文件夹和默认字体名称重置为系统默认值。 |
| static [SetFontsFolder](../../aspose.imaging/fontsettings/setfontsfolder/)(string) | 这是一个指向 [`SetFontsFolders`](./setfontsfolders/) 的快捷方式，用于仅设置一个字体目录。不会对字体文件夹执行任何检查。 |
| static [SetFontsFolders](../../aspose.imaging/fontsettings/setfontsfolders/)(string[], bool) | 设置加载 TrueType 字体的文件夹并清除所有已加载的字体。对字体文件夹不执行任何检查。 |
| static [UpdateFonts](../../aspose.imaging/fontsettings/updatefonts/)() | 更新包含文字图层的 PSD 文件的字体缓存。此方法确保在处理 PSD 文件时，会考虑使用 FontSettings.SetFontsFolder(fontsFolder) 方法设置的 fontsFolder 文件夹中的字体，或在调用 FontSettings.Reset() 重置字体后使用的字体。请在每次为 PSD 图像调用 FontSettings.SetFontsFolder(fontsFolder) 或 FontSettings.Reset() 时使用此方法。如果不调用此方法，则无法保证字体会被更新。 |

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


