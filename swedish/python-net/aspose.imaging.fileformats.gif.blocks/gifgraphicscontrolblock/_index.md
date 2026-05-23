---
title: "GifGraphicsControlBlock-klass"
type: docs
weight: 40
url: /sv/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---

**Summary:** Gif graphics control block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifGraphicsControlBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock__1) | Initierar en ny instans av klassen [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/). |
| [GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method)](#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2) | Initierar en ny instans av klassen [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/). |
| [GifGraphicsControlBlock(flags, delay_time, transparent_color_index)](#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3) | Initierar en ny instans av klassen [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [static] | int | r | Anger storleken på blockhuvudet. |
| EXTENSION_INTRODUCER [statisk] | System.Byte | r | Extension‑introducer. |
| EXTENSION_LABEL [statisk] | System.Byte | r | Utökningens etikett. |
| SUB_BLOCK_SIZE [static] | System.Byte | r | Hämtar storleken på subblocket. |
| delay_time | int | r/w | Hämtar eller anger bildrutes fördröjningstid uttryckt i 1/100 sekunder. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | r/w | Hämtar eller anger borttagningsmetoden. |
| flaggor | System.Byte | r/w | Hämtar eller anger flaggorna. |
| has_transparent_color | bool | r/w | Hämtar eller anger ett värde som indikerar om grafikstyrningsblocket har transparent färg. |
| is_changed | bool | r/w | Hämtar eller anger ett värde som indikerar om blocket har ändrats och kräver sparning. |
| transparent_color_index | System.Byte | r/w | Hämtar eller anger index för transparent färg. |
| user_input_expected | bool | r/w | Hämtar eller anger ett värde som indikerar om användarinmatning förväntas. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_flags(has_transparent_color, requires_user_input, disposal_method)](#create_flags_has_transparent_color_requires_user_input_disposal_method_1) | Skapar flaggorna. |
| [save(stream)](#save_stream_2) | Sparar blocket till den angivna strömmen. |


### Constructor: GifGraphicsControlBlock() {#GifGraphicsControlBlock__1}


```
 GifGraphicsControlBlock() 
```

Initierar en ny instans av klassen [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/).

### Constructor: GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) {#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2}


```
 GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) 
```

Initierar en ny instans av klassen [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| delay_time | int | Fördröjningstiden uttryckt i 1/100 sekunder. |
| has_transparent_color | bool | om den är inställd på <c>true</c> är _transparentColorIndex_ giltig. |
| transparent_color_index | System.Byte | Det transparenta färgindexet. |
| requires_user_input | bool | om den är inställd på <c>true</c> förväntas användarinmatning. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | Avslutningsmetoden. |

### Constructor: GifGraphicsControlBlock(flags, delay_time, transparent_color_index) {#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3}


```
 GifGraphicsControlBlock(flags, delay_time, transparent_color_index) 
```

Initierar en ny instans av klassen [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| flaggor | System.Byte | Flaggorna. |
| delay_time | int | Fördröjningstiden uttryckt i 1/100 sekunder. |
| transparent_color_index | System.Byte | Det transparenta färgindexet. |

### Method: create_flags(has_transparent_color, requires_user_input, disposal_method)  [static] {#create_flags_has_transparent_color_requires_user_input_disposal_method_1}


```
 create_flags(has_transparent_color, requires_user_input, disposal_method) 
```

Skapar flaggorna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| has_transparent_color | bool | om den är inställd på <c>true</c> har [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) ett giltigt transparent färgindex. |
| requires_user_input | bool | om den är inställd på <c>true</c> förväntas användarinmatning. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | Avslutningsmetoden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Byte | De genererade flaggorna. |


### Method: save(stream) {#save_stream_2}


```
 save(stream) 
```

Sparar blocket till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara data till. |

