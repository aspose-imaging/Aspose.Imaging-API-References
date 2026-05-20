---
title: "PixelDataFormat"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le format des données pixel."
type: docs
weight: 84
url: /fr/java/com.aspose.imaging/pixeldataformat/
---
**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

Le format de données pixel. C'est un objet immuable.
## Champs

| Champ | Description |
| --- | --- |
| [Grayscale](#Grayscale) | Obtient le [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) défini pour 8 bits par pixel avec 8 bits représentant l'intensité en niveaux de gris dans l'intervalle 0-255. |
| [Grayscale16](#Grayscale16) | Défini pour 16 bits par pixel avec jusqu'à 16 bits représentant l'intensité en niveaux de gris. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRgb32Bpp()](#getRgb32Bpp--) | Obtient le `PixelDataFormat` défini pour 32 bits par pixel avec 8 bits pour chacun des canaux alpha, rouge, vert et bleu. |
| [getCmyk()](#getCmyk--) | Obtient le `PixelDataFormat` défini pour 32 bits par pixel avec 8 bits pour chacun des canaux cyan, magenta, jaune et noir. |
| [getCmyka()](#getCmyka--) | Obtient le acmyk. |
| [getRgb24Bpp()](#getRgb24Bpp--) | Obtient le `PixelDataFormat` défini pour 24 bits par pixel avec 8 bits pour chacun des canaux alpha, rouge, vert et bleu, l'alpha n'est pas défini. |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | Obtient le `PixelDataFormat` défini pour 16 bits par pixel avec 5 bits pour chacun des canaux rouge, vert et bleu, l'alpha n'est pas défini. |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | Obtient le `PixelDataFormat` défini pour 16 bits par pixel avec 5 bits pour le rouge, 6 bits pour le vert et 5 bits pour le bleu, l'alpha n'est pas défini. |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | Obtient le `PixelDataFormat` défini pour un format indexé de 8 bits par couleur. |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | Obtient le `PixelDataFormat` défini pour un format indexé de 4 bits par couleur. |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | Obtient le `PixelDataFormat` défini pour un format indexé de 2 bits par couleur. |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | Obtient le `PixelDataFormat` défini pour un format indexé de 1 bit par couleur. |
| [getYCbCr()](#getYCbCr--) | Obtient le `PixelDataFormat` défini pour 24 bits par pixel avec 8 bits pour chacun des composants chroma luma, différence bleue et différence rouge. |
| [getYcck()](#getYcck--) | Obtient le `PixelDataFormat` défini pour 32 bits par pixel avec 8 bits pour chacun des composants chroma luma, différence bleue, différence rouge et noir. |
| [getRgba32Bpp()](#getRgba32Bpp--) | Obtient le `PixelDataFormat` défini pour 32 bits par pixel avec 8 bits pour chacun des canaux alpha, rouge, vert et bleu. |
| [getRgb24BppPng()](#getRgb24BppPng--) | Obtient le `PixelDataFormat` défini pour 24 bits par pixel avec 8 bits pour chacun des canaux alpha, rouge, vert et bleu, l'alpha n'est pas défini. |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | Obtient le `PixelDataFormat` défini pour 16 bits par pixel avec 8 bits représentant l'intensité en niveaux de gris dans l'intervalle 0-255 et un composant alpha supplémentaire de 8 bits. |
| [getPixelFormat()](#getPixelFormat--) | Obtient le format pixel. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient les bits par pixel. |
| [getChannelsCount()](#getChannelsCount--) | Obtient le nombre de canaux. |
| [getChannelBits()](#getChannelBits--) | Obtient le nombre de bits pour chaque canal. |
| [getCaption()](#getCaption--) | Obtient la légende du format de données de pixel. |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | Obtient la couleur en niveaux de gris avec un nombre spécifié de bits par échantillon. |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | Obtient la couleur GrayscaleAlpha avec un nombre spécifié de bits par échantillon. |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | Obtient la couleur GrayscaleAlpha avec un nombre spécifié de bits par échantillon. |
| [getRgb(int bitsPerSample)](#getRgb-int-) | Obtient la couleur RGB avec un nombre spécifié de bits par échantillon. |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | Obtient la couleur RGB avec un nombre spécifié de bits par échantillon. |
| [getRgba(int bitsPerSample)](#getRgba-int-) | Obtient la couleur RGBA avec un nombre spécifié de bits par échantillon. |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | Obtient la couleur RGBA avec un nombre spécifié de bits par échantillon. |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | Obtient la couleur indexée BGRA avec un nombre spécifié de bits par échantillon. |
| [getBgra(int bitsPerSample)](#getBgra-int-) | Obtient la couleur BGRA avec un nombre spécifié de bits par échantillon. |
| [getBgr(int bitsPerSample)](#getBgr-int-) | Obtient la couleur BGR avec un nombre spécifié de bits par échantillon. |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | Obtient la couleur YCbCr avec un nombre spécifié de bits par échantillon. |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | Obtient la couleur YCbCr avec un nombre spécifié de bits par échantillon. |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | Obtient la couleur CMYK avec un nombre spécifié de bits par échantillon. |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | Obtient la couleur CMYK avec un nombre spécifié de bits par échantillon. |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | Obtient la couleur CMYKA avec un nombre spécifié de bits par échantillon. |
| [getYcck(int bitsPerSample)](#getYcck-int-) | Obtient la couleur YCCK avec un nombre spécifié de bits par échantillon. |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | Obtient la couleur CIE Lab avec un nombre spécifié de bits par échantillon. |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Renvoie le résultat de non-égalité pour deux classes `PixelDataFormat`. |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-) | Renvoie le résultat d'égalité pour deux classes `PixelDataFormat`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'`System.Object` spécifié est égal à cette instance. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
| [toString()](#toString--) | Renvoie une `System.String` qui représente cette instance. |
### Grayscale {#Grayscale}
```
public static final PixelDataFormat Grayscale
```


Obtient le [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) défini pour 8 bits par pixel avec 8 bits représentant l'intensité en niveaux de gris dans l'intervalle 0-255.

Valeur : le [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) défini pour 8 bits par pixel avec 8 bits représentant l'intensité en niveaux de gris dans l'intervalle 0-255.

### Grayscale16 {#Grayscale16}
```
public static final PixelDataFormat Grayscale16
```


Défini pour 16 bits par pixel avec jusqu'à 16 bits représentant l'intensité en niveaux de gris.

### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


Obtient le `PixelDataFormat` défini pour 32 bits par pixel avec 8 bits pour chacun des canaux alpha, rouge, vert et bleu.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getCmyk() {#getCmyk--}
```
public static PixelDataFormat getCmyk()
```


Obtient le `PixelDataFormat` défini pour 32 bits par pixel avec 8 bits pour chacun des canaux cyan, magenta, jaune et noir.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


Obtient le acmyk.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


Obtient le `PixelDataFormat` défini pour 24 bits par pixel avec 8 bits pour chacun des canaux alpha, rouge, vert et bleu, l'alpha n'est pas défini.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


Obtient le `PixelDataFormat` défini pour 16 bits par pixel avec 5 bits pour chacun des canaux rouge, vert et bleu, l'alpha n'est pas défini.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


Obtient le `PixelDataFormat` défini pour 16 bits par pixel avec 5 bits pour le rouge, 6 bits pour le vert et 5 bits pour le bleu, l'alpha n'est pas défini.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


Obtient le `PixelDataFormat` défini pour un format indexé de 8 bits par couleur. Le stockage de données de pixel indexées est destiné à permettre le stockage et la récupération des données partout où la palette de couleurs est utilisée. Utilisez avec précaution, car cela peut nécessiter une conversion d'une palette à une autre ou de RGBA vers un modèle de couleur indexé.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 8 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


Obtient le `PixelDataFormat` défini pour un format indexé de 4 bits par couleur. Le stockage de données de pixel indexées est destiné à permettre le stockage et la récupération des données partout où la palette de couleurs est utilisée. Utilisez avec précaution, car cela peut nécessiter une conversion d'une palette à une autre ou de RGBA vers un modèle de couleur indexé.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 4 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


Obtient le `PixelDataFormat` défini pour un format indexé de 2 bits par couleur. Le stockage de données de pixel indexées est destiné à permettre le stockage et la récupération des données partout où la palette de couleurs est utilisée. Utilisez avec précaution, car cela peut nécessiter une conversion d'une palette à une autre ou de RGBA vers un modèle de couleur indexé.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 2 bit per color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


Obtient le `PixelDataFormat` défini pour un format indexé de 1 bit par couleur. Le stockage de données de pixel indexées est destiné à permettre le stockage et la récupération des données partout où la palette de couleurs est utilisée. Utilisez avec précaution, car cela peut nécessiter une conversion d'une palette à une autre ou de RGBA vers un modèle de couleur indexé.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for indexed 1 bit per color.
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


Obtient le `PixelDataFormat` défini pour 24 bits par pixel avec 8 bits pour chacun des composants chroma luma, différence bleue et différence rouge.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


Obtient le `PixelDataFormat` défini pour 32 bits par pixel avec 8 bits pour chacun des composants chroma luma, différence bleue, différence rouge et noir.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


Obtient le `PixelDataFormat` défini pour 32 bits par pixel avec 8 bits pour chacun des canaux alpha, rouge, vert et bleu.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


Obtient le `PixelDataFormat` défini pour 24 bits par pixel avec 8 bits pour chacun des canaux alpha, rouge, vert et bleu, l'alpha n'est pas défini.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


Obtient le `PixelDataFormat` défini pour 16 bits par pixel avec 8 bits représentant l'intensité en niveaux de gris dans l'intervalle 0-255 et un composant alpha supplémentaire de 8 bits.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The `PixelDataFormat` defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


Obtient le format pixel.

**Returns:**
int - Le format de pixel.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtient les bits par pixel.

**Returns:**
int - Le nombre de bits par pixel.
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


Obtient le nombre de canaux.

**Returns:**
int - Le nombre de canaux.
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


Obtient le nombre de bits pour chaque canal.

**Returns:**
int[] - Les bits du canal.
### getCaption() {#getCaption--}
```
public String getCaption()
```


Obtient la légende du format de données de pixel.

**Returns:**
java.lang.String
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


Obtient la couleur en niveaux de gris avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


Obtient la couleur GrayscaleAlpha avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


Obtient la couleur GrayscaleAlpha avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |
| alphaChannelBits | int | Le nombre de bits par échantillon dans le canal alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The GrayscaleAlpha color.
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


Obtient la couleur RGB avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


Obtient la couleur RGB avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerRedChannel | int | Le nombre de bits par canal Rouge. |
| bitsPerGreenChannel | int | Le nombre de bits par canal Vert. |
| bitsPerBlueChannel | int | Le nombre de bits par canal Bleu. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGB color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


Obtient la couleur RGBA avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


Obtient la couleur RGBA avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerRedChannel | int | Le nombre de bits par canal Rouge. |
| bitsPerGreenChannel | int | Le nombre de bits par canal Vert. |
| bitsPerBlueChannel | int | Le nombre de bits par canal Bleu. |
| bitsPerAlphaChannel | int | Le nombre de bits par canal Alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The RGBA color.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


Obtient la couleur indexée BGRA avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


Obtient la couleur BGRA avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGRA color.
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


Obtient la couleur BGR avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The BGR color.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


Obtient la couleur YCbCr avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


Obtient la couleur YCbCr avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerY | int | Le nombre de bits par canal Y. |
| bitsPerCb | int | Le nombre de bits par canal Cb. |
| bitsPerCr | int | Le nombre de bits par canal Cr. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCbCr color.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


Obtient la couleur CMYK avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


Obtient la couleur CMYK avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerCyanChannel | int | Le nombre de bits par canal Cyan. |
| bitsPerMagentaChannel | int | Le nombre de bits par canal Magenta. |
| bitsPerYellowChannel | int | Le nombre de bits par canal Jaune. |
| bitsPerKeyChannel | int | Le nombre de bits par canal Key. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


Obtient la couleur CMYKA avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerCyanChannel | int | Le nombre de bits par canal Cyan. |
| bitsPerMagentaChannel | int | Le nombre de bits par canal Magenta. |
| bitsPerYellowChannel | int | Le nombre de bits par canal Jaune. |
| bitsPerKeyChannel | int | Le nombre de bits par canal Key. |
| bitsPerAlphaChannel | int | Le nombre de bits par canal Alpha. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CMYK color.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


Obtient la couleur YCCK avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerSample | int | Le nombre de bits par échantillon. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The YCCK color.
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


Obtient la couleur CIE Lab avec un nombre spécifié de bits par échantillon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bitsPerL | int | Le nombre de bits par canal L. |
| bitsPerA | int | Le nombre de bits par canal A. |
| bitsPerB | int | Le nombre de bits par canal B. |

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The CIE Lab color.
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Renvoie le résultat de non-égalité pour deux classes `PixelDataFormat`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Le premier `PixelDataFormat` à comparer. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Le deuxième `PixelDataFormat` à comparer. |

**Returns:**
boolean - Vrai si `pixelFormat1` et `pixelFormat2` contiennent des données non égales ou si l'un des paramètres est nul.
### op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Equality-com.aspose.imaging.PixelDataFormat-com.aspose.imaging.PixelDataFormat-}
```
public static boolean op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


Renvoie le résultat d'égalité pour deux classes `PixelDataFormat`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Le premier `PixelDataFormat` à comparer. |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.imaging/pixeldataformat) | Le deuxième `PixelDataFormat` à comparer. |

**Returns:**
boolean - Vrai si `pixelFormat1` et `pixelFormat2` contiennent des données égales ou si les deux paramètres sont nuls.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si l'`System.Object` spécifié est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Le `System.Object` à comparer avec cette instance. |

**Returns:**
boolean - `true` si le `System.Object` spécifié est égal à cette instance; sinon, `false`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance.

**Returns:**
int - Un code de hachage pour cette instance, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.
### toString() {#toString--}
```
public String toString()
```


Renvoie une `System.String` qui représente cette instance.

**Returns:**
java.lang.String - Une `System.String` qui représente cette instance.
