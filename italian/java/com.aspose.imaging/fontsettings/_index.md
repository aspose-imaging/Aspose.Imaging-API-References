---
title: "FontSettings"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Impostazioni dei caratteri del renderer per i formati vettoriali di imaging generali."
type: docs
weight: 49
url: /it/java/com.aspose.imaging/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

Impostazioni dei caratteri del renderer per i formati vettoriali di imaging generali.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | Ottiene un valore che indica se [get alternative font]. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | Imposta un valore che indica se [get alternative font]. |
| [getDefaultFontName()](#getDefaultFontName--) | Ottiene il nome del font predefinito. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Imposta il nome del font predefinito. |
| [getFontsFolders()](#getFontsFolders--) | Ottiene una copia dell'array che contiene l'elenco delle cartelle in cui Aspose.Imaging cerca i font TrueType. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Ottiene le cartelle dei font predefiniti. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | Sovrascrivi l'elenco delle cartelle dei font per `folder` |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | Sovrascrivi l'elenco delle cartelle dei font per `folders` |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | Imposta le cartelle da cui vengono caricati i font TrueType e cancella tutti i font caricati. |
| [reset()](#reset--) | Ripristina la cartella dei font e il nome del font predefinito al valore predefinito di sistema. |
| [updateFonts()](#updateFonts--) | Aggiorna la cache dei font per i file PSD che contengono livelli di testo. |
| [addFontsFolder(String fontFolder)](#addFontsFolder-java.lang.String-) | Aggiunge il `fontFolder` all'elenco delle directory dei font e lo segna come prima cartella per la ricerca dei font |
| [removeFontsFolder(String folder)](#removeFontsFolder-java.lang.String-) | Rimuove `folder` dall'elenco delle cartelle |
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


Ottiene un valore che indica se [get alternative font].

Valore: `true` se [get alternative font]; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se [get alternative font].
### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


Imposta un valore che indica se [get alternative font].

Valore: `true` se [get alternative font]; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | un valore che indica se [get alternative font]. |

### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


Ottiene il nome del font predefinito.

**Returns:**
java.lang.String - nome del font predefinito
### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Imposta il nome del font predefinito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | java.lang.String | Il nome predefinito del font. |

### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Ottiene una copia dell'array che contiene l'elenco delle cartelle in cui Aspose.Imaging cerca i font TrueType.

Il valore restituito è una copia dei dati utilizzati da Aspose.Imaging. Se modifichi le voci nell'array restituito, non avranno alcun effetto sul rendering del documento. Per specificare nuove posizioni dei font usa il metodo `setFontsFolders`.

**Returns:**
java.lang.String[] - Una copia delle attuali posizioni dei font.
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Ottiene le cartelle dei font predefiniti.

**Returns:**
java.lang.String[] - Restituisce la cartella di sistema
### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


Sovrascrivi l'elenco delle cartelle dei font per `folder`

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | java.lang.String | Cartella con font TrueType. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


Sovrascrivi l'elenco delle cartelle dei font per `folders`

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folders | java.lang.String[] | Array di cartelle |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


Imposta le cartelle da cui vengono caricati i font TrueType e cancella tutti i font caricati. Non vengono eseguiti controlli sulle cartelle dei font.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folders | java.lang.String[] | Le cartelle dei font. |
| recursive | boolean | se impostato su `true` [recursive]. |

### reset() {#reset--}
```
public static void reset()
```


Ripristina la cartella dei font e il nome del font predefinito al valore predefinito di sistema.

### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


Aggiorna la cache dei font per i file PSD che contengono livelli di testo. Questo metodo garantisce che i font dalla cartella fontsFolder usando il metodo FontSettings.setFontsFolder(fontsFolder) o, dopo il reset dei font usando FontSettings.reset(), saranno considerati durante l'elaborazione dei file PSD. Si prega di utilizzare questo metodo ogni volta che FontSettings.setFontsFolder(fontsFolder) o FontSettings.reset() vengono chiamati per immagini PSD. Se questo metodo non viene chiamato, non vi è alcuna garanzia che i font vengano aggiornati.

### addFontsFolder(String fontFolder) {#addFontsFolder-java.lang.String-}
```
public static void addFontsFolder(String fontFolder)
```


Aggiunge il `fontFolder` all'elenco delle directory dei font e lo segna come prima cartella per la ricerca dei font

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontFolder | java.lang.String | La cartella contiene i font TrueType o il percorso di un singolo file font. |

### removeFontsFolder(String folder) {#removeFontsFolder-java.lang.String-}
```
public static void removeFontsFolder(String folder)
```


Rimuove `folder` dall'elenco delle cartelle

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folder | java.lang.String | La cartella da rimuovere |

