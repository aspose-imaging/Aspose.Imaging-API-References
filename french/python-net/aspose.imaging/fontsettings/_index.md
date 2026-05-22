---
title: "FontSettings classe"
type: docs
weight: 4850
url: /fr/python-net/aspose.imaging/fontsettings/
---

**Summary:** General imaging vector formats renderer font settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.FontSettings

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| default_font_name [statique] | string | r/w | Obtient ou définit le nom par défaut de la police. |
| get_system_alternative_font [statique] | bool | r/w | Obtient ou définit une valeur indiquant si [obtenir police alternative]. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_default_fonts_folders()](#get_default_fonts_folders__1) | Obtient les dossiers de polices par défaut. |
| [get_fonts_folders()](#get_fonts_folders__2) | Obtient une copie du tableau qui contient la liste des dossiers où Aspose.Words recherche les polices TrueType. |
| reset() | Réinitialise le dossier des polices et le nom de police par défaut au réglage système. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_3) | Ceci est un raccourci vers [FontSettings.set_fonts_folders(fonts_folders, recursive)](/imaging/python-net/aspose.imaging/fontsettings/) pour définir un seul répertoire de polices.<br/>            Aucun contrôle n'est effectué sur le dossier des polices. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_4) | Définit les dossiers d'où les polices TrueType sont chargées et supprime toutes les polices chargées.<br/>            Aucun contrôle n'est effectué sur les dossiers de polices. |
| update_fonts() | Mise à jour du cache des polices pour les fichiers PSD contenant des calques de texte. Cette méthode garantit que les polices du dossier fontsFolder utilisant<br/>            la méthode FontSettings.SetFontsFolder(fontsFolder) ou, après réinitialisation des polices avec FontSettings.Reset(), seront prises en compte lors du traitement des fichiers PSD. Veuillez utiliser cette méthode chaque fois que <br/>            FontSettings.SetFontsFolder(fontsFolder) ou FontSettings.Reset() est appelé pour des images PSD. Sans appeler cette méthode, aucune garantie n'est donnée que les polices seront mises à jour. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__1}


```
 get_default_fonts_folders() 
```

Obtient les dossiers de polices par défaut.

**Returns**

| Type | Description |
| :- | :- |
| string[] | Renvoie le dossier système |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__2}


```
 get_fonts_folders() 
```

Obtient une copie du tableau qui contient la liste des dossiers où Aspose.Words recherche les polices TrueType.

**Returns**

| Type | Description |
| :- | :- |
| string[] | Une copie des emplacements actuels des polices. |


### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_3}


```
 set_fonts_folder(font_folder) 
```

Ceci est un raccourci vers [FontSettings.set_fonts_folders(fonts_folders, recursive)](/imaging/python-net/aspose.imaging/fontsettings/) pour définir un seul répertoire de polices.<br/>            Aucun contrôle n'est effectué sur le dossier des polices.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| font_folder | string | Le dossier des polices. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_4}


```
 set_fonts_folders(fonts_folders, recursive) 
```

Définit les dossiers d'où les polices TrueType sont chargées et supprime toutes les polices chargées.<br/>            Aucun contrôle n'est effectué sur les dossiers de polices.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| fonts_folders | string[] | Les dossiers des polices. |
| recursive | bool | si défini sur <c>true</c> [récursif]. |

