---
title: "FontSettings.UpdateFonts"
second_title: "Aspose.Imaging for .NET API 参考"
description: "FontSettings 方法。更新包含文本图层的 PSD 文件的字体缓存。此方法保证在处理 PSD 文件时，会考虑使用 FontSettings.SetFontsFolderfontsFolder 方法的 fontsFolder 文件夹中的字体，或在使用 FontSettings.Reset 重置字体后。请在每次为 PSD 图像调用 FontSettings.SetFontsFolderfontsFolder 或 FontSettings.Reset 时使用此方法。如果未调用此方法，则无法保证字体会被更新。"
type: docs
weight: 80
url: /zh/net/aspose.imaging/fontsettings/updatefonts/
---
## FontSettings.UpdateFonts method

更新包含文字图层的 PSD 文件的字体缓存。此方法确保在处理 PSD 文件时，会考虑使用 FontSettings.SetFontsFolder(fontsFolder) 方法设置的 fontsFolder 文件夹中的字体，或在调用 FontSettings.Reset() 重置字体后使用的字体。请在每次为 PSD 图像调用 FontSettings.SetFontsFolder(fontsFolder) 或 FontSettings.Reset() 时使用此方法。如果不调用此方法，则无法保证字体会被更新。

```csharp
public static void UpdateFonts()
```

### 另请参见

* class [FontSettings](../)
* namespace [Aspose.Imaging](../../fontsettings/)
* assembly [Aspose.Imaging](../../../)


