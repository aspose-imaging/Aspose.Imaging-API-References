---
title: FontSettings Class
type: docs
weight: 210
url: /python-net/aspose.imaging/fontsettings/
---

General imaging vector formats renderer font settings.

**Namespace:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Class Name:** aspose.imaging.FontSettings

**Assembly:**  Aspose.Imaging Version: 23.5.6

The FontSettings type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|get_system_alternative_font|Gets or sets a value indicating whether [get alternative font].|
|default_font_name|Gets or sets the default name of the font.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|get_fonts_folders()|Gets a copy of the array that contains the list of folders where Aspose.Words looks for TrueType fonts.|
|get_default_fonts_folders()|Gets the default fonts folders.|
|set_fonts_folder(font_folder)|This is a shortcut to|
|set_fonts_folders(fonts_folders, recursive)|Sets the folders where TrueType fonts are loaded from and clears all loaded fonts.<br/>            There are no checks performed on the fonts folders.|
|reset()|Resets the fonts folder and default font name to the system default.|
|update_fonts()|Updates fonts cache for PSD files that contain text layers. This method guarantees that fonts from folder fontsFolder using<br/>            method FontSettings.SetFontsFolder(fontsFolder) or after reset fonts using FontSettings.Reset() will be taken into consideration when processing PSD files. Please use this method each time when  <br/>            FontSettings.SetFontsFolder(fontsFolder) or FontSettings.Reset() called for PSD images. Without calling this Method there is no guarantee that fonts will be updated.|
