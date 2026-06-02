---
title: "FontSettings"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Paramètres de police du rendu des formats vectoriels d'imagerie généraux."
type: docs
weight: 49
url: /fr/java/com.aspose.imaging/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

Paramètres de police du rendu des formats vectoriels d'imagerie généraux.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | Obtient une valeur indiquant si [get alternative font]. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | Définit une valeur indiquant si [get alternative font]. |
| [getDefaultFontName()](#getDefaultFontName--) | Obtient le nom de police par défaut. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Définit le nom de police par défaut. |
| [getFontsFolders()](#getFontsFolders--) | Obtient une copie du tableau contenant la liste des dossiers où Aspose.Imaging recherche les polices TrueType. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Obtient les dossiers de polices par défaut. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | Remplace la liste des dossiers de polices pour `folder` |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | Remplace la liste des dossiers de polices pour `folders` |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | Définit les dossiers à partir desquels les polices TrueType sont chargées et supprime toutes les polices chargées. |
| [reset()](#reset--) | Réinitialise le dossier des polices et le nom de police par défaut au paramètre système par défaut. |
| [updateFonts()](#updateFonts--) | Met à jour le cache des polices pour les fichiers PSD contenant des calques de texte. |
| [addFontsFolder(String fontFolder)](#addFontsFolder-java.lang.String-) | Ajoute le `fontFolder` à la liste des répertoires de polices et le marque comme premier dossier pour la recherche de polices |
| [removeFontsFolder(String folder)](#removeFontsFolder-java.lang.String-) | Supprime le `folder` de la liste des dossiers |
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


Obtient une valeur indiquant si [get alternative font].

Valeur : `true` si [get alternative font] ; sinon, `false`.

**Returns:**
boolean - une valeur indiquant si [get alternative font].
### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


Définit une valeur indiquant si [get alternative font].

Valeur : `true` si [get alternative font] ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si [get alternative font]. |

### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


Obtient le nom de police par défaut.

**Returns:**
java.lang.String - nom de la police par défaut
### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Définit le nom de police par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Le nom par défaut de la police. |

### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Obtient une copie du tableau contenant la liste des dossiers où Aspose.Imaging recherche les polices TrueType.

La valeur retournée est une copie des données utilisées par Aspose.Imaging. Si vous modifiez les éléments du tableau retourné, cela n'affectera pas le rendu du document. Pour spécifier de nouveaux emplacements de polices, utilisez la méthode `setFontsFolders`.

**Returns:**
java.lang.String[] - Une copie des emplacements de polices actuels.
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Obtient les dossiers de polices par défaut.

**Returns:**
java.lang.String[] - Retourne le dossier système
### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


Remplace la liste des dossiers de polices pour `folder`

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | Dossier contenant des polices TrueType. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


Remplace la liste des dossiers de polices pour `folders`

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| folders | java.lang.String[] | Tableau de dossiers |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


Définit les dossiers d'où les polices TrueType sont chargées et supprime toutes les polices chargées. Aucun contrôle n'est effectué sur les dossiers de polices.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| folders | java.lang.String[] | Les dossiers de polices. |
| recursive | boolean | si défini sur `true` [recursive]. |

### reset() {#reset--}
```
public static void reset()
```


Réinitialise le dossier des polices et le nom de police par défaut au paramètre système par défaut.

### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


Mise à jour du cache des polices pour les fichiers PSD contenant des calques de texte. Cette méthode garantit que les polices du dossier fontsFolder utilisant la méthode FontSettings.setFontsFolder(fontsFolder) ou après réinitialisation des polices avec FontSettings.reset() seront prises en compte lors du traitement des fichiers PSD. Veuillez utiliser cette méthode chaque fois que FontSettings.setFontsFolder(fontsFolder) ou FontSettings.reset() est appelé pour des images PSD. Sans appeler cette méthode, aucune garantie n'est donnée que les polices seront mises à jour.

### addFontsFolder(String fontFolder) {#addFontsFolder-java.lang.String-}
```
public static void addFontsFolder(String fontFolder)
```


Ajoute le `fontFolder` à la liste des répertoires de polices et le marque comme premier dossier pour la recherche de polices

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontFolder | java.lang.String | Le dossier contient les polices TrueType ou le chemin d'un fichier de police unique. |

### removeFontsFolder(String folder) {#removeFontsFolder-java.lang.String-}
```
public static void removeFontsFolder(String folder)
```


Supprime le `folder` de la liste des dossiers

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | Le dossier à supprimer |

