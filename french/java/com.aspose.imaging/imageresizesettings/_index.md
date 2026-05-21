---
title: "ImageResizeSettings"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Classe des paramètres de redimensionnement d'image"
type: docs
weight: 63
url: /fr/java/com.aspose.imaging/imageresizesettings/
---
**Inheritance:**
java.lang.Object
```
public class ImageResizeSettings
```

Classe des paramètres de redimensionnement d'image
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImageResizeSettings()](#ImageResizeSettings--) | Initialise une nouvelle instance de la classe `ImageResizeSettings` avec le type de redimensionnement = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample)) avec le type de filtre = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular)) avec la méthode de quantification des couleurs = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity)) avec la méthode de comparaison des couleurs = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) avec le nombre d'entrées de couleur = 256 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType)](#ImageResizeSettings-int-) | Initialise une nouvelle instance de la classe [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) avec le type de filtre = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None)) avec la méthode de quantification des couleurs = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) avec la méthode de comparaison des couleurs = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) avec le nombre d'entrées de couleur = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType)](#ImageResizeSettings-int-int-) | Initialise une nouvelle instance de la classe [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) avec la méthode de quantification des couleurs = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) avec la méthode de comparaison des couleurs = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) avec le nombre d'entrées de couleur = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)](#ImageResizeSettings-int-int-int-) | Initialise une nouvelle instance de la classe [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) avec la méthode de comparaison des couleurs = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) avec le nombre d'entrées de couleur = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)](#ImageResizeSettings-int-int-int-int-) | Initialise une nouvelle instance de la classe [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) avec le nombre d'entrées de couleur = 0 (\#getEntriesCount().getEntriesCount()) |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | Obtient le nombre d'entrées |
| [setEntriesCount(int value)](#setEntriesCount-int-) | Définit le nombre d'entrées |
| [getMode()](#getMode--) | Obtient le mode d'interpolation. |
| [setMode(int value)](#setMode-int-) | Définit le mode d'interpolation. |
| [getFilterType()](#getFilterType--) | Obtient le type du filtre. |
| [setFilterType(int value)](#setFilterType-int-) | Définit le type du filtre. |
| [getColorQuantizationMethod()](#getColorQuantizationMethod--) | Obtient la méthode de quantification des couleurs. |
| [setColorQuantizationMethod(int value)](#setColorQuantizationMethod-int-) | Définit la méthode de quantification des couleurs. |
| [getColorCompareMethod()](#getColorCompareMethod--) | Obtient la méthode de comparaison des couleurs. |
| [setColorCompareMethod(int value)](#setColorCompareMethod-int-) | Définit la méthode de comparaison des couleurs. |
### ImageResizeSettings() {#ImageResizeSettings--}
```
public ImageResizeSettings()
```


Initialise une nouvelle instance de la classe `ImageResizeSettings` avec le type de redimensionnement = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample)) avec le type de filtre = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular)) avec la méthode de quantification des couleurs = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity)) avec la méthode de comparaison des couleurs = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) avec le nombre d'entrées de couleur = 256 (\#getEntriesCount().getEntriesCount())

### ImageResizeSettings(int resizeType) {#ImageResizeSettings-int-}
```
public ImageResizeSettings(int resizeType)
```


Initialise une nouvelle instance de la classe [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) avec le type de filtre = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None)) avec la méthode de quantification des couleurs = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) avec la méthode de comparaison des couleurs = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) avec le nombre d'entrées de couleur = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| resizeType | int | Type de redimensionnement. |

### ImageResizeSettings(int resizeType, int filterType) {#ImageResizeSettings-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType)
```


Initialise une nouvelle instance de la classe [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) avec la méthode de quantification des couleurs = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) avec la méthode de comparaison des couleurs = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) avec le nombre d'entrées de couleur = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| resizeType | int | Type de redimensionnement. |
| filterType | int | Type de filtre. |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod) {#ImageResizeSettings-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)
```


Initialise une nouvelle instance de la classe [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) avec la méthode de comparaison des couleurs = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) avec le nombre d'entrées de couleur = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| resizeType | int | Type de redimensionnement. |
| filterType | int | Type de filtre. |
| colorQuantizationMethod | int | Méthode de quantification des couleurs. |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod) {#ImageResizeSettings-int-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)
```


Initialise une nouvelle instance de la classe [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) avec le nombre d'entrées de couleur = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| resizeType | int | Type de redimensionnement. |
| filterType | int | Type de filtre. |
| colorQuantizationMethod | int | Méthode de quantification des couleurs. |
| colorCompareMethod | int | Méthode de comparaison des couleurs. |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Obtient le nombre d'entrées

**Returns:**
int - Le nombre d'entrées
### setEntriesCount(int value) {#setEntriesCount-int-}
```
public void setEntriesCount(int value)
```


Définit le nombre d'entrées

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le nombre d'entrées |

### getMode() {#getMode--}
```
public int getMode()
```


Obtient le mode d'interpolation.

**Returns:**
int - Le mode.
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Définit le mode d'interpolation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le mode. |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Obtient le type du filtre.

**Returns:**
int - Le type du filtre.
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Définit le type du filtre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le type du filtre. |

### getColorQuantizationMethod() {#getColorQuantizationMethod--}
```
public int getColorQuantizationMethod()
```


Obtient la méthode de quantification des couleurs.

**Returns:**
int - La méthode de quantification des couleurs.
### setColorQuantizationMethod(int value) {#setColorQuantizationMethod-int-}
```
public void setColorQuantizationMethod(int value)
```


Définit la méthode de quantification des couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La méthode de quantification des couleurs. |

### getColorCompareMethod() {#getColorCompareMethod--}
```
public int getColorCompareMethod()
```


Obtient la méthode de comparaison des couleurs.

**Returns:**
int - La méthode de comparaison des couleurs.
### setColorCompareMethod(int value) {#setColorCompareMethod-int-}
```
public void setColorCompareMethod(int value)
```


Définit la méthode de comparaison des couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La méthode de comparaison des couleurs. |

