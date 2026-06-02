---
title: "PdfCoreOptions"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Las opciones comunes para la conversión a PDF"
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.pdf/pdfcoreoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfCoreOptions
```

Las opciones comunes para la conversión a PDF
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfCoreOptions()](#PdfCoreOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Especifica cuántos niveles de elementos de esquema incluir en el esquema del documento. |
| [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Especifica cuántos niveles de elementos de esquema incluir en el esquema del documento. |
| [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Especifica cuántos niveles del esquema del documento se mostrarán expandidos al visualizar el archivo PDF. |
| [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Especifica cuántos niveles del esquema del documento se mostrarán expandidos al visualizar el archivo PDF. |
| [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Especifica en qué nivel del esquema del documento se mostrarán los objetos de marcador. |
| [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Especifica en qué nivel del esquema del documento se mostrarán los objetos de marcador. |
| [getJpegQuality()](#getJpegQuality--) | Especifica la calidad de la compresión JPEG para imágenes (si se utiliza compresión JPEG). |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Especifica la calidad de la compresión JPEG para imágenes (si se utiliza compresión JPEG). |
| [getPdfCompliance()](#getPdfCompliance--) | Obtiene el cumplimiento PDF. |
| [setPdfCompliance(int value)](#setPdfCompliance-int-) | Establece el cumplimiento PDF. |
| [getCompression()](#getCompression--) | Obtiene la compresión. |
| [setCompression(int value)](#setCompression-int-) | Establece la compresión. |
### PdfCoreOptions() {#PdfCoreOptions--}
```
public PdfCoreOptions()
```


### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public int getHeadingsOutlineLevels()
```


Especifica cuántos niveles de elementos de esquema incluir en el esquema del documento. 0 - sin esquema, 1 - un nivel de esquema y así sucesivamente. El valor predeterminado es 0.

**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public void setHeadingsOutlineLevels(int value)
```


Especifica cuántos niveles de elementos de esquema incluir en el esquema del documento. 0 - sin esquema, 1 - un nivel de esquema y así sucesivamente. El valor predeterminado es 0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public int getExpandedOutlineLevels()
```


Especifica cuántos niveles del esquema del documento se mostrarán expandidos al visualizar el archivo PDF. 0 - el esquema del documento no está expandido. 1 - los elementos del primer nivel del documento están expandidos y así sucesivamente. El valor predeterminado es 0.

**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public void setExpandedOutlineLevels(int value)
```


Especifica cuántos niveles del esquema del documento se mostrarán expandidos al visualizar el archivo PDF. 0 - el esquema del documento no está expandido. 1 - los elementos del primer nivel del documento están expandidos y así sucesivamente. El valor predeterminado es 0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public int getBookmarksOutlineLevel()
```


Especifica en qué nivel del esquema del documento se mostrarán los objetos de marcador. 0 - no se muestra. 1 en el primer nivel y así sucesivamente. El valor predeterminado es 0.

**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public void setBookmarksOutlineLevel(int value)
```


Especifica en qué nivel del esquema del documento se mostrarán los objetos de marcador. 0 - no se muestra. 1 en el primer nivel y así sucesivamente. El valor predeterminado es 0.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


Especifica la calidad de la compresión JPEG para imágenes (si se utiliza compresión JPEG). El valor predeterminado es 95.

**Returns:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Especifica la calidad de la compresión JPEG para imágenes (si se utiliza compresión JPEG). El valor predeterminado es 95.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPdfCompliance() {#getPdfCompliance--}
```
public final int getPdfCompliance()
```


Obtiene el cumplimiento PDF.

**Returns:**
int - el cumplimiento PDF.
### setPdfCompliance(int value) {#setPdfCompliance-int-}
```
public final void setPdfCompliance(int value)
```


Establece el cumplimiento PDF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | el cumplimiento PDF. |

### getCompression() {#getCompression--}
```
public final int getCompression()
```


Obtiene la compresión.

Valor: La compresión.

**Returns:**
int - la compresión.
### setCompression(int value) {#setCompression-int-}
```
public final void setCompression(int value)
```


Establece la compresión.

Valor: La compresión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | la compresión. |

