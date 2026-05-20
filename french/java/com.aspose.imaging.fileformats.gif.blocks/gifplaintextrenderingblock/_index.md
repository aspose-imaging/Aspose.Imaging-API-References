---
title: "GifPlainTextRenderingBlock"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Bloc d'extension de texte brut Gif."
type: docs
weight: 14
url: /fr/java/com.aspose.imaging.fileformats.gif.blocks/gifplaintextrenderingblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifPlainTextRenderingBlock extends GifBlock
```

Bloc d'extension de texte brut Gif. L'extension de texte brut contient des données textuelles et les paramètres nécessaires pour rendre ces données sous forme graphique, de manière simple.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GifPlainTextRenderingBlock()](#GifPlainTextRenderingBlock--) | Initialise une nouvelle instance de la classe `GifPlainTextRenderingBlock`. |
| [GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)](#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---) | Initialise une nouvelle instance de la classe `GifPlainTextRenderingBlock`. |
## Champs

| Champ | Description |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Le libellé de l'extension de texte brut. |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | La taille du sous-bloc. |
| [BLOCK_SIZE](#BLOCK-SIZE) | La taille globale du bloc. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTextForegroundColorIndex()](#getTextForegroundColorIndex--) | Obtient ou définit l'index de la couleur dans la palette de couleurs globale utilisée pour dessiner le premier plan du texte. |
| [setTextForegroundColorIndex(byte value)](#setTextForegroundColorIndex-byte-) | Obtient ou définit l'index de la couleur dans la palette de couleurs globale utilisée pour dessiner le premier plan du texte. |
| [getTextBackgroundColorIndex()](#getTextBackgroundColorIndex--) | Obtient ou définit l'index de la couleur dans la palette de couleurs globale utilisée pour dessiner l'arrière-plan du texte. |
| [setTextBackgroundColorIndex(byte value)](#setTextBackgroundColorIndex-byte-) | Obtient ou définit l'index de la couleur dans la palette de couleurs globale utilisée pour dessiner l'arrière-plan du texte. |
| [getCharacterCellWidth()](#getCharacterCellWidth--) | Obtient ou définit la largeur de la cellule de caractère, en pixels, de chaque cellule de la grille. |
| [setCharacterCellWidth(byte value)](#setCharacterCellWidth-byte-) | Obtient ou définit la largeur de la cellule de caractère, en pixels, de chaque cellule de la grille. |
| [getCharacterCellHeight()](#getCharacterCellHeight--) | Obtient ou définit la hauteur de la cellule de caractère, en pixels, de chaque cellule de la grille. |
| [setCharacterCellHeight(byte value)](#setCharacterCellHeight-byte-) | Obtient ou définit la hauteur de la cellule de caractère, en pixels, de chaque cellule de la grille. |
| [getTextGridLeftPosition()](#getTextGridLeftPosition--) | Obtient ou définit la position gauche de la grille de texte. |
| [setTextGridLeftPosition(int value)](#setTextGridLeftPosition-int-) | Obtient ou définit la position gauche de la grille de texte. |
| [getTextGridTopPosition()](#getTextGridTopPosition--) | Obtient ou définit la position supérieure de la grille de texte. |
| [setTextGridTopPosition(int value)](#setTextGridTopPosition-int-) | Obtient ou définit la position supérieure de la grille de texte. |
| [getTextGridWidth()](#getTextGridWidth--) | Obtient ou définit la largeur de la grille de texte en pixels |
| [setTextGridWidth(int value)](#setTextGridWidth-int-) | Obtient ou définit la largeur de la grille de texte en pixels |
| [getTextGridHeight()](#getTextGridHeight--) | Obtient ou définit la hauteur de la grille de texte en pixels |
| [setTextGridHeight(int value)](#setTextGridHeight-int-) | Obtient ou définit la hauteur de la grille de texte en pixels |
| [getPlainTextData()](#getPlainTextData--) | Obtient ou définit les données de texte brut. |
| [setPlainTextData(byte[] value)](#setPlainTextData-byte---) | Obtient ou définit les données de texte brut. |
### GifPlainTextRenderingBlock() {#GifPlainTextRenderingBlock--}
```
public GifPlainTextRenderingBlock()
```


Initialise une nouvelle instance de la classe `GifPlainTextRenderingBlock`.

### GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data) {#GifPlainTextRenderingBlock-int-int-int-int-byte-byte-byte-byte-byte---}
```
public GifPlainTextRenderingBlock(int textGridLeftPosition, int textGridTopPosition, int textGridWidth, int textGridHeight, byte characterCellWidth, byte characterCellHeight, byte textForegroundColorIndex, byte textBackgroundColorIndex, byte[] data)
```


Initialise une nouvelle instance de la classe `GifPlainTextRenderingBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| textGridLeftPosition | int | La position gauche de la grille de texte. |
| textGridTopPosition | int | La position supérieure de la grille de texte. |
| textGridWidth | int | La largeur de la grille de texte. |
| textGridHeight | int | La hauteur de la grille de texte. |
| characterCellWidth | byte | La largeur de la cellule de caractère. |
| characterCellHeight | byte | La hauteur de la cellule de caractère. |
| textForegroundColorIndex | byte | L'index de la couleur de premier plan. |
| textBackgroundColorIndex | byte | L'index de couleur d'arrière-plan. |
| données | byte[] | Les données de texte brut. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Le libellé de l'extension de texte brut.

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


La taille du sous-bloc.

### BLOCK_SIZE {#BLOCK-SIZE}
```
public static final byte BLOCK_SIZE
```


La taille globale du bloc.

### getTextForegroundColorIndex() {#getTextForegroundColorIndex--}
```
public byte getTextForegroundColorIndex()
```


Obtient ou définit l'index de la couleur dans la palette de couleurs globale utilisée pour dessiner le premier plan du texte.

Valeur : l'index de couleur de premier plan.

**Returns:**
byte
### setTextForegroundColorIndex(byte value) {#setTextForegroundColorIndex-byte-}
```
public void setTextForegroundColorIndex(byte value)
```


Obtient ou définit l'index de la couleur dans la palette de couleurs globale utilisée pour dessiner le premier plan du texte.

Valeur : l'index de couleur de premier plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getTextBackgroundColorIndex() {#getTextBackgroundColorIndex--}
```
public byte getTextBackgroundColorIndex()
```


Obtient ou définit l'index de la couleur dans la palette de couleurs globale utilisée pour dessiner l'arrière-plan du texte.

Valeur : l'index de couleur d'arrière-plan.

**Returns:**
byte
### setTextBackgroundColorIndex(byte value) {#setTextBackgroundColorIndex-byte-}
```
public void setTextBackgroundColorIndex(byte value)
```


Obtient ou définit l'index de la couleur dans la palette de couleurs globale utilisée pour dessiner l'arrière-plan du texte.

Valeur : l'index de couleur d'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCharacterCellWidth() {#getCharacterCellWidth--}
```
public byte getCharacterCellWidth()
```


Obtient ou définit la largeur de la cellule de caractère, en pixels, de chaque cellule de la grille.

Valeur : la largeur de la cellule de caractère.

**Returns:**
byte
### setCharacterCellWidth(byte value) {#setCharacterCellWidth-byte-}
```
public void setCharacterCellWidth(byte value)
```


Obtient ou définit la largeur de la cellule de caractère, en pixels, de chaque cellule de la grille.

Valeur : la largeur de la cellule de caractère.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCharacterCellHeight() {#getCharacterCellHeight--}
```
public byte getCharacterCellHeight()
```


Obtient ou définit la hauteur de la cellule de caractère, en pixels, de chaque cellule de la grille.

Valeur : la hauteur de la cellule de caractère.

**Returns:**
byte
### setCharacterCellHeight(byte value) {#setCharacterCellHeight-byte-}
```
public void setCharacterCellHeight(byte value)
```


Obtient ou définit la hauteur de la cellule de caractère, en pixels, de chaque cellule de la grille.

Valeur : la hauteur de la cellule de caractère.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getTextGridLeftPosition() {#getTextGridLeftPosition--}
```
public int getTextGridLeftPosition()
```


Obtient ou définit la position gauche de la grille de texte.

Valeur : la position gauche de la grille de texte.

Il s'agit d'un numéro de colonne, en pixels, du bord gauche de la grille de texte, par rapport au bord gauche de l'écran logique.

**Returns:**
int
### setTextGridLeftPosition(int value) {#setTextGridLeftPosition-int-}
```
public void setTextGridLeftPosition(int value)
```


Obtient ou définit la position gauche de la grille de texte.

Valeur : la position gauche de la grille de texte.

Il s'agit d'un numéro de colonne, en pixels, du bord gauche de la grille de texte, par rapport au bord gauche de l'écran logique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTextGridTopPosition() {#getTextGridTopPosition--}
```
public int getTextGridTopPosition()
```


Obtient ou définit la position supérieure de la grille de texte.

Valeur : la position supérieure de la grille de texte.

Il s'agit d'un numéro de ligne, en pixels, du bord supérieur de la grille de texte, par rapport au bord supérieur de l'écran logique.

**Returns:**
int
### setTextGridTopPosition(int value) {#setTextGridTopPosition-int-}
```
public void setTextGridTopPosition(int value)
```


Obtient ou définit la position supérieure de la grille de texte.

Valeur : la position supérieure de la grille de texte.

Il s'agit d'un numéro de ligne, en pixels, du bord supérieur de la grille de texte, par rapport au bord supérieur de l'écran logique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTextGridWidth() {#getTextGridWidth--}
```
public int getTextGridWidth()
```


Obtient ou définit la largeur de la grille de texte en pixels

Valeur : la largeur de la grille de texte en pixels.

**Returns:**
int
### setTextGridWidth(int value) {#setTextGridWidth-int-}
```
public void setTextGridWidth(int value)
```


Obtient ou définit la largeur de la grille de texte en pixels

Valeur : la largeur de la grille de texte en pixels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTextGridHeight() {#getTextGridHeight--}
```
public int getTextGridHeight()
```


Obtient ou définit la hauteur de la grille de texte en pixels

Valeur : la hauteur de la grille de texte en pixels.

**Returns:**
int
### setTextGridHeight(int value) {#setTextGridHeight-int-}
```
public void setTextGridHeight(int value)
```


Obtient ou définit la hauteur de la grille de texte en pixels

Valeur : la hauteur de la grille de texte en pixels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getPlainTextData() {#getPlainTextData--}
```
public byte[] getPlainTextData()
```


Obtient ou définit les données de texte brut.

Valeur : les données de texte brut.

**Returns:**
byte[]
### setPlainTextData(byte[] value) {#setPlainTextData-byte---}
```
public void setPlainTextData(byte[] value)
```


Obtient ou définit les données de texte brut.

Valeur : les données de texte brut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

