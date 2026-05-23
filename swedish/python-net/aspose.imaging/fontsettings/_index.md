---
title: "FontSettings-klass"
type: docs
weight: 4850
url: /sv/python-net/aspose.imaging/fontsettings/
---

**Summary:** General imaging vector formats renderer font settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.FontSettings

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| default_font_name [statisk] | string | r/w | Hämtar eller anger standardnamnet för teckensnittet. |
| get_system_alternative_font [statisk] | bool | r/w | Hämtar eller anger ett värde som indikerar om [get alternative font]. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_default_fonts_folders()](#get_default_fonts_folders__1) | Hämtar standardmapparna för teckensnitt. |
| [get_fonts_folders()](#get_fonts_folders__2) | Hämtar en kopia av arrayen som innehåller listan över mappar där Aspose.Words söker efter TrueType-teckensnitt. |
| reset() | Återställer teckensnittsmappen och standardteckensnittets namn till systemstandard. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_3) | Detta är en genväg till [FontSettings.set_fonts_folders(fonts_folders, recursive)](/imaging/python-net/aspose.imaging/fontsettings/) för att ange endast en teckensnittskatalog.<br/>            Det utförs inga kontroller på teckensnittsmappen. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_4) | Anger mapparna där TrueType-teckensnitt laddas från och rensar alla laddade teckensnitt.<br/>            Det utförs inga kontroller på teckensnittsmapparna. |
| update_fonts() | Uppdaterar teckensnittscache för PSD-filer som innehåller textlager. Denna metod garanterar att teckensnitt från mappen fontsFolder som används<br/>            med metoden FontSettings.SetFontsFolder(fontsFolder) eller efter återställning av teckensnitt med FontSettings.Reset() tas i beaktande vid bearbetning av PSD-filer. Använd denna metod varje gång när <br/>            FontSettings.SetFontsFolder(fontsFolder) eller FontSettings.Reset() anropas för PSD-bilder. Utan att anropa denna metod finns ingen garanti för att teckensnitt uppdateras. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__1}


```
 get_default_fonts_folders() 
```

Hämtar standardmapparna för teckensnitt.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string[] | Returnerar systemmappen |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__2}


```
 get_fonts_folders() 
```

Hämtar en kopia av arrayen som innehåller listan över mappar där Aspose.Words söker efter TrueType-teckensnitt.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string[] | En kopia av de aktuella teckensnittslägena. |


### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_3}


```
 set_fonts_folder(font_folder) 
```

Detta är en genväg till [FontSettings.set_fonts_folders(fonts_folders, recursive)](/imaging/python-net/aspose.imaging/fontsettings/) för att ange endast en teckensnittskatalog.<br/>            Det utförs inga kontroller på teckensnittsmappen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_folder | string | Teckensnittsmappen. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_4}


```
 set_fonts_folders(fonts_folders, recursive) 
```

Anger mapparna där TrueType-teckensnitt laddas från och rensar alla laddade teckensnitt.<br/>            Det utförs inga kontroller på teckensnittsmapparna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fonts_folders | string[] | Teckensnittsmapparna. |
| rekursiv | bool | om inställd på <c>true</c> [rekursiv]. |

