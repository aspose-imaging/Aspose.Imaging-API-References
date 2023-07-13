---
title: FontSettings Class
type: docs
weight: 4790
url: /python-net/aspose.imaging/fontsettings/
---

General imaging vector formats renderer font settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.FontSettings

**Aspose.Imaging Version:** 23.6

The FontSettings type exposes the following members:
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| get_system_alternative_font [static] | bool | r/w | Gets or sets a value indicating whether [get alternative font]. |
| default_font_name [static] | string | r/w | Gets or sets the default name of the font. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_fonts_folders()](#get_fonts_folders__0) | Gets a copy of the array that contains the list of folders where Aspose.Words looks for TrueType fonts. |
| [get_default_fonts_folders()](#get_default_fonts_folders__1) | Gets the default fonts folders. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_2) | This is a shortcut to <see cref="M:Aspose.Imaging.FontSettings.SetFontsFolders(System.String[],System.Boolean)" /> for setting only one font directory.<br/>            There are no checks performed on the fonts folder. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_3) | Sets the folders where TrueType fonts are loaded from and clears all loaded fonts.<br/>            There are no checks performed on the fonts folders. |
| reset() | Resets the fonts folder and default font name to the system default. |
| update_fonts() | Updates fonts cache for PSD files that contain text layers. This method guarantees that fonts from folder fontsFolder using<br/>            method FontSettings.SetFontsFolder(fontsFolder) or after reset fonts using FontSettings.Reset() will be taken into consideration when processing PSD files. Please use this method each time when  <br/>            FontSettings.SetFontsFolder(fontsFolder) or FontSettings.Reset() called for PSD images. Without calling this Method there is no guarantee that fonts will be updated. |

### get_fonts_folders()  [static] {#get_fonts_folders__0}


```
 get_fonts_folders() 
```

Gets a copy of the array that contains the list of folders where Aspose.Words looks for TrueType fonts.

**Returns**

| Type | Description |
| :- | :- |
| string | A copy of the current font locations. |


### get_default_fonts_folders()  [static] {#get_default_fonts_folders__1}


```
 get_default_fonts_folders() 
```

Gets the default fonts folders.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns system folder |


### set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_2}


```
 set_fonts_folder(font_folder) 
```

This is a shortcut to <see cref="M:Aspose.Imaging.FontSettings.SetFontsFolders(System.String[],System.Boolean)" /> for setting only one font directory.<br/>            There are no checks performed on the fonts folder.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_folder | string | The font folder. |

### set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_3}


```
 set_fonts_folders(fonts_folders, recursive) 
```

Sets the folders where TrueType fonts are loaded from and clears all loaded fonts.<br/>            There are no checks performed on the fonts folders.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| fonts_folders | string | The fonts folders. |
| recursive | bool | if set to <c>true</c> [recursive]. |

