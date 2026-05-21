---
title: "GifFrameBlock"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Bloc de trame Gif."
type: docs
weight: 12
url: /fr/java/com.aspose.imaging.fileformats.gif.blocks/gifframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifFrameBlock extends RasterCachedImage implements IGifBlock, IAnimationFrame, IInterlaced
```

Bloc de trame Gif.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GifFrameBlock(int width, int height)](#GifFrameBlock-int-int-) | Initialise une nouvelle instance de la classe `GifFrameBlock`. |
| [GifFrameBlock(int left, int top, int width, int height)](#GifFrameBlock-int-int-int-int-) | Initialise une nouvelle instance de la classe `GifFrameBlock`. |
| [GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)](#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-) | Initialise une nouvelle instance de la classe `GifFrameBlock`. |
| [GifFrameBlock(RasterImage image)](#GifFrameBlock-com.aspose.imaging.RasterImage-) | Initialise une nouvelle instance de la classe `GifFrameBlock`. |
| [GifFrameBlock(RasterImage image, int left, int top)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-) | Initialise une nouvelle instance de la classe `GifFrameBlock`. |
| [GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-) | Initialise une nouvelle instance de la classe `GifFrameBlock`. |
| [GifFrameBlock(InputStream stream)](#GifFrameBlock-java.io.InputStream-) | Initialise une nouvelle instance de la classe `GifFrameBlock`. |
| [GifFrameBlock(System.IO.Stream stream)](#GifFrameBlock-com.aspose.ms.System.IO.Stream-) |  |
| [GifFrameBlock(InputStream stream, int left, int top)](#GifFrameBlock-java.io.InputStream-int-int-) | Initialise une nouvelle instance de la classe `GifFrameBlock`. |
| [GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-) | Initialise une nouvelle instance de la classe `GifFrameBlock`. |
| [GifFrameBlock(String path)](#GifFrameBlock-java.lang.String-) | Initialise une nouvelle instance de la classe `GifFrameBlock`. |
| [GifFrameBlock(String path, int left, int top)](#GifFrameBlock-java.lang.String-int-int-) | Initialise une nouvelle instance de la classe `GifFrameBlock`. |
| [GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-) | Initialise une nouvelle instance de la classe `GifFrameBlock`. |
## Champs

| Champ | Description |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Étiquette d'extension de bloc. |
| [IMAGE_DESCRIPTOR_SIZE](#IMAGE-DESCRIPTOR-SIZE) | La taille du descripteur d'image. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)](#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-) | Obtient la palette de couleurs associée. |
| [createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)](#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-) | Crée les indicateurs. |
| [getFileFormat()](#getFileFormat--) | Obtient une valeur du format de fichier |
| [getWidth()](#getWidth--) | Obtient la largeur de l'image. |
| [getHeight()](#getHeight--) | Obtient la hauteur de l'image. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient le nombre de bits par pixel de l'image. |
| [getFrameTime()](#getFrameTime--) | Obtient la durée. |
| [setFrameTime(int value)](#setFrameTime-int-) | Définit la durée. |
| [getInterlaced()](#getInterlaced--) | Obtient ou définit une valeur indiquant si ce `GifFrameBlock` est entrelacé. |
| [isInterlaced()](#isInterlaced--) | Obtient une valeur indiquant si cette instance d'image est entrelacée. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Obtient ou définit une valeur indiquant si ce `GifFrameBlock` est entrelacé. |
| [isPaletteSorted()](#isPaletteSorted--) | Obtient ou définit une valeur indiquant si la palette de couleurs est triée. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Obtient ou définit une valeur indiquant si la palette de couleurs est triée. |
| [getGifFrameBitsPerPixel()](#getGifFrameBitsPerPixel--) | Obtient ou définit les bits par pixel de la trame GIF. |
| [setGifFrameBitsPerPixel(byte value)](#setGifFrameBitsPerPixel-byte-) | Obtient ou définit les bits par pixel de la trame GIF. |
| [getLeft()](#getLeft--) | Obtient ou définit la position gauche de l'image. |
| [setLeft(int value)](#setLeft-int-) | Obtient ou définit la position gauche de l'image. |
| [getTop()](#getTop--) | Obtient ou définit la position supérieure de l'image. |
| [setTop(int value)](#setTop-int-) | Obtient ou définit la position supérieure de l'image. |
| [getFrameTop()](#getFrameTop--) | Convertit en p. |
| [getFrameLeft()](#getFrameLeft--) | Obtient la gauche. |
| [getDisposalMethod()](#getDisposalMethod--) | Obtient la méthode de disposition. |
| [getFlags()](#getFlags--) | Obtient ou définit les indicateurs. |
| [setFlags(byte value)](#setFlags-byte-) | Obtient ou définit les indicateurs. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Obtient une valeur indiquant si [utiliser le mélange alpha]. |
| [getControlBlock()](#getControlBlock--) | Obtient le bloc de contrôle graphique associé à ce bloc. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtient une valeur indiquant si le bloc de trame possède une couleur transparente. |
| [getTransparentColor()](#getTransparentColor--) | Obtient la couleur transparente du bloc de trame. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Obtient une valeur indiquant si le bloc de trame possède une couleur transparente. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Obtient la couleur transparente du bloc de trame. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtient une valeur pour la couleur d'arrière-plan. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Définit une valeur pour la couleur d'arrière-plan. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtient les options basées sur les paramètres du fichier original. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Ajustement de la luminosité d'une image. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. |
| [getFullFrame()](#getFullFrame--) | Obtient la trame complète. |
| [resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensionne cette instance de [RasterCachedImage](../../com.aspose.imaging/rastercachedimage). |
### GifFrameBlock(int width, int height) {#GifFrameBlock-int-int-}
```
public GifFrameBlock(int width, int height)
```


Initialise une nouvelle instance de la classe `GifFrameBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur de l'image. |
| height | int | La hauteur de l'image. |

### GifFrameBlock(int left, int top, int width, int height) {#GifFrameBlock-int-int-int-int-}
```
public GifFrameBlock(int left, int top, int width, int height)
```


Initialise une nouvelle instance de la classe `GifFrameBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gauche | int | La position gauche de l'image. |
| haut | int | La position supérieure de l'image. |
| width | int | La largeur de l'image. |
| height | int | La hauteur de l'image. |

### GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel) {#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-}
```
public GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)
```


Initialise une nouvelle instance de la classe `GifFrameBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gauche | int | La position gauche de l'image. |
| haut | int | La position supérieure de l'image. |
| width | int | La largeur de l'image. |
| height | int | La hauteur de l'image. |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette de couleurs. |
| isPaletteSorted | boolean | si défini sur `true`, la palette de couleurs est triée. |
| isGifFrameInterlaced | boolean | si défini sur `true`, la trame GIF est entrelacée. |
| bitsPerPixel | byte | Les bits par pixel. |

### GifFrameBlock(RasterImage image) {#GifFrameBlock-com.aspose.imaging.RasterImage-}
```
public GifFrameBlock(RasterImage image)
```


Initialise une nouvelle instance de la classe `GifFrameBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image avec laquelle initialiser les données de pixels et de palette du cadre. |

### GifFrameBlock(RasterImage image, int left, int top) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-}
```
public GifFrameBlock(RasterImage image, int left, int top)
```


Initialise une nouvelle instance de la classe `GifFrameBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image avec laquelle initialiser les données de pixels et de palette du cadre. |
| gauche | int | La position gauche de l'image. |
| haut | int | La position supérieure de l'image. |

### GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Initialise une nouvelle instance de la classe `GifFrameBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | L'image avec laquelle initialiser les données de pixels et de palette du cadre. |
| gauche | int | La position gauche de l'image. |
| haut | int | La position supérieure de l'image. |
| isPaletteSorted | boolean | si défini sur `true`, la palette de couleurs est triée. |
| isGifFrameInterlaced | boolean | si défini sur `true`, la trame GIF est entrelacée. |
| lzwCodeSize | byte | Les bits par pixel. |

### GifFrameBlock(InputStream stream) {#GifFrameBlock-java.io.InputStream-}
```
public GifFrameBlock(InputStream stream)
```


Initialise une nouvelle instance de la classe `GifFrameBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux à partir duquel charger une image et avec lequel initialiser les données de pixels et de palette du cadre. |

### GifFrameBlock(System.IO.Stream stream) {#GifFrameBlock-com.aspose.ms.System.IO.Stream-}
```
public GifFrameBlock(System.IO.Stream stream)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | com.aspose.ms.System.IO.Stream |  |

### GifFrameBlock(InputStream stream, int left, int top) {#GifFrameBlock-java.io.InputStream-int-int-}
```
public GifFrameBlock(InputStream stream, int left, int top)
```


Initialise une nouvelle instance de la classe `GifFrameBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux à partir duquel charger une image et avec lequel initialiser les données de pixels et de palette du cadre. |
| gauche | int | La position gauche de l'image. |
| haut | int | La position supérieure de l'image. |

### GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Initialise une nouvelle instance de la classe `GifFrameBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Le flux à partir duquel charger une image et avec lequel initialiser les données de pixels et de palette du cadre. |
| gauche | int | La position gauche de l'image. |
| haut | int | La position supérieure de l'image. |
| isPaletteSorted | boolean | si défini sur `true`, la palette de couleurs est triée. |
| isGifFrameInterlaced | boolean | si défini sur `true`, la trame GIF est entrelacée. |
| lzwCodeSize | byte | Les bits par pixel. |

### GifFrameBlock(String path) {#GifFrameBlock-java.lang.String-}
```
public GifFrameBlock(String path)
```


Initialise une nouvelle instance de la classe `GifFrameBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Le chemin à partir duquel charger une image et avec lequel initialiser les données de pixels et de palette du cadre. |

### GifFrameBlock(String path, int left, int top) {#GifFrameBlock-java.lang.String-int-int-}
```
public GifFrameBlock(String path, int left, int top)
```


Initialise une nouvelle instance de la classe `GifFrameBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Le chemin à partir duquel charger une image et avec lequel initialiser les données de pixels et de palette du cadre. |
| gauche | int | La position gauche de l'image. |
| haut | int | La position supérieure de l'image. |

### GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Initialise une nouvelle instance de la classe `GifFrameBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Le chemin à partir duquel charger une image et avec lequel initialiser les données de pixels et de palette du cadre. |
| gauche | int | La position gauche de l'image. |
| haut | int | La position supérieure de l'image. |
| isPaletteSorted | boolean | si défini sur `true`, la palette de couleurs est triée. |
| isGifFrameInterlaced | boolean | si défini sur `true`, la trame GIF est entrelacée. |
| lzwCodeSize | byte | Les bits par pixel. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final int EXTENSION_LABEL
```


Étiquette d'extension de bloc.

### IMAGE_DESCRIPTOR_SIZE {#IMAGE-DESCRIPTOR-SIZE}
```
public static final int IMAGE_DESCRIPTOR_SIZE
```


La taille du descripteur d'image.

### getColorPalette(IColorPalette framePalette, IColorPalette containerPalette) {#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-}
```
public static IColorPalette getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)
```


Obtient la palette de couleurs associée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| framePalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette de trame. |
| containerPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette du conteneur. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced) {#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-}
```
public static byte createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)
```


Crée les indicateurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La palette de couleurs. |
| isPaletteSorted | boolean | si défini sur `true`, les couleurs de la palette sont triées. |
| isGifFrameInterlaced | boolean | si défini sur `true`, l'image de la trame GIF est entrelacée. |

**Returns:**
byte - Les indicateurs créés.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtient une valeur du format de fichier

**Returns:**
long
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient la largeur de l'image.

**Returns:**
int - La largeur de l'image.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient la hauteur de l'image.

**Returns:**
int - La hauteur de l'image.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtient le nombre de bits par pixel de l'image.

**Returns:**
int - Le nombre de bits par pixel de l'image.
### getFrameTime() {#getFrameTime--}
```
public int getFrameTime()
```


Obtient la durée.

Valeur : la durée, en millisecondes.

**Returns:**
int - la durée.
### setFrameTime(int value) {#setFrameTime-int-}
```
public void setFrameTime(int value)
```


Définit la durée.

Valeur : la durée, en millisecondes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | la durée. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Obtient ou définit une valeur indiquant si ce `GifFrameBlock` est entrelacé.

**Returns:**
boolean - `true` si entrelacé ; sinon, `false`.
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


Obtient une valeur indiquant si cette instance d'image est entrelacée.

Valeur : `true` si cette instance d'image est entrelacée ; sinon, `false`.

**Returns:**
boolean - une valeur indiquant si cette instance d'image est entrelacée.
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Obtient ou définit une valeur indiquant si ce `GifFrameBlock` est entrelacé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `true` si entrelacé ; sinon, `false`. |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Obtient ou définit une valeur indiquant si la palette de couleurs est triée.

**Returns:**
boolean - `true` si la palette de couleurs est triée ; sinon, `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Obtient ou définit une valeur indiquant si la palette de couleurs est triée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | `true` si la palette de couleurs est triée ; sinon, `false`. |

### getGifFrameBitsPerPixel() {#getGifFrameBitsPerPixel--}
```
public byte getGifFrameBitsPerPixel()
```


Obtient ou définit les bits par pixel de la trame GIF.

**Returns:**
byte - Les bits par pixel de la trame GIF.
### setGifFrameBitsPerPixel(byte value) {#setGifFrameBitsPerPixel-byte-}
```
public void setGifFrameBitsPerPixel(byte value)
```


Obtient ou définit les bits par pixel de la trame GIF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte | Les bits par pixel de la trame GIF. |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Obtient ou définit la position gauche de l'image.

**Returns:**
int - La position gauche de l'image.
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Obtient ou définit la position gauche de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La position gauche de l'image. |

### getTop() {#getTop--}
```
public int getTop()
```


Obtient ou définit la position supérieure de l'image.

**Returns:**
int - L'emplacement de l'image en haut.
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Obtient ou définit la position supérieure de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'emplacement de l'image en haut. |

### getFrameTop() {#getFrameTop--}
```
public int getFrameTop()
```


Convertit en p.

Valeur : le haut.

**Returns:**
int
### getFrameLeft() {#getFrameLeft--}
```
public int getFrameLeft()
```


Obtient la gauche.

Valeur : la gauche.

**Returns:**
int - la gauche.
### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


Obtient la méthode de disposition.

**Returns:**
int - la méthode de disposition.
### getFlags() {#getFlags--}
```
public byte getFlags()
```


Obtient ou définit les indicateurs.

**Returns:**
byte - Les indicateurs.
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


Obtient ou définit les indicateurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte | Les indicateurs. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public boolean isUseAlphaBlending()
```


Obtient une valeur indiquant si [utiliser le mélange alpha].

Valeur : `true` si [use alpha blending] ; sinon, `false`.

**Returns:**
boolean - une valeur indiquant si [use alpha blending].
### getControlBlock() {#getControlBlock--}
```
public GifGraphicsControlBlock getControlBlock()
```


Obtient le bloc de contrôle graphique associé à ce bloc.

**Returns:**
[GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) - The control block.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Obtient une valeur indiquant si le bloc de trame possède une couleur transparente.

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Obtient la couleur transparente du bloc de trame.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Obtient une valeur indiquant si le bloc de trame possède une couleur transparente.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Obtient la couleur transparente du bloc de trame.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtient une valeur pour la couleur d'arrière-plan.

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Définit une valeur pour la couleur d'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | une valeur pour la couleur d'arrière-plan. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Obtient les options basées sur les paramètres du fichier original. Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés. Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis l'enregistrons en utilisant la méthode [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) , une image PNG de sortie avec 8 bits par pixel sera produite. Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre à la méthode [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) en tant que deuxième paramètre.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Ajustement de la luminosité d'une image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightness | int | Valeur de luminosité. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| oldColorArgb | int | Ancienne valeur ARGB de couleur à remplacer. |
| oldColorDiff | byte | Différence autorisée dans l'ancienne couleur pour pouvoir élargir la teinte de couleur remplacée. |
| newColorArgb | int | Nouvelle valeur ARGB de couleur avec laquelle remplacer l'ancienne couleur. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Remplace toutes les couleurs non transparentes par la nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColorArgb | int | Nouvelle valeur ARGB de couleur avec laquelle remplacer les couleurs non transparentes. |

### getFullFrame() {#getFullFrame--}
```
public RasterImage getFullFrame()
```


Obtient la trame complète.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - he RasterImage with full frame
### resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings)
```


Redimensionne cette instance de [RasterCachedImage](../../com.aspose.imaging/rastercachedimage).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | Nouvelle largeur. |
| newHeight | int | Nouvelle hauteur. |
| imageResizeSettings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Paramètres de redimensionnement. |

