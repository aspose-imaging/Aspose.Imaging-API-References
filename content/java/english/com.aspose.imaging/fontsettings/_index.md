---
title: FontSettings
second_title: Aspose.Imaging for Java API Reference
description: General imaging vector formats renderer font settings.
type: docs
weight: 49
url: /com.aspose.imaging/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

General imaging vector formats renderer font settings.
## Methods

| Method | Description |
| --- | --- |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | Gets a value indicating whether [get alternative font]. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | Sets a value indicating whether [get alternative font]. |
| [getDefaultFontName()](#getDefaultFontName--) | Gets the default font name. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Sets the default font name. |
| [getFontsFolders()](#getFontsFolders--) | Gets a copy of the array that contains the list of folders where Aspose.Imaging looks for TrueType fonts. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Gets the default fonts folders. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | Override font folder list for `folder` |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | Override font folder list for `folders` |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | Sets the folders where TrueType fonts are loaded from and clears all loaded fonts. |
| [reset()](#reset--) | Resets the fonts folder and default font name to the system default. |
| [updateFonts()](#updateFonts--) | Updates fonts cache for PSD files that contain text layers. |
| [addFontsFolder(String fontFolder)](#addFontsFolder-java.lang.String-) | Adds the `fontFolder` into font directory list and marks it as first folder for font searching |
| [removeFontsFolder(String folder)](#removeFontsFolder-java.lang.String-) | Removes `folder` from folder list |
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


Gets a value indicating whether [get alternative font].

Value: `true` if [get alternative font]; otherwise, `false`.

**Returns:**
boolean - a value indicating whether [get alternative font].
### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


Sets a value indicating whether [get alternative font].

Value: `true` if [get alternative font]; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | a value indicating whether [get alternative font]. |

### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


Gets the default font name.

**Returns:**
java.lang.String - default font's name
### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Sets the default font name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | The default name of the font. |

### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Gets a copy of the array that contains the list of folders where Aspose.Imaging looks for TrueType fonts.

The returned value is a copy of the data that Aspose.Imaging uses. If you change the entries in the returned array, it will have no effect on document rendering. To specify new font locations use the `setFontsFolders` method.

**Returns:**
java.lang.String[] - A copy of the current font locations.
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Gets the default fonts folders.

**Returns:**
java.lang.String[] - Returns system folder
### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


Override font folder list for `folder`

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | Folder with TrueType fonts. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


Override font folder list for `folders`

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folders | java.lang.String[] | Array of folder |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


Sets the folders where TrueType fonts are loaded from and clears all loaded fonts. There are no checks performed on the fonts folders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folders | java.lang.String[] | The fonts folders. |
| recursive | boolean | if set to `true` [recursive]. |

### reset() {#reset--}
```
public static void reset()
```


Resets the fonts folder and default font name to the system default.

### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


Updates fonts cache for PSD files that contain text layers. This method guarantees that fonts from folder fontsFolder using method FontSettings.setFontsFolder(fontsFolder) or after reset fonts using FontSettings.reset() will be taken into consideration when processing PSD files. Please use this method each time when FontSettings.setFontsFolder(fontsFolder) or FontSettings.reset() called for PSD images. Without calling this Method there is no guarantee that fonts will be updated.

### addFontsFolder(String fontFolder) {#addFontsFolder-java.lang.String-}
```
public static void addFontsFolder(String fontFolder)
```


Adds the `fontFolder` into font directory list and marks it as first folder for font searching

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFolder | java.lang.String | The folder contains the TrueType fonts or single font file path. |

### removeFontsFolder(String folder) {#removeFontsFolder-java.lang.String-}
```
public static void removeFontsFolder(String folder)
```


Removes `folder` from folder list

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | The folder to remove |

