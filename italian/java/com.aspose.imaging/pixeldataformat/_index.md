---
title: "PixelDataFormat"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il formato dei dati pixel."
type: docs
weight: 84
url: /it/java/com.aspose.imaging/pixeldataformat/
---
**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

Il formato dei dati pixel. Questo è un oggetto immutabile.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Grayscale](#Grayscale) | Ottiene il [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) definito per 8 bit per pixel con 8 bit che rappresentano l'intensità in scala di grigi nell'intervallo 0-255. |
| [Grayscale16](#Grayscale16) | Definito per 16 bit per pixel con fino a 16 bit che rappresentano l'intensità in scala di grigi. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRgb32Bpp()](#getRgb32Bpp--) | Ottiene il `PixelDataFormat` definito per 32 bit per pixel con 8 bit per ciascuno di alfa, rosso, verde e blu. |
| [getCmyk()](#getCmyk--) | Ottiene il `PixelDataFormat` definito per 32 bit per pixel con 8 bit per ciascuno di ciano, magenta, giallo e nero. |
| [getCmyka()](#getCmyka--) | Ottiene l'acmyk. |
| [getRgb24Bpp()](#getRgb24Bpp--) | Ottiene il `PixelDataFormat` definito per 24 bit per pixel con 8 bit per ciascuno di alfa, rosso, verde e blu, alfa non è definito. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | Ottiene il `PixelDataFormat` definito per 16 bit per pixel con 5 bit per ciascuno di rosso, verde e blu, alfa non è definito. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | Ottiene il `PixelDataFormat` definito per 16 bit per pixel con 5 bit per rosso, 6 bit per verde e 5 bit per blu, alfa non è definito. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Ottiene il `PixelDataFormat` definito per indicizzato a 8 bit per colore. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Ottiene il `PixelDataFormat` definito per indicizzato a 4 bit per colore. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Ottiene il `PixelDataFormat` definito per indicizzato a 2 bit per colore. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Ottiene il `PixelDataFormat` definito per indicizzato a 1 bit per colore. |
| [getYCbCr()](#getYCbCr--) | Ottiene il `PixelDataFormat` definito per 24 bit per pixel con 8 bit per ciascuno dei componenti di crominanza luma, differenza blu e differenza rossa. |
| [getYcck()](#getYcck--) | Ottiene il `PixelDataFormat` definito per 32 bit per pixel con 8 bit per ciascuno dei componenti di crominanza luma, differenza blu, differenza rossa e nero. |
| [getRgba32Bpp()](#getRgba32Bpp--) | Ottiene il `PixelDataFormat` definito per 32 bit per pixel con 8 bit per ciascuno di alfa, rosso, verde e blu. |
| [getRgb24BppPng()](#getRgb24BppPng--) | Ottiene il `PixelDataFormat` definito per 24 bit per pixel con 8 bit per ciascuno di alfa, rosso, verde e blu, alfa non è definito. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | Ottiene il `PixelDataFormat` definito per 16 bit per pixel con 8 bit che rappresentano l'intensità in scala di grigi nell'intervallo 0-255 e un ulteriore componente alfa a 8 bit. |
| [getPixelFormat()](#getPixelFormat--) | Ottiene il formato pixel. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ottiene i bit per pixel. |
| [getChannelsCount()](#getChannelsCount--) | Ottiene il conteggio dei canali. |
| [getChannelBits()](#getChannelBits--) | Restituisce il conteggio dei bit per ciascun canale. |
| [getCaption()](#getCaption--) | Restituisce la didascalia del formato dei dati pixel. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Restituisce il colore in scala di grigi con un numero specificato di bit per campione. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Restituisce il colore GrayscaleAlpha con un numero specificato di bit per campione. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Restituisce il colore GrayscaleAlpha con un numero specificato di bit per campione. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Restituisce il colore RGB con un numero specificato di bit per campione. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Restituisce il colore RGB con un numero specificato di bit per campione. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Restituisce il colore RGBA con un numero specificato di bit per campione. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Restituisce il colore RGBA con un numero specificato di bit per campione. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Restituisce il colore indicizzato BGRA con un numero specificato di bit per campione. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Restituisce il colore BGRA con un numero specificato di bit per campione. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Restituisce il colore BGR con un numero specificato di bit per campione. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Restituisce il colore YCbCr con un numero specificato di bit per campione. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Restituisce il colore YCbCr con un numero specificato di bit per campione. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Restituisce il colore CMYK con un numero specificato di bit per campione. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Restituisce il colore CMYK con un numero specificato di bit per campione. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Restituisce il colore CMYKA con un numero specificato di bit per campione. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Restituisce il colore YCCK con un numero specificato di bit per campione. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Restituisce il colore CIE Lab con un numero specificato di bit per campione. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Restituisce il risultato della non uguaglianza per due classi `PixelDataFormat`. |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Restituisce il risultato dell'uguaglianza per due classi `PixelDataFormat`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se lo `System.Object` specificato è uguale a questa istanza. |
| [hashCode()](#hashCode--) | Restituisce un codice hash per questa istanza. |
| [toString()](#toString--) | Restituisce una `System.String` che rappresenta questa istanza. |
### Grayscale {#Grayscale}
```
public static final PixelDataFormat Grayscale
```


Ottiene il [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) definito per 8 bit per pixel con 8 bit che rappresentano l'intensità in scala di grigi nell'intervallo 0-255.

Valore: Il [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) definito per 8 bit per pixel con 8 bit che rappresentano l'intensità in scala di grigi nell'intervallo 0-255.

### Grayscale16 {#Grayscale16}
```
public static final PixelDataFormat Grayscale16
```


Definito per 16 bit per pixel con fino a 16 bit che rappresentano l'intensità in scala di grigi.

### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


Ottiene il `PixelDataFormat` definito per 32 bit per pixel con 8 bit per ciascuno di alfa, rosso, verde e blu.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getCmyk() {#getCmyk--}
```
public static PixelDataFormat getCmyk()
```


Ottiene il `PixelDataFormat` definito per 32 bit per pixel con 8 bit per ciascuno di ciano, magenta, giallo e nero.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


Ottiene l'acmyk.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


Ottiene il `PixelDataFormat` definito per 24 bit per pixel con 8 bit per ciascuno di alfa, rosso, verde e blu, alfa non è definito.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


Ottiene il `PixelDataFormat` definito per 16 bit per pixel con 5 bit per ciascuno di rosso, verde e blu, alfa non è definito.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


Ottiene il `PixelDataFormat` definito per 16 bit per pixel con 5 bit per rosso, 6 bit per verde e 5 bit per blu, alfa non è definito.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


Restituisce il `PixelDataFormat` definito per 8 bit indicizzati per colore. L'archiviazione dei dati pixel indicizzati è destinata a consentire l'archiviazione e il recupero dei dati ovunque venga utilizzata la tavolozza dei colori. Usare con cautela, poiché potrebbe richiedere la conversione da una tavolozza all'altra o da RGBA a modello di colore indicizzato.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 8 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


Restituisce il `PixelDataFormat` definito per 4 bit indicizzati per colore. L'archiviazione dei dati pixel indicizzati è destinata a consentire l'archiviazione e il recupero dei dati ovunque venga utilizzata la tavolozza dei colori. Usare con cautela, poiché potrebbe richiedere la conversione da una tavolozza all'altra o da RGBA a modello di colore indicizzato.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 4 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


Restituisce il `PixelDataFormat` definito per 2 bit indicizzati per colore. L'archiviazione dei dati pixel indicizzati è destinata a consentire l'archiviazione e il recupero dei dati ovunque venga utilizzata la tavolozza dei colori. Usare con cautela, poiché potrebbe richiedere la conversione da una tavolozza all'altra o da RGBA a modello di colore indicizzato.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 2 bit per color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


Restituisce il `PixelDataFormat` definito per 1 bit indicizzato per colore. L'archiviazione dei dati pixel indicizzati è destinata a consentire l'archiviazione e il recupero dei dati ovunque venga utilizzata la tavolozza dei colori. Usare con cautela, poiché potrebbe richiedere la conversione da una tavolozza all'altra o da RGBA a modello di colore indicizzato.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 1 bit per color.
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


Ottiene il `PixelDataFormat` definito per 24 bit per pixel con 8 bit per ciascuno dei componenti di crominanza luma, differenza blu e differenza rossa.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


Ottiene il `PixelDataFormat` definito per 32 bit per pixel con 8 bit per ciascuno dei componenti di crominanza luma, differenza blu, differenza rossa e nero.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


Ottiene il `PixelDataFormat` definito per 32 bit per pixel con 8 bit per ciascuno di alfa, rosso, verde e blu.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


Ottiene il `PixelDataFormat` definito per 24 bit per pixel con 8 bit per ciascuno di alfa, rosso, verde e blu, alfa non è definito.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


Ottiene il `PixelDataFormat` definito per 16 bit per pixel con 8 bit che rappresentano l'intensità in scala di grigi nell'intervallo 0-255 e un ulteriore componente alfa a 8 bit.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Ottiene il formato pixel.

**Returns:**
int - Il formato pixel.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ottiene i bit per pixel.

**Returns:**
int - I bit per pixel.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Ottiene il conteggio dei canali.

**Returns:**
int - Il conteggio dei canali.
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Restituisce il conteggio dei bit per ciascun canale.

**Returns:**
int[] - I bit del canale.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Restituisce la didascalia del formato dei dati pixel.

**Returns:**
java.lang.String
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Restituisce il colore in scala di grigi con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Restituisce il colore GrayscaleAlpha con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Restituisce il colore GrayscaleAlpha con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |
| alphaChannelBits | int | Il numero di bit per campione nel canale alfa. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Restituisce il colore RGB con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Restituisce il colore RGB con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerRedChannel | int | Il numero di bit per il canale Rosso. |
| bitsPerGreenChannel | int | Il numero di bit per il canale Verde. |
| bitsPerBlueChannel | int | Il numero di bit per il canale Blu. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Restituisce il colore RGBA con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Restituisce il colore RGBA con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerRedChannel | int | Il numero di bit per il canale Rosso. |
| bitsPerGreenChannel | int | Il numero di bit per il canale Verde. |
| bitsPerBlueChannel | int | Il numero di bit per il canale Blu. |
| bitsPerAlphaChannel | int | Il numero di bit per il canale Alfa. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Restituisce il colore indicizzato BGRA con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Restituisce il colore BGRA con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Restituisce il colore BGR con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGR color.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Restituisce il colore YCbCr con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Restituisce il colore YCbCr con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerY | int | Il numero di bit per il canale Y. |
| bitsPerCb | int | Il numero di bit per il canale Cb. |
| bitsPerCr | int | Il numero di bit per il canale Cr. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Restituisce il colore CMYK con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Restituisce il colore CMYK con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerCyanChannel | int | Il numero di bit per il canale Ciano. |
| bitsPerMagentaChannel | int | Il numero di bit per il canale Magenta. |
| bitsPerYellowChannel | int | Il numero di bit per il canale Yellow. |
| bitsPerKeyChannel | int | Il numero di bit per il canale Key. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Restituisce il colore CMYKA con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerCyanChannel | int | Il numero di bit per il canale Ciano. |
| bitsPerMagentaChannel | int | Il numero di bit per il canale Magenta. |
| bitsPerYellowChannel | int | Il numero di bit per il canale Yellow. |
| bitsPerKeyChannel | int | Il numero di bit per il canale Key. |
| bitsPerAlphaChannel | int | Il numero di bit per il canale Alfa. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Restituisce il colore YCCK con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerSample | int | Il numero di bit per campione. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCCK color.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Restituisce il colore CIE Lab con un numero specificato di bit per campione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bitsPerL | int | Il numero di bit per il canale L. |
| bitsPerA | int | Il numero di bit per il canale A. |
| bitsPerB | int | Il numero di bit per il canale B. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CIE Lab color.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Restituisce il risultato della non uguaglianza per due classi `PixelDataFormat`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Il primo `PixelDataFormat` da confrontare. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Il secondo `PixelDataFormat` da confrontare. |

**Returns:**
boolean - Vero se entrambi `pixelFormat1` e `pixelFormat2` contengono dati non uguali o uno dei parametri è nullo.
### op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Restituisce il risultato dell'uguaglianza per due classi `PixelDataFormat`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Il primo `PixelDataFormat` da confrontare. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Il secondo `PixelDataFormat` da confrontare. |

**Returns:**
boolean - Vero se entrambi `pixelFormat1` e `pixelFormat2` contengono dati uguali o entrambi i parametri sono nulli.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se lo `System.Object` specificato è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Il `System.Object` da confrontare con questa istanza. |

**Returns:**
boolean - `true` se lo `System.Object` specificato è uguale a questa istanza; altrimenti, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Restituisce un codice hash per questa istanza.

**Returns:**
int - Un codice hash per questa istanza, adatto per l'uso in algoritmi di hashing e strutture dati come una tabella hash.
### toString() {#toString--}
```
public String toString()
```


Restituisce una `System.String` che rappresenta questa istanza.

**Returns:**
java.lang.String - Una `System.String` che rappresenta questa istanza.
