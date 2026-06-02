---
title: "FontSettings"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "通用图像矢量格式渲染器的字体设置。"
type: docs
weight: 49
url: /zh/java/com.aspose.imaging/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

通用图像矢量格式渲染器的字体设置。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | 获取一个值，指示是否 [get alternative font]。 |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | 设置一个值，指示是否 [get alternative font]。 |
| [getDefaultFontName()](#getDefaultFontName--) | 获取默认字体名称。 |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | 设置默认字体名称。 |
| [getFontsFolders()](#getFontsFolders--) | 获取包含 Aspose.Imaging 查找 TrueType 字体的文件夹列表的数组副本。 |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | 获取默认字体文件夹。 |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | 覆盖 `folder` 的字体文件夹列表 |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | 覆盖 `folders` 的字体文件夹列表 |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | 设置加载 TrueType 字体的文件夹并清除所有已加载的字体。 |
| [reset()](#reset--) | 将字体文件夹和默认字体名称重置为系统默认。 |
| [updateFonts()](#updateFonts--) | 更新包含文本图层的 PSD 文件的字体缓存。 |
| [addFontsFolder(String fontFolder)](#addFontsFolder-java.lang.String-) | 将 `fontFolder` 添加到字体目录列表中，并将其标记为字体搜索的第一个文件夹 |
| [removeFontsFolder(String folder)](#removeFontsFolder-java.lang.String-) | 从文件夹列表中移除 `folder` |
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


获取一个值，指示是否 [get alternative font]。

值：如果 [get alternative font] 为 `true`；否则为 `false`。

**Returns:**
boolean - 表示是否 [get alternative font] 的值。
### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


设置一个值，指示是否 [get alternative font]。

值：如果 [get alternative font] 为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 指示是否 [get alternative font] 的值。 |

### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


获取默认字体名称。

**Returns:**
java.lang.String - 默认字体的名称
### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


设置默认字体名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | 字体的默认名称。 |

### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


获取包含 Aspose.Imaging 查找 TrueType 字体的文件夹列表的数组副本。

返回的值是 Aspose.Imaging 使用的数据的副本。如果更改返回数组中的条目，将不会影响文档渲染。要指定新的字体位置，请使用 `setFontsFolders` 方法。

**Returns:**
java.lang.String[] - 当前字体位置的副本。
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


获取默认字体文件夹。

**Returns:**
java.lang.String[] - 返回系统文件夹
### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


覆盖 `folder` 的字体文件夹列表

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| folder | java.lang.String | 包含 TrueType 字体的文件夹。 |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


覆盖 `folders` 的字体文件夹列表

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| folders | java.lang.String[] | 文件夹数组 |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


设置加载 TrueType 字体的文件夹并清除所有已加载的字体。不会对字体文件夹执行任何检查。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| folders | java.lang.String[] | 字体文件夹。 |
| recursive | boolean | 如果设置为 `true` [recursive]。 |

### reset() {#reset--}
```
public static void reset()
```


将字体文件夹和默认字体名称重置为系统默认。

### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


更新包含文本图层的 PSD 文件的字体缓存。此方法确保在处理 PSD 文件时，会考虑使用 FontSettings.setFontsFolder(fontsFolder) 方法指定的 fontsFolder 文件夹中的字体，或在使用 FontSettings.reset() 重置字体后得到的字体。请在每次为 PSD 图像调用 FontSettings.setFontsFolder(fontsFolder) 或 FontSettings.reset() 时使用此方法。如果不调用此方法，则无法保证字体会被更新。

### addFontsFolder(String fontFolder) {#addFontsFolder-java.lang.String-}
```
public static void addFontsFolder(String fontFolder)
```


将 `fontFolder` 添加到字体目录列表中，并将其标记为字体搜索的第一个文件夹

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontFolder | java.lang.String | 该文件夹包含 TrueType 字体或单个字体文件路径。 |

### removeFontsFolder(String folder) {#removeFontsFolder-java.lang.String-}
```
public static void removeFontsFolder(String folder)
```


从文件夹列表中移除 `folder`

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| folder | java.lang.String | 要移除的文件夹 |

