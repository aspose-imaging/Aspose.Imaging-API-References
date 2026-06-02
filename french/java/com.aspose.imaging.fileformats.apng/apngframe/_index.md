---
title: "ApngFrame"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Créez des images‑cadres PNG animés APNG à partir d'images raster à page unique avec notre API."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.apng/apngframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class ApngFrame extends RasterCachedImage implements IAnimationFrame
```

Créez des images‑cadres PNG animés (APNG) à partir d'images raster à page unique avec notre API. Définissez sans effort l'animation et la durée des cadres, programmez le nombre de cadres et ajustez les niveaux de gamma et de contraste, garantissant des animations captivantes et personnalisables adaptées à votre vision.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient le nombre de bits par pixel de l'image. |
| [getWidth()](#getWidth--) | Obtient la largeur de l'image. |
| [getHeight()](#getHeight--) | Obtient la hauteur de l'image. |
| [getFrameTime()](#getFrameTime--) | Obtient la durée de la trame. |
| [setFrameTime(int value)](#setFrameTime-int-) | Définit la durée du cadre. |
| [getFrameTop()](#getFrameTop--) | Obtient le décalage supérieur de la trame. |
| [getFrameLeft()](#getFrameLeft--) | Obtient le décalage gauche de la trame. |
| [getDisposalMethod()](#getDisposalMethod--) | Obtient la méthode de disposition. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtient une valeur indiquant si l'image possède une couleur transparente. |
| [hasAlpha()](#hasAlpha--) | Obtient une valeur indiquant si cette instance possède un canal alpha. |
| [getTransparentColor()](#getTransparentColor--) | Obtient la couleur transparente. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Une valeur indiquant si l'image possède une couleur transparente. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | La couleur transparente. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Obtient une valeur indiquant si elle possède une couleur d'arrière‑plan. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtient la couleur d'arrière-plan. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Une valeur indiquant si elle possède une couleur d'arrière‑plan. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | La couleur d'arrière-plan. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Obtient une valeur indiquant si [utiliser le mélange alpha]. |
| [getFullFrame()](#getFullFrame--) | Obtient la trame complète. |
| [cacheData()](#cacheData--) | Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué depuis le `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtient le nombre de bits par pixel de l'image.

**Returns:**
int - le nombre de bits par pixel de l'image.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient la largeur de l'image.

**Returns:**
int - la largeur de l'image.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient la hauteur de l'image.

**Returns:**
int - la hauteur de l'image.
### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


Obtient la durée de la trame.

**Returns:**
int - la durée de la trame.
### setFrameTime(int value) {#setFrameTime-int-}
```
public final void setFrameTime(int value)
```


Définit la durée du cadre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | la durée du cadre. |

### getFrameTop() {#getFrameTop--}
```
public final int getFrameTop()
```


Obtient le décalage supérieur de la trame.

**Returns:**
int - le décalage supérieur de la trame.
### getFrameLeft() {#getFrameLeft--}
```
public final int getFrameLeft()
```


Obtient le décalage gauche de la trame.

**Returns:**
int - le décalage gauche de la trame.
### getDisposalMethod() {#getDisposalMethod--}
```
public final int getDisposalMethod()
```


Obtient la méthode de disposition.

**Returns:**
int - la méthode de disposition.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Obtient une valeur indiquant si l'image possède une couleur transparente.

**Returns:**
booléen - une valeur indiquant si l'image possède une couleur transparente.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Obtient une valeur indiquant si cette instance possède un canal alpha.

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Obtient la couleur transparente.

**Returns:**
[Color](../../com.aspose.imaging/color) - the transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Une valeur indiquant si l'image possède une couleur transparente.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si l'image possède une couleur transparente. |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


La couleur transparente.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | la couleur transparente. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Obtient une valeur indiquant si elle possède une couleur d'arrière‑plan.

**Returns:**
booléen - une valeur indiquant s'il possède une couleur d'arrière-plan.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtient la couleur d'arrière-plan.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Une valeur indiquant si elle possède une couleur d'arrière‑plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant s'il possède une couleur d'arrière-plan. |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


La couleur d'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | la couleur d'arrière-plan. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


Obtient une valeur indiquant si [utiliser le mélange alpha].

Valeur : `true` si [use alpha blending] ; sinon, `false`.

**Returns:**
boolean - une valeur indiquant si [use alpha blending].
### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


Obtient la trame complète.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué depuis le `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)).

