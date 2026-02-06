---
title: Class FontSettings
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.FontSettings class. General imaging vector formats renderer font settings
type: docs
weight: 9520
url: /net/aspose.imaging/fontsettings/
---
## FontSettings class

General imaging vector formats renderer font settings.

```csharp
public static class FontSettings
```

## Properties

| Name | Description |
| --- | --- |
| static [DefaultFontName](../../aspose.imaging/fontsettings/defaultfontname/) { get; set; } | Gets or sets the default name of the font. |
| static [GetSystemAlternativeFont](../../aspose.imaging/fontsettings/getsystemalternativefont/) { get; set; } | Gets or sets a value indicating whether [get alternative font]. |

## Methods

| Name | Description |
| --- | --- |
| static [GetDefaultFontsFolders](../../aspose.imaging/fontsettings/getdefaultfontsfolders/)() | Gets the default fonts folders. |
| static [GetFontsFolders](../../aspose.imaging/fontsettings/getfontsfolders/)() | Gets a copy of the array that contains the list of folders where Aspose.Words looks for TrueType fonts. |
| static [Reset](../../aspose.imaging/fontsettings/reset/)() | Resets the fonts folder and default font name to the system default. |
| static [SetFontsFolder](../../aspose.imaging/fontsettings/setfontsfolder/)(string) | This is a shortcut to [`SetFontsFolders`](./setfontsfolders/) for setting only one font directory. There are no checks performed on the fonts folder. |
| static [SetFontsFolders](../../aspose.imaging/fontsettings/setfontsfolders/)(string[], bool) | Sets the folders where TrueType fonts are loaded from and clears all loaded fonts. There are no checks performed on the fonts folders. |
| static [UpdateFonts](../../aspose.imaging/fontsettings/updatefonts/)() | Updates fonts cache for PSD files that contain text layers. This method guarantees that fonts from folder fontsFolder using method FontSettings.SetFontsFolder(fontsFolder) or after reset fonts using FontSettings.Reset() will be taken into consideration when processing PSD files. Please use this method each time when FontSettings.SetFontsFolder(fontsFolder) or FontSettings.Reset() called for PSD images. Without calling this Method there is no guarantee that fonts will be updated. |

### See Also

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


