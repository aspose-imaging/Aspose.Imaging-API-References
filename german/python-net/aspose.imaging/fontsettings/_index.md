---
title: "FontSettings Klasse"
type: docs
weight: 4850
url: /de/python-net/aspose.imaging/fontsettings/
---

**Summary:** General imaging vector formats renderer font settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.FontSettings

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| default_font_name [static] | string | r/w | Liest oder setzt den Standardnamen der Schriftart. |
| get_system_alternative_font [static] | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [get alternative font]. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_default_fonts_folders()](#get_default_fonts_folders__1) | Liest die Standardordner für Schriftarten. |
| [get_fonts_folders()](#get_fonts_folders__2) | Liest eine Kopie des Arrays, das die Liste der Ordner enthält, in denen Aspose.Words nach TrueType-Schriftarten sucht. |
| reset() | Setzt den Schriftartenordner und den Standardnamen der Schriftart auf die Systemvorgabe zurück. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_3) | Dies ist eine Verknüpfung zu [FontSettings.set_fonts_folders(fonts_folders, recursive)](/imaging/python-net/aspose.imaging/fontsettings/) zum Einstellen eines einzigen Schriftartenverzeichnisses.<br/>            Es werden keine Prüfungen des Schriftartenordners durchgeführt. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_4) | Legt die Ordner fest, aus denen TrueType-Schriftarten geladen werden, und löscht alle geladenen Schriftarten.<br/>            Es werden keine Prüfungen der Schriftartenordner durchgeführt. |
| update_fonts() | Aktualisiert den Schriftarten-Cache für PSD-Dateien, die Textebenen enthalten. Diese Methode garantiert, dass Schriftarten aus dem Ordner fontsFolder, die über<br/>            die Methode FontSettings.SetFontsFolder(fontsFolder) geladen werden, oder nach dem Zurücksetzen von Schriftarten mittels FontSettings.Reset() bei der Verarbeitung von PSD-Dateien berücksichtigt werden. Bitte verwenden Sie diese Methode jedes Mal, wenn <br/>            FontSettings.SetFontsFolder(fontsFolder) oder FontSettings.Reset() für PSD‑Bilder aufgerufen wird. Ohne Aufruf dieser Methode gibt es keine Garantie, dass Schriftarten aktualisiert werden. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__1}


```
 get_default_fonts_folders() 
```

Liest die Standardordner für Schriftarten.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string[] | Gibt den Systemordner zurück |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__2}


```
 get_fonts_folders() 
```

Liest eine Kopie des Arrays, das die Liste der Ordner enthält, in denen Aspose.Words nach TrueType-Schriftarten sucht.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string[] | Eine Kopie der aktuellen Schriftartstandorte. |


### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_3}


```
 set_fonts_folder(font_folder) 
```

Dies ist eine Verknüpfung zu [FontSettings.set_fonts_folders(fonts_folders, recursive)](/imaging/python-net/aspose.imaging/fontsettings/) zum Einstellen eines einzigen Schriftartenverzeichnisses.<br/>            Es werden keine Prüfungen des Schriftartenordners durchgeführt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_folder | string | Der Schriftartenordner. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_4}


```
 set_fonts_folders(fonts_folders, recursive) 
```

Legt die Ordner fest, aus denen TrueType-Schriftarten geladen werden, und löscht alle geladenen Schriftarten.<br/>            Es werden keine Prüfungen der Schriftartenordner durchgeführt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| fonts_folders | string[] | Die Schriftartenordner. |
| recursive | bool | wenn auf <c>true</c> [recursive] gesetzt. |

