---
title: "FontSettings"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Configuración de fuentes del renderizador de formatos vectoriales de imagen generales."
type: docs
weight: 49
url: /es/java/com.aspose.imaging/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

Configuración de fuentes del renderizador de formatos vectoriales de imagen generales.
## Métodos

| Método | Descripción |
| --- | --- |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | Obtiene un valor que indica si [get alternative font]. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | Establece un valor que indica si [get alternative font]. |
| [getDefaultFontName()](#getDefaultFontName--) | Obtiene el nombre de fuente predeterminado. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Establece el nombre de fuente predeterminado. |
| [getFontsFolders()](#getFontsFolders--) | Obtiene una copia de la matriz que contiene la lista de carpetas donde Aspose.Imaging busca fuentes TrueType. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Obtiene las carpetas de fuentes predeterminadas. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | Sobrescribir la lista de carpetas de fuentes para `folder` |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | Sobrescribir la lista de carpetas de fuentes para `folders` |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | Establece las carpetas desde donde se cargan las fuentes TrueType y elimina todas las fuentes cargadas. |
| [reset()](#reset--) | Restablece la carpeta de fuentes y el nombre de fuente predeterminado al valor predeterminado del sistema. |
| [updateFonts()](#updateFonts--) | Actualiza la caché de fuentes para archivos PSD que contienen capas de texto. |
| [addFontsFolder(String fontFolder)](#addFontsFolder-java.lang.String-) | Agrega el `fontFolder` a la lista de directorios de fuentes y lo marca como la primera carpeta para la búsqueda de fuentes |
| [removeFontsFolder(String folder)](#removeFontsFolder-java.lang.String-) | Elimina `folder` de la lista de carpetas |
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


Obtiene un valor que indica si [get alternative font].

Valor: `true` si [get alternative font]; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si [get alternative font].
### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


Establece un valor que indica si [get alternative font].

Valor: `true` si [get alternative font]; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | un valor que indica si [get alternative font]. |

### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


Obtiene el nombre de fuente predeterminado.

**Returns:**
java.lang.String - nombre de la fuente predeterminada
### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Establece el nombre de fuente predeterminado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | El nombre predeterminado de la fuente. |

### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Obtiene una copia de la matriz que contiene la lista de carpetas donde Aspose.Imaging busca fuentes TrueType.

El valor devuelto es una copia de los datos que usa Aspose.Imaging. Si cambias las entradas en la matriz devuelta, no tendrá ningún efecto en la renderización del documento. Para especificar nuevas ubicaciones de fuentes usa el método `setFontsFolders`.

**Returns:**
java.lang.String[] - Una copia de las ubicaciones actuales de fuentes.
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Obtiene las carpetas de fuentes predeterminadas.

**Returns:**
java.lang.String[] - Devuelve la carpeta del sistema
### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


Sobrescribir la lista de carpetas de fuentes para `folder`

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| folder | java.lang.String | Carpeta con fuentes TrueType. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


Sobrescribir la lista de carpetas de fuentes para `folders`

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| folders | java.lang.String[] | Matriz de carpetas |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


Establece las carpetas desde donde se cargan las fuentes TrueType y borra todas las fuentes cargadas. No se realizan comprobaciones en las carpetas de fuentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| folders | java.lang.String[] | Las carpetas de fuentes. |
| recursive | boolean | si se establece en `true` [recursive]. |

### reset() {#reset--}
```
public static void reset()
```


Restablece la carpeta de fuentes y el nombre de fuente predeterminado al valor predeterminado del sistema.

### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


Actualiza la caché de fuentes para archivos PSD que contienen capas de texto. Este método garantiza que las fuentes de la carpeta fontsFolder mediante el método FontSettings.setFontsFolder(fontsFolder) o después de restablecer fuentes usando FontSettings.reset() se tengan en cuenta al procesar archivos PSD. Por favor, use este método cada vez que se llame a FontSettings.setFontsFolder(fontsFolder) o FontSettings.reset() para imágenes PSD. Sin llamar a este método no hay garantía de que las fuentes se actualicen.

### addFontsFolder(String fontFolder) {#addFontsFolder-java.lang.String-}
```
public static void addFontsFolder(String fontFolder)
```


Agrega el `fontFolder` a la lista de directorios de fuentes y lo marca como la primera carpeta para la búsqueda de fuentes

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontFolder | java.lang.String | La carpeta contiene las fuentes TrueType o la ruta a un archivo de fuente único. |

### removeFontsFolder(String folder) {#removeFontsFolder-java.lang.String-}
```
public static void removeFontsFolder(String folder)
```


Elimina `folder` de la lista de carpetas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| folder | java.lang.String | La carpeta a eliminar |

