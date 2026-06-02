---
title: "GifGraphicsControlBlock"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Bloc de contrôle graphique Gif."
type: docs
weight: 13
url: /fr/java/com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifGraphicsControlBlock extends GifBlock
```

Bloc de contrôle graphique Gif.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock--) | Initialise une nouvelle instance de la classe `GifGraphicsControlBlock`. |
| [GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)](#GifGraphicsControlBlock-byte-int-byte-) | Initialise une nouvelle instance de la classe `GifGraphicsControlBlock`. |
| [GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)](#GifGraphicsControlBlock-int-boolean-byte-boolean-int-) | Initialise une nouvelle instance de la classe `GifGraphicsControlBlock`. |
## Champs

| Champ | Description |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Spécifie la taille de l'en-tête du bloc. |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Étiquette d'extension. |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | Obtient la taille du sous-bloc. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDelayTime()](#getDelayTime--) | Obtient ou définit le temps de retard de la trame exprimé en 1/100 de seconde. |
| [setDelayTime(int value)](#setDelayTime-int-) | Obtient ou définit le temps de retard de la trame exprimé en 1/100 de seconde. |
| [getFlags()](#getFlags--) | Obtient ou définit les indicateurs. |
| [setFlags(byte value)](#setFlags-byte-) | Obtient ou définit les indicateurs. |
| [getTransparentColorIndex()](#getTransparentColorIndex--) | Obtient ou définit l'index de couleur transparente. |
| [setTransparentColorIndex(byte value)](#setTransparentColorIndex-byte-) | Obtient ou définit l'index de couleur transparente. |
| [getDisposalMethod()](#getDisposalMethod--) | Obtient ou définit la méthode de disposition. |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | Obtient ou définit la méthode de disposition. |
| [getUserInputExpected()](#getUserInputExpected--) | Obtient ou définit une valeur indiquant si une entrée utilisateur est attendue. |
| [setUserInputExpected(boolean value)](#setUserInputExpected-boolean-) | Obtient ou définit une valeur indiquant si une entrée utilisateur est attendue. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtient ou définit une valeur indiquant si le bloc de contrôle graphique possède une couleur transparente. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Obtient ou définit une valeur indiquant si le bloc de contrôle graphique possède une couleur transparente. |
| [createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)](#createFlags-boolean-boolean-int-) | Crée les indicateurs. |
### GifGraphicsControlBlock() {#GifGraphicsControlBlock--}
```
public GifGraphicsControlBlock()
```


Initialise une nouvelle instance de la classe `GifGraphicsControlBlock`.

### GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex) {#GifGraphicsControlBlock-byte-int-byte-}
```
public GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)
```


Initialise une nouvelle instance de la classe `GifGraphicsControlBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| drapeaux | byte | Les indicateurs. |
| delayTime | int | Le temps de retard exprimé en 1/100 de seconde. |
| transparentColorIndex | byte | L'index de couleur transparente. |

### GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod) {#GifGraphicsControlBlock-int-boolean-byte-boolean-int-}
```
public GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)
```


Initialise une nouvelle instance de la classe `GifGraphicsControlBlock`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| delayTime | int | Le temps de retard exprimé en 1/100 de seconde. |
| hasTransparentColor | boolean | si défini sur `true`, le `transparentColorIndex` est valide. |
| transparentColorIndex | byte | L'index de couleur transparente. |
| requiresUserInput | boolean | si défini sur `true`, l'entrée utilisateur est attendue. |
| disposalMethod | int | La méthode de disposition. |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Spécifie la taille de l'en-tête du bloc.

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Étiquette d'extension.

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


Obtient la taille du sous-bloc.

### getDelayTime() {#getDelayTime--}
```
public int getDelayTime()
```


Obtient ou définit le temps de retard de la trame exprimé en 1/100 de seconde.

**Returns:**
int
### setDelayTime(int value) {#setDelayTime-int-}
```
public void setDelayTime(int value)
```


Obtient ou définit le temps de retard de la trame exprimé en 1/100 de seconde.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getFlags() {#getFlags--}
```
public byte getFlags()
```


Obtient ou définit les indicateurs.

Valeur : les indicateurs.

**Returns:**
byte
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


Obtient ou définit les indicateurs.

Valeur : les indicateurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getTransparentColorIndex() {#getTransparentColorIndex--}
```
public byte getTransparentColorIndex()
```


Obtient ou définit l'index de couleur transparente.

Valeur : l'index de couleur transparente.

**Returns:**
byte
### setTransparentColorIndex(byte value) {#setTransparentColorIndex-byte-}
```
public void setTransparentColorIndex(byte value)
```


Obtient ou définit l'index de couleur transparente.

Valeur : l'index de couleur transparente.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


Obtient ou définit la méthode de disposition.

Valeur : la méthode de disposition.

**Returns:**
int
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public void setDisposalMethod(int value)
```


Obtient ou définit la méthode de disposition.

Valeur : la méthode de disposition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getUserInputExpected() {#getUserInputExpected--}
```
public boolean getUserInputExpected()
```


Obtient ou définit une valeur indiquant si une entrée utilisateur est attendue.

Valeur : `true` si l'entrée utilisateur est attendue ; sinon, `false`.

**Returns:**
boolean
### setUserInputExpected(boolean value) {#setUserInputExpected-boolean-}
```
public void setUserInputExpected(boolean value)
```


Obtient ou définit une valeur indiquant si une entrée utilisateur est attendue.

Valeur : `true` si l'entrée utilisateur est attendue ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Obtient ou définit une valeur indiquant si le bloc de contrôle graphique possède une couleur transparente.

Valeur : `true` si le bloc de contrôle graphique possède une couleur transparente ; sinon, `false`.

**Returns:**
boolean
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Obtient ou définit une valeur indiquant si le bloc de contrôle graphique possède une couleur transparente.

Valeur : `true` si le bloc de contrôle graphique possède une couleur transparente ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean |  |

### createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod) {#createFlags-boolean-boolean-int-}
```
public static byte createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)
```


Crée les indicateurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| hasTransparentColor | boolean | si défini sur `true`, le `GifGraphicsControlBlock` a un index de couleur transparente valide. |
| requiresUserInput | boolean | si défini sur `true`, l'entrée utilisateur est attendue. |
| disposalMethod | int | La méthode de disposition. |

**Returns:**
byte - Les indicateurs générés.
