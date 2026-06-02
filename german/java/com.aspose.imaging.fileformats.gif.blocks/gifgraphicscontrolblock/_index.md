---
title: "GifGraphicsControlBlock"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Gif-Grafiksteuerungsblock."
type: docs
weight: 13
url: /de/java/com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.gif.GifBlock](../../com.aspose.imaging.fileformats.gif/gifblock)
```
public class GifGraphicsControlBlock extends GifBlock
```

Gif-Grafiksteuerungsblock.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock--) | Initialisiert eine neue Instanz der `GifGraphicsControlBlock`-Klasse. |
| [GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)](#GifGraphicsControlBlock-byte-int-byte-) | Initialisiert eine neue Instanz der `GifGraphicsControlBlock`-Klasse. |
| [GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)](#GifGraphicsControlBlock-int-boolean-byte-boolean-int-) | Initialisiert eine neue Instanz der `GifGraphicsControlBlock`-Klasse. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [BLOCK_HEADER_SIZE](#BLOCK-HEADER-SIZE) | Gibt die Größe des Blockkopfes an. |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Erweiterungsbezeichnung. |
| [SUB_BLOCK_SIZE](#SUB-BLOCK-SIZE) | Liest die Größe des Unterblocks. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDelayTime()](#getDelayTime--) | Liest oder setzt die Bildverzögerungszeit, ausgedrückt in 1/100 Sekunden. |
| [setDelayTime(int value)](#setDelayTime-int-) | Liest oder setzt die Bildverzögerungszeit, ausgedrückt in 1/100 Sekunden. |
| [getFlags()](#getFlags--) | Liest oder setzt die Flags. |
| [setFlags(byte value)](#setFlags-byte-) | Liest oder setzt die Flags. |
| [getTransparentColorIndex()](#getTransparentColorIndex--) | Liest oder setzt den Index der transparenten Farbe. |
| [setTransparentColorIndex(byte value)](#setTransparentColorIndex-byte-) | Liest oder setzt den Index der transparenten Farbe. |
| [getDisposalMethod()](#getDisposalMethod--) | Liest oder setzt die Entsorgungsmethode. |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | Liest oder setzt die Entsorgungsmethode. |
| [getUserInputExpected()](#getUserInputExpected--) | Liest oder setzt einen Wert, der angibt, ob Benutzereingaben erwartet werden. |
| [setUserInputExpected(boolean value)](#setUserInputExpected-boolean-) | Liest oder setzt einen Wert, der angibt, ob Benutzereingaben erwartet werden. |
| [hasTransparentColor()](#hasTransparentColor--) | Liest oder setzt einen Wert, der angibt, ob der Grafiksteuerungsblock eine transparente Farbe hat. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Liest oder setzt einen Wert, der angibt, ob der Grafiksteuerungsblock eine transparente Farbe hat. |
| [createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)](#createFlags-boolean-boolean-int-) | Erstellt die Flags. |
### GifGraphicsControlBlock() {#GifGraphicsControlBlock--}
```
public GifGraphicsControlBlock()
```


Initialisiert eine neue Instanz der `GifGraphicsControlBlock`-Klasse.

### GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex) {#GifGraphicsControlBlock-byte-int-byte-}
```
public GifGraphicsControlBlock(byte flags, int delayTime, byte transparentColorIndex)
```


Initialisiert eine neue Instanz der `GifGraphicsControlBlock`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kennzeichen | byte | Die Flags. |
| delayTime | int | Die Verzögerungszeit, ausgedrückt in 1/100 Sekunden. |
| transparentColorIndex | byte | Der Index der transparenten Farbe. |

### GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod) {#GifGraphicsControlBlock-int-boolean-byte-boolean-int-}
```
public GifGraphicsControlBlock(int delayTime, boolean hasTransparentColor, byte transparentColorIndex, boolean requiresUserInput, int disposalMethod)
```


Initialisiert eine neue Instanz der `GifGraphicsControlBlock`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| delayTime | int | Die Verzögerungszeit, ausgedrückt in 1/100 Sekunden. |
| hasTransparentColor | boolean | wenn auf `true` gesetzt, ist der `transparentColorIndex` gültig. |
| transparentColorIndex | byte | Der Index der transparenten Farbe. |
| requiresUserInput | boolean | wenn auf `true` gesetzt, wird die Benutzereingabe erwartet. |
| disposalMethod | int | Die Entsorgungsmethode. |

### BLOCK_HEADER_SIZE {#BLOCK-HEADER-SIZE}
```
public static final int BLOCK_HEADER_SIZE
```


Gibt die Größe des Blockkopfes an.

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final byte EXTENSION_LABEL
```


Erweiterungsbezeichnung.

### SUB_BLOCK_SIZE {#SUB-BLOCK-SIZE}
```
public static final byte SUB_BLOCK_SIZE
```


Liest die Größe des Unterblocks.

### getDelayTime() {#getDelayTime--}
```
public int getDelayTime()
```


Liest oder setzt die Bildverzögerungszeit, ausgedrückt in 1/100 Sekunden.

**Returns:**
int
### setDelayTime(int value) {#setDelayTime-int-}
```
public void setDelayTime(int value)
```


Liest oder setzt die Bildverzögerungszeit, ausgedrückt in 1/100 Sekunden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getFlags() {#getFlags--}
```
public byte getFlags()
```


Liest oder setzt die Flags.

Wert: Die Flags.

**Returns:**
byte
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


Liest oder setzt die Flags.

Wert: Die Flags.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getTransparentColorIndex() {#getTransparentColorIndex--}
```
public byte getTransparentColorIndex()
```


Liest oder setzt den Index der transparenten Farbe.

Wert: Der Index der transparenten Farbe.

**Returns:**
byte
### setTransparentColorIndex(byte value) {#setTransparentColorIndex-byte-}
```
public void setTransparentColorIndex(byte value)
```


Liest oder setzt den Index der transparenten Farbe.

Wert: Der Index der transparenten Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


Liest oder setzt die Entsorgungsmethode.

Wert: Die Entsorgungsmethode.

**Returns:**
int
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public void setDisposalMethod(int value)
```


Liest oder setzt die Entsorgungsmethode.

Wert: Die Entsorgungsmethode.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getUserInputExpected() {#getUserInputExpected--}
```
public boolean getUserInputExpected()
```


Liest oder setzt einen Wert, der angibt, ob Benutzereingaben erwartet werden.

Wert: `true`, wenn Benutzereingabe erwartet wird; andernfalls `false`.

**Returns:**
boolean
### setUserInputExpected(boolean value) {#setUserInputExpected-boolean-}
```
public void setUserInputExpected(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob Benutzereingaben erwartet werden.

Wert: `true`, wenn Benutzereingabe erwartet wird; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Liest oder setzt einen Wert, der angibt, ob der Grafiksteuerungsblock eine transparente Farbe hat.

Wert: `true`, wenn der Grafiksteuerungsblock eine transparente Farbe hat; andernfalls `false`.

**Returns:**
boolean
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Liest oder setzt einen Wert, der angibt, ob der Grafiksteuerungsblock eine transparente Farbe hat.

Wert: `true`, wenn der Grafiksteuerungsblock eine transparente Farbe hat; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod) {#createFlags-boolean-boolean-int-}
```
public static byte createFlags(boolean hasTransparentColor, boolean requiresUserInput, int disposalMethod)
```


Erstellt die Flags.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| hasTransparentColor | boolean | wenn auf `true` gesetzt, hat der `GifGraphicsControlBlock` einen gültigen Index für transparente Farbe. |
| requiresUserInput | boolean | wenn auf `true` gesetzt, wird die Benutzereingabe erwartet. |
| disposalMethod | int | Die Entsorgungsmethode. |

**Returns:**
byte - Die erzeugten Flags.
