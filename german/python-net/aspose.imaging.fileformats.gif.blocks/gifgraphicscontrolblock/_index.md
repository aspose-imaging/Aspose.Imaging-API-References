---
title: "GifGraphicsControlBlock Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---

**Summary:** Gif graphics control block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifGraphicsControlBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock__1) | Initialisiert eine neue Instanz der [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) Klasse. |
| [GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method)](#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2) | Initialisiert eine neue Instanz der [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) Klasse. |
| [GifGraphicsControlBlock(flags, delay_time, transparent_color_index)](#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3) | Initialisiert eine neue Instanz der [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [statisch] | int | r | Gibt die Größe des Blockkopfes an. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Erweiterungs‑Einführer. |
| EXTENSION_LABEL [static] | System.Byte | r | Erweiterungsbezeichnung. |
| SUB_BLOCK_SIZE [static] | System.Byte | r | Liest die Größe des Unterblocks. |
| delay_time | int | r/w | Liest oder setzt die Bildverzögerungszeit, ausgedrückt in 1/100 Sekunden. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | r/w | Ermittelt oder setzt die Entsorgungsmethode. |
| flags | System.Byte | r/w | Liest oder setzt die Flags. |
| has_transparent_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob der Grafiksteuerungsblock eine transparente Farbe hat. |
| is_changed | bool | r/w | Liest oder setzt einen Wert, der angibt, ob der Block geändert wurde und gespeichert werden muss. |
| transparent_color_index | System.Byte | r/w | Liest oder setzt den Index der transparenten Farbe. |
| user_input_expected | bool | r/w | Liest oder setzt einen Wert, der angibt, ob Benutzereingaben erwartet werden. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_flags(has_transparent_color, requires_user_input, disposal_method)](#create_flags_has_transparent_color_requires_user_input_disposal_method_1) | Erstellt die Flags. |
| [save(stream)](#save_stream_2) | Speichert den Block in den angegebenen Stream. |


### Constructor: GifGraphicsControlBlock() {#GifGraphicsControlBlock__1}


```
 GifGraphicsControlBlock() 
```

Initialisiert eine neue Instanz der [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) Klasse.

### Constructor: GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) {#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2}


```
 GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) 
```

Initialisiert eine neue Instanz der [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| delay_time | int | Die Verzögerungszeit ausgedrückt in 1/100 Sekunden. |
| has_transparent_color | bool | wenn auf <c>true</c> gesetzt, ist der _transparentColorIndex_ gültig. |
| transparent_color_index | System.Byte | Der transparente Farbindex. |
| requires_user_input | bool | wenn auf <c>true</c> gesetzt, wird die Benutzereingabe erwartet. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | Die Entsorgungsmethode. |

### Constructor: GifGraphicsControlBlock(flags, delay_time, transparent_color_index) {#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3}


```
 GifGraphicsControlBlock(flags, delay_time, transparent_color_index) 
```

Initialisiert eine neue Instanz der [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| flags | System.Byte | Die Flags. |
| delay_time | int | Die Verzögerungszeit ausgedrückt in 1/100 Sekunden. |
| transparent_color_index | System.Byte | Der transparente Farbindex. |

### Method: create_flags(has_transparent_color, requires_user_input, disposal_method)  [static] {#create_flags_has_transparent_color_requires_user_input_disposal_method_1}


```
 create_flags(has_transparent_color, requires_user_input, disposal_method) 
```

Erstellt die Flags.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| has_transparent_color | bool | wenn auf <c>true</c> gesetzt, hat der [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) einen gültigen transparenten Farbindex. |
| requires_user_input | bool | wenn auf <c>true</c> gesetzt, wird die Benutzereingabe erwartet. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | Die Entsorgungsmethode. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Byte | Die generierten Flags. |


### Method: save(stream) {#save_stream_2}


```
 save(stream) 
```

Speichert den Block in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Der Stream, in dem Daten gespeichert werden. |

