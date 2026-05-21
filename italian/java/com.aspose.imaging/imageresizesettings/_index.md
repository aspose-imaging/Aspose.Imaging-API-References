---
title: "ImageResizeSettings"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Classe delle impostazioni di ridimensionamento dell'immagine"
type: docs
weight: 63
url: /it/java/com.aspose.imaging/imageresizesettings/
---
**Inheritance:**
java.lang.Object
```
public class ImageResizeSettings
```

Classe delle impostazioni di ridimensionamento dell'immagine
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageResizeSettings()](#ImageResizeSettings--) | Inizializza una nuova istanza della classe `ImageResizeSettings` con tipo di ridimensionamento = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample)) con tipo di filtro = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular)) con metodo di quantizzazione del colore = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity)) con metodo di confronto del colore = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) con conteggio delle voci di colore = 256 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType)](#ImageResizeSettings-int-) | Inizializza una nuova istanza della classe [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) con tipo di filtro = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None)) con metodo di quantizzazione del colore = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) con metodo di confronto del colore = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) con conteggio delle voci di colore = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType)](#ImageResizeSettings-int-int-) | Inizializza una nuova istanza della classe [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) con metodo di quantizzazione del colore = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) con metodo di confronto del colore = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) con conteggio delle voci di colore = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)](#ImageResizeSettings-int-int-int-) | Inizializza una nuova istanza della classe [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) con metodo di confronto del colore = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) con conteggio delle voci di colore = 0 (\#getEntriesCount().getEntriesCount()) |
| [ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)](#ImageResizeSettings-int-int-int-int-) | Inizializza una nuova istanza della classe [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) con conteggio delle voci di colore = 0 (\#getEntriesCount().getEntriesCount()) |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEntriesCount()](#getEntriesCount--) | Ottiene il conteggio delle voci |
| [setEntriesCount(int value)](#setEntriesCount-int-) | Imposta il conteggio delle voci |
| [getMode()](#getMode--) | Ottiene la modalità di interpolazione. |
| [setMode(int value)](#setMode-int-) | Imposta la modalità di interpolazione. |
| [getFilterType()](#getFilterType--) | Ottiene il tipo del filtro. |
| [setFilterType(int value)](#setFilterType-int-) | Imposta il tipo del filtro. |
| [getColorQuantizationMethod()](#getColorQuantizationMethod--) | Ottiene il metodo di quantizzazione del colore. |
| [setColorQuantizationMethod(int value)](#setColorQuantizationMethod-int-) | Imposta il metodo di quantizzazione del colore. |
| [getColorCompareMethod()](#getColorCompareMethod--) | Ottiene il metodo di confronto del colore. |
| [setColorCompareMethod(int value)](#setColorCompareMethod-int-) | Imposta il metodo di confronto del colore. |
### ImageResizeSettings() {#ImageResizeSettings--}
```
public ImageResizeSettings()
```


Inizializza una nuova istanza della classe `ImageResizeSettings` con tipo di ridimensionamento = ([ResizeType.BilinearResample](../../com.aspose.imaging/resizetype\#BilinearResample)) con tipo di filtro = ([ImageFilterType.SmallRectangular](../../com.aspose.imaging/imagefiltertype\#SmallRectangular)) con metodo di quantizzazione del colore = ([ColorQuantizationMethod.Popularity](../../com.aspose.imaging/colorquantizationmethod\#Popularity)) con metodo di confronto del colore = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) con conteggio delle voci di colore = 256 (\#getEntriesCount().getEntriesCount())

### ImageResizeSettings(int resizeType) {#ImageResizeSettings-int-}
```
public ImageResizeSettings(int resizeType)
```


Inizializza una nuova istanza della classe [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) con tipo di filtro = ([ImageFilterType.None](../../com.aspose.imaging/imagefiltertype\#None)) con metodo di quantizzazione del colore = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) con metodo di confronto del colore = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) con conteggio delle voci di colore = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resizeType | int | Tipo di ridimensionamento. |

### ImageResizeSettings(int resizeType, int filterType) {#ImageResizeSettings-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType)
```


Inizializza una nuova istanza della classe [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) con metodo di quantizzazione del colore = ([ColorQuantizationMethod.None](../../com.aspose.imaging/colorquantizationmethod\#None)) con metodo di confronto del colore = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) con conteggio delle voci di colore = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resizeType | int | Tipo di ridimensionamento. |
| filterType | int | Tipo di filtro. |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod) {#ImageResizeSettings-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod)
```


Inizializza una nuova istanza della classe [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) con metodo di confronto del colore = ([ColorCompareMethod.Euclidian](../../com.aspose.imaging/colorcomparemethod\#Euclidian)) con conteggio delle voci di colore = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resizeType | int | Tipo di ridimensionamento. |
| filterType | int | Tipo di filtro. |
| colorQuantizationMethod | int | Metodo di quantizzazione del colore. |

### ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod) {#ImageResizeSettings-int-int-int-int-}
```
public ImageResizeSettings(int resizeType, int filterType, int colorQuantizationMethod, int colorCompareMethod)
```


Inizializza una nuova istanza della classe [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) con conteggio delle voci di colore = 0 (\#getEntriesCount().getEntriesCount())

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| resizeType | int | Tipo di ridimensionamento. |
| filterType | int | Tipo di filtro. |
| colorQuantizationMethod | int | Metodo di quantizzazione del colore. |
| colorCompareMethod | int | Metodo di confronto del colore. |

### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Ottiene il conteggio delle voci

**Returns:**
int - Il conteggio delle voci
### setEntriesCount(int value) {#setEntriesCount-int-}
```
public void setEntriesCount(int value)
```


Imposta il conteggio delle voci

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il conteggio delle voci |

### getMode() {#getMode--}
```
public int getMode()
```


Ottiene la modalità di interpolazione.

**Returns:**
int - La modalità.
### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Imposta la modalità di interpolazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La modalità. |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


Ottiene il tipo del filtro.

**Returns:**
int - Il tipo del filtro.
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


Imposta il tipo del filtro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il tipo del filtro. |

### getColorQuantizationMethod() {#getColorQuantizationMethod--}
```
public int getColorQuantizationMethod()
```


Ottiene il metodo di quantizzazione del colore.

**Returns:**
int - Il metodo di quantizzazione del colore.
### setColorQuantizationMethod(int value) {#setColorQuantizationMethod-int-}
```
public void setColorQuantizationMethod(int value)
```


Imposta il metodo di quantizzazione del colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il metodo di quantizzazione del colore. |

### getColorCompareMethod() {#getColorCompareMethod--}
```
public int getColorCompareMethod()
```


Ottiene il metodo di confronto del colore.

**Returns:**
int - Il metodo di confronto del colore.
### setColorCompareMethod(int value) {#setColorCompareMethod-int-}
```
public void setColorCompareMethod(int value)
```


Imposta il metodo di confronto del colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il metodo di confronto del colore. |

