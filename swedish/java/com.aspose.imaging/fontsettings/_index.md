---
title: "FontSettings"
second_title: "Aspose.Imaging för Java API-referens"
description: "Allmänna teckensnittsinställningar för vektorformatrenderare i bildbehandling."
type: docs
weight: 49
url: /sv/java/com.aspose.imaging/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

Allmänna teckensnittsinställningar för vektorformatrenderare i bildbehandling.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | Hämtar ett värde som indikerar om [get alternative font]. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | Ställer in ett värde som indikerar om [get alternative font]. |
| [getDefaultFontName()](#getDefaultFontName--) | Hämtar standardtypsnittets namn. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Ställer in standardtypsnittets namn. |
| [getFontsFolders()](#getFontsFolders--) | Hämtar en kopia av arrayen som innehåller listan över mappar där Aspose.Imaging söker efter TrueType-typsnitt. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Hämtar standardmapparna för typsnitt. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | Åsidosätt typsnittsmappningslistan för `folder` |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | Åsidosätt typsnittsmappningslistan för `folders` |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | Ställer in mapparna där TrueType-typsnitt laddas från och rensar alla inlästa typsnitt. |
| [reset()](#reset--) | Återställer teckensnittsmappen och standardteckensnittets namn till systemets standard. |
| [updateFonts()](#updateFonts--) | Uppdaterar teckensnittscache för PSD-filer som innehåller textlager. |
| [addFontsFolder(String fontFolder)](#addFontsFolder-java.lang.String-) | Lägger till `fontFolder` i teckensnittskataloglistan och markerar den som den första mappen för teckensnittssökning |
| [removeFontsFolder(String folder)](#removeFontsFolder-java.lang.String-) | Tar bort `folder` från mapplistan |
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


Hämtar ett värde som indikerar om [get alternative font].

Värde: `true` om [get alternative font]; annars, `false`.

**Returns:**
boolean - ett värde som indikerar om [get alternative font].
### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


Ställer in ett värde som indikerar om [get alternative font].

Värde: `true` om [get alternative font]; annars, `false`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | ett värde som indikerar om [get alternative font]. |

### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


Hämtar standardtypsnittets namn.

**Returns:**
java.lang.String - standardteckensnittets namn
### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Ställer in standardtypsnittets namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | Standardnamnet på teckensnittet. |

### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Hämtar en kopia av arrayen som innehåller listan över mappar där Aspose.Imaging söker efter TrueType-typsnitt.

Det returnerade värdet är en kopia av de data som Aspose.Imaging använder. Om du ändrar posterna i den returnerade arrayen kommer det inte att påverka dokumentrenderingen. För att ange nya teckensnittslägen använder du metoden `setFontsFolders`.

**Returns:**
java.lang.String[] - En kopia av de aktuella teckensnittslägena.
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Hämtar standardmapparna för typsnitt.

**Returns:**
java.lang.String[] - Returnerar systemmappen
### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


Åsidosätt typsnittsmappningslistan för `folder`

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | java.lang.String | Mapp med TrueType-teckensnitt. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


Åsidosätt typsnittsmappningslistan för `folders`

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folders | java.lang.String[] | Array av mappar |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


Ställer in mapparna där TrueType-teckensnitt laddas från och rensar alla laddade teckensnitt. Det utförs inga kontroller på teckensnittsmapparna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folders | java.lang.String[] | Teckensnittsmapparna. |
| recursive | boolean | om satt till `true` [recursive]. |

### reset() {#reset--}
```
public static void reset()
```


Återställer teckensnittsmappen och standardteckensnittets namn till systemets standard.

### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


Uppdaterar teckensnittscache för PSD-filer som innehåller textlager. Denna metod garanterar att teckensnitt från mappen fontsFolder som används med metoden FontSettings.setFontsFolder(fontsFolder) eller efter återställning av teckensnitt med FontSettings.reset() tas i beaktande vid bearbetning av PSD-filer. Använd denna metod varje gång FontSettings.setFontsFolder(fontsFolder) eller FontSettings.reset() anropas för PSD-bilder. Utan att anropa denna metod finns det ingen garanti för att teckensnitten uppdateras.

### addFontsFolder(String fontFolder) {#addFontsFolder-java.lang.String-}
```
public static void addFontsFolder(String fontFolder)
```


Lägger till `fontFolder` i teckensnittskataloglistan och markerar den som den första mappen för teckensnittssökning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFolder | java.lang.String | Mappen innehåller TrueType-teckensnitt eller en enskild teckensnittsfilväg. |

### removeFontsFolder(String folder) {#removeFontsFolder-java.lang.String-}
```
public static void removeFontsFolder(String folder)
```


Tar bort `folder` från mapplistan

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | java.lang.String | Mappen att ta bort |

