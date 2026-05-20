---
title: "FontSettings"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Allgemeine Schriftarteinstellungen für den Renderer von Vektorformaten der Bildverarbeitung."
type: docs
weight: 49
url: /de/java/com.aspose.imaging/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

Allgemeine Schriftarteinstellungen für den Renderer von Vektorformaten der Bildverarbeitung.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | Ermittelt einen Wert, der angibt, ob [get alternative font]. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | Legt einen Wert fest, der angibt, ob [get alternative font]. |
| [getDefaultFontName()](#getDefaultFontName--) | Ermittelt den Standard-Schriftartnamen. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Legt den Standard-Schriftartnamen fest. |
| [getFontsFolders()](#getFontsFolders--) | Ermittelt eine Kopie des Arrays, das die Liste der Ordner enthält, in denen Aspose.Imaging nach TrueType-Schriften sucht. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Ermittelt die Standard-Schriftordner. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | Überschreibe die Schriftordnerliste für `folder` |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | Überschreibe die Schriftordnerliste für `folders` |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | Legt die Ordner fest, aus denen TrueType-Schriften geladen werden, und löscht alle geladenen Schriften. |
| [reset()](#reset--) | Setzt den Schriftartenordner und den Standard‑Schriftartnamen auf die Systemeinstellung zurück. |
| [updateFonts()](#updateFonts--) | Aktualisiert den Schriftarten‑Cache für PSD‑Dateien, die Textebenen enthalten. |
| [addFontsFolder(String fontFolder)](#addFontsFolder-java.lang.String-) | Fügt das `fontFolder` zur Schriftverzeichnisliste hinzu und markiert es als ersten Ordner für die Schriftartensuche. |
| [removeFontsFolder(String folder)](#removeFontsFolder-java.lang.String-) | Entfernt `folder` aus der Ordnerliste. |
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


Ermittelt einen Wert, der angibt, ob [get alternative font].

Wert: `true`, wenn [get alternative font]; andernfalls `false`.

**Returns:**
boolean – ein Wert, der angibt, ob [get alternative font].
### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


Legt einen Wert fest, der angibt, ob [get alternative font].

Wert: `true`, wenn [get alternative font]; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob [get alternative font]. |

### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


Ermittelt den Standard-Schriftartnamen.

**Returns:**
java.lang.String – Name der Standardschriftart
### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Legt den Standard-Schriftartnamen fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | java.lang.String | Der Standardname der Schriftart. |

### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Ermittelt eine Kopie des Arrays, das die Liste der Ordner enthält, in denen Aspose.Imaging nach TrueType-Schriften sucht.

Der zurückgegebene Wert ist eine Kopie der Daten, die Aspose.Imaging verwendet. Wenn Sie die Einträge im zurückgegebenen Array ändern, hat dies keine Auswirkung auf die Dokumentdarstellung. Um neue Schriftartpfade anzugeben, verwenden Sie die Methode `setFontsFolders`.

**Returns:**
java.lang.String[] – Eine Kopie der aktuellen Schriftartpfade.
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Ermittelt die Standard-Schriftordner.

**Returns:**
java.lang.String[] – Gibt den Systemordner zurück.
### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


Überschreibe die Schriftordnerliste für `folder`

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | java.lang.String | Ordner mit TrueType-Schriftarten. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


Überschreibe die Schriftordnerliste für `folders`

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ordner | java.lang.String[] | Array von Ordnern |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


Legt die Ordner fest, aus denen TrueType-Schriftarten geladen werden, und löscht alle geladenen Schriftarten. Es werden keine Prüfungen der Schriftartenordner durchgeführt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ordner | java.lang.String[] | Die Schriftartenordner. |
| rekursiv | boolean | wenn auf `true` gesetzt [recursive]. |

### reset() {#reset--}
```
public static void reset()
```


Setzt den Schriftartenordner und den Standard‑Schriftartnamen auf die Systemeinstellung zurück.

### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


Aktualisiert den Schriftarten‑Cache für PSD‑Dateien, die Textebenen enthalten. Diese Methode stellt sicher, dass Schriftarten aus dem Ordner fontsFolder, die mit der Methode FontSettings.setFontsFolder(fontsFolder) festgelegt wurden, oder nach einem Zurücksetzen der Schriftarten mit FontSettings.reset() berücksichtigt werden, wenn PSD‑Dateien verarbeitet werden. Bitte verwenden Sie diese Methode jedes Mal, wenn FontSettings.setFontsFolder(fontsFolder) oder FontSettings.reset() für PSD‑Bilder aufgerufen wird. Ohne Aufruf dieser Methode gibt es keine Garantie, dass die Schriftarten aktualisiert werden.

### addFontsFolder(String fontFolder) {#addFontsFolder-java.lang.String-}
```
public static void addFontsFolder(String fontFolder)
```


Fügt das `fontFolder` zur Schriftverzeichnisliste hinzu und markiert es als ersten Ordner für die Schriftartensuche.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontFolder | java.lang.String | Der Ordner enthält die TrueType-Schriftarten oder den Pfad zu einer einzelnen Schriftartdatei. |

### removeFontsFolder(String folder) {#removeFontsFolder-java.lang.String-}
```
public static void removeFontsFolder(String folder)
```


Entfernt `folder` aus der Ordnerliste.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| folder | java.lang.String | Der zu entfernende Ordner |

