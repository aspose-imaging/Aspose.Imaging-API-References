---
title: "RawDataSettings"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le impostazioni dei dati grezzi"
type: docs
weight: 92
url: /it/java/com.aspose.imaging/rawdatasettings/
---
**Inheritance:**
java.lang.Object
```
public class RawDataSettings
```

Le impostazioni dei dati grezzi
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RawDataSettings()](#RawDataSettings--) | Istanza vuota inizializzata. |
| [RawDataSettings(RawDataSettings origin)](#RawDataSettings-com.aspose.imaging.RawDataSettings-) | Inizializza una copia di `origin`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPixelDataFormat()](#getPixelDataFormat--) | Ottiene il formato dei dati pixel |
| [setPixelDataFormat(PixelDataFormat value)](#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Imposta il formato dei dati pixel |
| [getColorPalette()](#getColorPalette--) | Ottiene la tavolozza dei colori |
| [setColorPalette(IColorPalette value)](#setColorPalette-com.aspose.imaging.IColorPalette-) | Imposta la tavolozza dei colori |
| [getDitheringMethod()](#getDitheringMethod--) | Ottiene il metodo di dithering da utilizzare per la conversione dei dati grezzi |
| [setDitheringMethod(int value)](#setDitheringMethod-int-) | Imposta il metodo di dithering da utilizzare per la conversione dei dati grezzi |
| [getIndexedColorConverter()](#getIndexedColorConverter--) | Ottiene il convertitore di colore indicizzato |
| [setIndexedColorConverter(IIndexedColorConverter value)](#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-) | Imposta il convertitore di colore indicizzato |
| [getCustomColorConverter()](#getCustomColorConverter--) | Ottiene il convertitore di colore personalizzato |
| [setCustomColorConverter(IColorConverter value)](#setCustomColorConverter-com.aspose.imaging.IColorConverter-) | Imposta il convertitore di colore personalizzato |
| [getFallbackIndex()](#getFallbackIndex--) | Ottiene l'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti |
| [setFallbackIndex(int value)](#setFallbackIndex-int-) | Imposta l'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti |
| [getLineSize()](#getLineSize--) | Ottiene la dimensione della riga dei pixel in byte per l'elaborazione dei dati grezzi |
| [setLineSize(int value)](#setLineSize-int-) | Imposta la dimensione della riga dei pixel in byte per l'elaborazione dei dati grezzi |
| [<T>copy()](#-T-copy--) | Crea una copia superficiale. |
### RawDataSettings() {#RawDataSettings--}
```
public RawDataSettings()
```


Istanza vuota inizializzata.

### RawDataSettings(RawDataSettings origin) {#RawDataSettings-com.aspose.imaging.RawDataSettings-}
```
public RawDataSettings(RawDataSettings origin)
```


Inizializza una copia di `origin`. Utilizzato in [copy()](../../com.aspose.imaging/rawdatasettings\#copy--).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| origin | [RawDataSettings](../../com.aspose.imaging/rawdatasettings) | L'istanza da copiare. |

### getPixelDataFormat() {#getPixelDataFormat--}
```
public PixelDataFormat getPixelDataFormat()
```


Ottiene il formato dei dati pixel

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The pixel data format
### setPixelDataFormat(PixelDataFormat value) {#setPixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public void setPixelDataFormat(PixelDataFormat value)
```


Imposta il formato dei dati pixel

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Il formato dei dati pixel |

### getColorPalette() {#getColorPalette--}
```
public IColorPalette getColorPalette()
```


Ottiene la tavolozza dei colori

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette
### setColorPalette(IColorPalette value) {#setColorPalette-com.aspose.imaging.IColorPalette-}
```
public void setColorPalette(IColorPalette value)
```


Imposta la tavolozza dei colori

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La tavolozza dei colori |

### getDitheringMethod() {#getDitheringMethod--}
```
public int getDitheringMethod()
```


Ottiene il metodo di dithering da utilizzare per la conversione dei dati grezzi

**Returns:**
int - Il metodo di dithering da utilizzare per la conversione dei dati grezzi
### setDitheringMethod(int value) {#setDitheringMethod-int-}
```
public void setDitheringMethod(int value)
```


Imposta il metodo di dithering da utilizzare per la conversione dei dati grezzi

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il metodo di dithering da utilizzare per la conversione dei dati grezzi |

### getIndexedColorConverter() {#getIndexedColorConverter--}
```
public IIndexedColorConverter getIndexedColorConverter()
```


Ottiene il convertitore di colore indicizzato

**Returns:**
[IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) - The indexed color converter
### setIndexedColorConverter(IIndexedColorConverter value) {#setIndexedColorConverter-com.aspose.imaging.IIndexedColorConverter-}
```
public void setIndexedColorConverter(IIndexedColorConverter value)
```


Imposta il convertitore di colore indicizzato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.imaging/iindexedcolorconverter) | Il convertitore di colore indicizzato |

### getCustomColorConverter() {#getCustomColorConverter--}
```
public IColorConverter getCustomColorConverter()
```


Ottiene il convertitore di colore personalizzato

**Returns:**
[IColorConverter](../../com.aspose.imaging/icolorconverter) - The custom color converter
### setCustomColorConverter(IColorConverter value) {#setCustomColorConverter-com.aspose.imaging.IColorConverter-}
```
public void setCustomColorConverter(IColorConverter value)
```


Imposta il convertitore di colore personalizzato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.imaging/icolorconverter) | Il convertitore di colore personalizzato |

### getFallbackIndex() {#getFallbackIndex--}
```
public int getFallbackIndex()
```


Ottiene l'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti

**Returns:**
int - L'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti
### setFallbackIndex(int value) {#setFallbackIndex-int-}
```
public void setFallbackIndex(int value)
```


Imposta l'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | L'indice di fallback da utilizzare quando l'indice della tavolozza è fuori dai limiti |

### getLineSize() {#getLineSize--}
```
public int getLineSize()
```


Ottiene la dimensione della riga dei pixel in byte per l'elaborazione dei dati grezzi

**Returns:**
int - La dimensione della riga dei pixel in byte per l'elaborazione dei dati grezzi
### setLineSize(int value) {#setLineSize-int-}
```
public void setLineSize(int value)
```


Imposta la dimensione della riga dei pixel in byte per l'elaborazione dei dati grezzi

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | La dimensione della riga di pixel in byte per l'elaborazione dei dati grezzi |

### <T>copy() {#-T-copy--}
```
public T <T>copy()
```


Crea una copia superficiale.

**Returns:**
T - Una copia superficiale.
