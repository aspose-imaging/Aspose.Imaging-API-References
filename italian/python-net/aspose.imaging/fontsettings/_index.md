---
title: "Classe FontSettings"
type: docs
weight: 4850
url: /it/python-net/aspose.imaging/fontsettings/
---

**Summary:** General imaging vector formats renderer font settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.FontSettings

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| default_font_name [static] | string | r/w | Ottiene o imposta il nome predefinito del carattere. |
| get_system_alternative_font [static] | bool | r/w | Ottiene o imposta un valore che indica se [get alternative font]. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_default_fonts_folders()](#get_default_fonts_folders__1) | Ottiene le cartelle predefinite dei caratteri. |
| [get_fonts_folders()](#get_fonts_folders__2) | Ottiene una copia dell'array che contiene l'elenco delle cartelle in cui Aspose.Words cerca i caratteri TrueType. |
| reset() | Ripristina la cartella dei caratteri e il nome predefinito del carattere ai valori predefiniti di sistema. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_3) | Questo è un collegamento rapido a [FontSettings.set_fonts_folders(fonts_folders, recursive)](/imaging/python-net/aspose.imaging/fontsettings/) per impostare una sola directory dei caratteri.<br/>            Non vengono eseguiti controlli sulla cartella dei caratteri. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_4) | Imposta le cartelle da cui vengono caricati i caratteri TrueType e cancella tutti i caratteri caricati.<br/>            Non vengono eseguiti controlli sulle cartelle dei caratteri. |
| update_fonts() | Aggiorna la cache dei caratteri per i file PSD che contengono livelli di testo. Questo metodo garantisce che i caratteri dalla cartella fontsFolder usando<br/>            il metodo FontSettings.SetFontsFolder(fontsFolder) o, dopo il reset dei caratteri usando FontSettings.Reset(), vengano considerati durante l'elaborazione dei file PSD. Si prega di utilizzare questo metodo ogni volta che <br/>            FontSettings.SetFontsFolder(fontsFolder) o FontSettings.Reset() vengono chiamati per immagini PSD. Senza chiamare questo Metodo non vi è alcuna garanzia che i caratteri vengano aggiornati. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__1}


```
 get_default_fonts_folders() 
```

Ottiene le cartelle predefinite dei caratteri.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string[] | Restituisce la cartella di sistema |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__2}


```
 get_fonts_folders() 
```

Ottiene una copia dell'array che contiene l'elenco delle cartelle in cui Aspose.Words cerca i caratteri TrueType.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string[] | Una copia delle attuali posizioni dei caratteri. |


### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_3}


```
 set_fonts_folder(font_folder) 
```

Questo è un collegamento rapido a [FontSettings.set_fonts_folders(fonts_folders, recursive)](/imaging/python-net/aspose.imaging/fontsettings/) per impostare una sola directory dei caratteri.<br/>            Non vengono eseguiti controlli sulla cartella dei caratteri.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_folder | string | La cartella dei caratteri. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_4}


```
 set_fonts_folders(fonts_folders, recursive) 
```

Imposta le cartelle da cui vengono caricati i caratteri TrueType e cancella tutti i caratteri caricati.<br/>            Non vengono eseguiti controlli sulle cartelle dei caratteri.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fonts_folders | string[] | Le cartelle dei caratteri. |
| recursive | bool | se impostato su <c>true</c> [recursive]. |

