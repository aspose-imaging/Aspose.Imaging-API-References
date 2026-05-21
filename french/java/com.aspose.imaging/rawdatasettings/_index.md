---
title: "RawDataSettings"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les paramètres des données brutes"
type: docs
weight: 92
url: /fr/java/com.aspose.imaging/rawdatasettings/
---
**Inheritance:**
java.lang.Object
```
public class RawDataSettings
```

Les paramètres des données brutes
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RawDataSettings()](#RawDataSettings--) | Instance vide initialisée. |
| [RawDataSettings(RawDataSettings origin)](#RawDataSettings-com.aspose.imaging.RawDataSettings-) | Initialiser une copie de `origin`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPixelDataFormat()](#getPixelDataFormat--) | Obtient le format des données de pixel |
| [setPixelDataFormat(PixelDataFormat value)](#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Définit le format des données de pixel |
| [getColorPalette()](#getColorPalette--) | Obtient la palette de couleurs |
| [setColorPalette(IColorPalette value)](#setColorPalette-com.aspose.imaging.IColorPalette-) | Définit la palette de couleurs |
| [getDitheringMethod()](#getDitheringMethod--) | Obtient la méthode de tramage à utiliser pour la conversion de données brutes |
| [setDitheringMethod(int value)](#setDitheringMethod-int-) | Définit la méthode de tramage à utiliser pour la conversion de données brutes |
| [getIndexedColorConverter()](#getIndexedColorConverter--) | Obtient le convertisseur de couleur indexée |
| [setIndexedColorConverter(IIndexedColorConverter value)](#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | Définit le convertisseur de couleur indexée |
| [getCustomColorConverter()](#getCustomColorConverter--) | Obtient le convertisseur de couleur personnalisé |
| [setCustomColorConverter(IColorConverter value)](#setCustomColorConverter-com.aspose.imaging.IColorConverter-) | Définit le convertisseur de couleur personnalisé |
| [getFallbackIndex()](#getFallbackIndex--) | Obtient l'index de secours à utiliser lorsque l'index de la palette est hors limites |
| [setFallbackIndex(int value)](#setFallbackIndex-int-) | Définit l'index de secours à utiliser lorsque l'index de la palette est hors limites |
| [getLineSize()](#getLineSize--) | Obtient la taille de ligne des pixels en octets pour le traitement des données brutes |
| [setLineSize(int value)](#setLineSize-int-) | Définit la taille de ligne des pixels en octets pour le traitement des données brutes |
| [<T>copy()](#-T-copy--) | Crée une copie superficielle. |
### RawDataSettings() {#RawDataSettings--}
```
public RawDataSettings()
```


Instance vide initialisée.

### RawDataSettings(RawDataSettings origin) {#RawDataSettings-com.aspose.imaging.RawDataSettings-}
```
public RawDataSettings(RawDataSettings origin)
```


Initialise une copie de `origin`. Utilisé dans [copy()](../../com.aspose.imaging/rawdatasettings\#copy--).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| origin | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | L'instance à copier. |

### getPixelDataFormat() {#getPixelDataFormat--}
```
public PixelDataFormat getPixelDataFormat()
```


Obtient le format des données de pixel

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The pixel data format
### setPixelDataFormat(PixelDataFormat value) {#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public void setPixelDataFormat(PixelDataFormat value)
```


Définit le format des données de pixel

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Le format des données de pixel |

### getColorPalette() {#getColorPalette--}
```
public IColorPalette getColorPalette()
```


Obtient la palette de couleurs

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette
### setColorPalette(IColorPalette value) {#setColorPalette-com.aspose.imaging.IColorPalette-}
```
public void setColorPalette(IColorPalette value)
```


Définit la palette de couleurs

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette de couleurs |

### getDitheringMethod() {#getDitheringMethod--}
```
public int getDitheringMethod()
```


Obtient la méthode de tramage à utiliser pour la conversion de données brutes

**Returns:**
int - La méthode de tramage à utiliser pour la conversion de données brutes
### setDitheringMethod(int value) {#setDitheringMethod-int-}
```
public void setDitheringMethod(int value)
```


Définit la méthode de tramage à utiliser pour la conversion de données brutes

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La méthode de tramage à utiliser pour la conversion de données brutes |

### getIndexedColorConverter() {#getIndexedColorConverter--}
```
public IIndexedColorConverter getIndexedColorConverter()
```


Obtient le convertisseur de couleur indexée

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setIndexedColorConverter(IIndexedColorConverter value) {#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setIndexedColorConverter(IIndexedColorConverter value)
```


Définit le convertisseur de couleur indexée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | Le convertisseur de couleur indexée |

### getCustomColorConverter() {#getCustomColorConverter--}
```
public IColorConverter getCustomColorConverter()
```


Obtient le convertisseur de couleur personnalisé

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setCustomColorConverter(IColorConverter value) {#setCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setCustomColorConverter(IColorConverter value)
```


Définit le convertisseur de couleur personnalisé

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | Le convertisseur de couleur personnalisé |

### getFallbackIndex() {#getFallbackIndex--}
```
public int getFallbackIndex()
```


Obtient l'index de secours à utiliser lorsque l'index de la palette est hors limites

**Returns:**
int - L'index de secours à utiliser lorsque l'index de la palette est hors limites
### setFallbackIndex(int value) {#setFallbackIndex-int-}
```
public void setFallbackIndex(int value)
```


Définit l'index de secours à utiliser lorsque l'index de la palette est hors limites

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'index de secours à utiliser lorsque l'index de la palette est hors limites |

### getLineSize() {#getLineSize--}
```
public int getLineSize()
```


Obtient la taille de ligne des pixels en octets pour le traitement des données brutes

**Returns:**
int - La taille de ligne des pixels en octets pour le traitement des données brutes
### setLineSize(int value) {#setLineSize-int-}
```
public void setLineSize(int value)
```


Définit la taille de ligne des pixels en octets pour le traitement des données brutes

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La taille de ligne des pixels en octets pour le traitement des données brutes |

### <T>copy() {#-T-copy--}
```
public T <T>copy()
```


Crée une copie superficielle.

**Returns:**
T - Une copie superficielle.
