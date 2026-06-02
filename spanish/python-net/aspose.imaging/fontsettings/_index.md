---
title: "Clase FontSettings"
type: docs
weight: 4850
url: /es/python-net/aspose.imaging/fontsettings/
---

**Summary:** General imaging vector formats renderer font settings.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.FontSettings

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| default_font_name [static] | string | r/w | Obtiene o establece el nombre predeterminado de la fuente. |
| get_system_alternative_font [static] | bool | r/w | Obtiene o establece un valor que indica si [get alternative font]. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_default_fonts_folders()](#get_default_fonts_folders__1) | Obtiene las carpetas predeterminadas de fuentes. |
| [get_fonts_folders()](#get_fonts_folders__2) | Obtiene una copia de la matriz que contiene la lista de carpetas donde Aspose.Words busca fuentes TrueType. |
| reset() | Restablece la carpeta de fuentes y el nombre predeterminado de la fuente al valor predeterminado del sistema. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_3) | Este es un acceso directo a [FontSettings.set_fonts_folders(fonts_folders, recursive)](/imaging/python-net/aspose.imaging/fontsettings/) para establecer solo un directorio de fuentes.<br/>            No se realizan verificaciones en la carpeta de fuentes. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_4) | Establece las carpetas desde donde se cargan las fuentes TrueType y elimina todas las fuentes cargadas.<br/>            No se realizan verificaciones en las carpetas de fuentes. |
| update_fonts() | Actualiza la caché de fuentes para archivos PSD que contienen capas de texto. Este método garantiza que las fuentes de la carpeta fontsFolder usando<br/>            el método FontSettings.SetFontsFolder(fontsFolder) o, después de restablecer fuentes usando FontSettings.Reset(), se tengan en cuenta al procesar archivos PSD. Por favor, use este método cada vez que <br/>            se llame a FontSettings.SetFontsFolder(fontsFolder) o FontSettings.Reset() para imágenes PSD. Sin llamar a este método no hay garantía de que las fuentes se actualicen. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__1}


```
 get_default_fonts_folders() 
```

Obtiene las carpetas predeterminadas de fuentes.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string[] | Devuelve la carpeta del sistema |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__2}


```
 get_fonts_folders() 
```

Obtiene una copia de la matriz que contiene la lista de carpetas donde Aspose.Words busca fuentes TrueType.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string[] | Una copia de las ubicaciones actuales de fuentes. |


### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_3}


```
 set_fonts_folder(font_folder) 
```

Este es un acceso directo a [FontSettings.set_fonts_folders(fonts_folders, recursive)](/imaging/python-net/aspose.imaging/fontsettings/) para establecer solo un directorio de fuentes.<br/>            No se realizan verificaciones en la carpeta de fuentes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_folder | string | La carpeta de fuentes. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_4}


```
 set_fonts_folders(fonts_folders, recursive) 
```

Establece las carpetas desde donde se cargan las fuentes TrueType y elimina todas las fuentes cargadas.<br/>            No se realizan verificaciones en las carpetas de fuentes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fonts_folders | string[] | Las carpetas de fuentes. |
| recursive | bool | si se establece en <c>true</c> [recursive]. |

