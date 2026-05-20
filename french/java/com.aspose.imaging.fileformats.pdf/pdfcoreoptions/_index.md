---
title: "PdfCoreOptions"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les options courantes pour la conversion en PDF"
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.pdf/pdfcoreoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfCoreOptions
```

Les options courantes pour la conversion en PDF
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfCoreOptions()](#PdfCoreOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Spécifie le nombre de niveaux d'éléments de plan à inclure dans le plan du document. |
| [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Spécifie le nombre de niveaux d'éléments de plan à inclure dans le plan du document. |
| [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Spécifie le nombre de niveaux du plan du document à afficher développés lors de la visualisation du fichier PDF. |
| [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Spécifie le nombre de niveaux du plan du document à afficher développés lors de la visualisation du fichier PDF. |
| [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Spécifie à quel niveau du plan du document afficher les objets de signet. |
| [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Spécifie à quel niveau du plan du document afficher les objets de signet. |
| [getJpegQuality()](#getJpegQuality--) | Spécifie la qualité de la compression JPEG pour les images (si la compression JPEG est utilisée). |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Spécifie la qualité de la compression JPEG pour les images (si la compression JPEG est utilisée). |
| [getPdfCompliance()](#getPdfCompliance--) | Obtient la conformité PDF. |
| [setPdfCompliance(int value)](#setPdfCompliance-int-) | Définit la conformité PDF. |
| [getCompression()](#getCompression--) | Obtient la compression. |
| [setCompression(int value)](#setCompression-int-) | Définit la compression. |
### PdfCoreOptions() {#PdfCoreOptions--}
```
public PdfCoreOptions()
```


### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public int getHeadingsOutlineLevels()
```


Spécifie le nombre de niveaux d'éléments de plan à inclure dans le plan du document. 0 - aucun plan, 1 - un niveau de plan, etc. La valeur par défaut est 0.

**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public void setHeadingsOutlineLevels(int value)
```


Spécifie le nombre de niveaux d'éléments de plan à inclure dans le plan du document. 0 - aucun plan, 1 - un niveau de plan, etc. La valeur par défaut est 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public int getExpandedOutlineLevels()
```


Spécifie le nombre de niveaux du plan du document à afficher développés lors de la visualisation du fichier PDF. 0 - le plan du document n'est pas développé. 1 - les éléments du premier niveau du document sont développés, etc. La valeur par défaut est 0.

**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public void setExpandedOutlineLevels(int value)
```


Spécifie le nombre de niveaux du plan du document à afficher développés lors de la visualisation du fichier PDF. 0 - le plan du document n'est pas développé. 1 - les éléments du premier niveau du document sont développés, etc. La valeur par défaut est 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public int getBookmarksOutlineLevel()
```


Spécifie à quel niveau du plan du document afficher les objets de signet. 0 - non affiché. 1 au premier niveau, etc. La valeur par défaut est 0.

**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public void setBookmarksOutlineLevel(int value)
```


Spécifie à quel niveau du plan du document afficher les objets de signet. 0 - non affiché. 1 au premier niveau, etc. La valeur par défaut est 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


Spécifie la qualité de la compression JPEG pour les images (si la compression JPEG est utilisée). La valeur par défaut est 95.

**Returns:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Spécifie la qualité de la compression JPEG pour les images (si la compression JPEG est utilisée). La valeur par défaut est 95.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getPdfCompliance() {#getPdfCompliance--}
```
public final int getPdfCompliance()
```


Obtient la conformité PDF.

**Returns:**
int - la conformité PDF.
### setPdfCompliance(int value) {#setPdfCompliance-int-}
```
public final void setPdfCompliance(int value)
```


Définit la conformité PDF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | la conformité PDF. |

### getCompression() {#getCompression--}
```
public final int getCompression()
```


Obtient la compression.

Valeur : la compression.

**Returns:**
int - la compression.
### setCompression(int value) {#setCompression-int-}
```
public final void setCompression(int value)
```


Définit la compression.

Valeur : la compression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | la compression. |

