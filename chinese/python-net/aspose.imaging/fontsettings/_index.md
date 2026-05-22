---
title: "FontSettings 类"
type: docs
weight: 4850
url: /zh/python-net/aspose.imaging/fontsettings/
---

**Summary:** General imaging vector formats renderer font settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.FontSettings

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| default_font_name [static] | string | r/w | 获取或设置字体的默认名称。 |
| get_system_alternative_font [static] | bool | r/w | 获取或设置一个值，以指示是否 [get alternative font]。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_default_fonts_folders()](#get_default_fonts_folders__1) | 获取默认的字体文件夹。 |
| [get_fonts_folders()](#get_fonts_folders__2) | 获取一个数组的副本，该数组包含 Aspose.Words 查找 TrueType 字体的文件夹列表。 |
| reset() | 将字体文件夹和默认字体名称重置为系统默认值。 |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_3) | 这是一个快捷方式，指向 [FontSettings.set_fonts_folders(fonts_folders, recursive)](/imaging/python-net/aspose.imaging/fontsettings/)，用于仅设置一个字体目录。<br/>            对字体文件夹不执行任何检查。 |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_4) | 设置加载 TrueType 字体的文件夹并清除所有已加载的字体。<br/>            对字体文件夹不执行任何检查。 |
| update_fonts() | 更新包含文本图层的 PSD 文件的字体缓存。此方法确保在处理 PSD 文件时，会考虑来自文件夹 fontsFolder 的字体，使用<br/>            方法 FontSettings.SetFontsFolder(fontsFolder) 或在使用 FontSettings.Reset() 重置字体后。请在每次为 PSD 图像调用 FontSettings.SetFontsFolder(fontsFolder) 或 FontSettings.Reset() 时使用此方法。如果不调用此方法，则无法保证字体会被更新。 |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__1}


```
 get_default_fonts_folders() 
```

获取默认的字体文件夹。

**Returns**

| Type | Description |
| :- | :- |
| string[] | 返回系统文件夹 |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__2}


```
 get_fonts_folders() 
```

获取一个数组的副本，该数组包含 Aspose.Words 查找 TrueType 字体的文件夹列表。

**Returns**

| Type | Description |
| :- | :- |
| string[] | 当前字体位置的副本。 |


### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_3}


```
 set_fonts_folder(font_folder) 
```

这是一个快捷方式，指向 [FontSettings.set_fonts_folders(fonts_folders, recursive)](/imaging/python-net/aspose.imaging/fontsettings/)，用于仅设置一个字体目录。<br/>            对字体文件夹不执行任何检查。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| font_folder | string | 字体文件夹。 |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_4}


```
 set_fonts_folders(fonts_folders, recursive) 
```

设置加载 TrueType 字体的文件夹并清除所有已加载的字体。<br/>            对字体文件夹不执行任何检查。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| fonts_folders | string[] | 字体文件夹。 |
| recursive | bool | 如果设置为 <c>true</c> [recursive]。 |

