---
title: "Classe GifGraphicsControlBlock"
type: docs
weight: 40
url: /it/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/
---

**Summary:** Gif graphics control block.

**Module:** [aspose.imaging.fileformats.gif.blocks](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/)

**Full Name:** aspose.imaging.fileformats.gif.blocks.GifGraphicsControlBlock

**Inheritance:** IGifBlock, GifBlock

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [GifGraphicsControlBlock()](#GifGraphicsControlBlock__1) | Inizializza una nuova istanza della classe [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/). |
| [GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method)](#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2) | Inizializza una nuova istanza della classe [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/). |
| [GifGraphicsControlBlock(flags, delay_time, transparent_color_index)](#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3) | Inizializza una nuova istanza della classe [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| BLOCK_HEADER_SIZE [static] | int | r | Specifica la dimensione dell'intestazione del blocco. |
| EXTENSION_INTRODUCER [static] | System.Byte | r | Introduttore di estensione. |
| EXTENSION_LABEL [static] | System.Byte | r | Etichetta dell'estensione. |
| SUB_BLOCK_SIZE [static] | System.Byte | r | Ottiene la dimensione del sotto-blocco. |
| delay_time | int | r/w | Ottiene o imposta il tempo di ritardo del fotogramma espresso in 1/100 di secondo. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | r/w | Ottiene o imposta il metodo di smaltimento. |
| flag | System.Byte | r/w | Ottiene o imposta i flag. |
| has_transparent_color | bool | r/w | Ottiene o imposta un valore che indica se il blocco di controllo grafico ha un colore trasparente. |
| is_changed | bool | r/w | Ottiene o imposta un valore che indica se il blocco è stato modificato e richiede il salvataggio. |
| transparent_color_index | System.Byte | r/w | Ottiene o imposta l'indice del colore trasparente. |
| user_input_expected | bool | r/w | Ottiene o imposta un valore che indica se l'input dell'utente è previsto. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_flags(has_transparent_color, requires_user_input, disposal_method)](#create_flags_has_transparent_color_requires_user_input_disposal_method_1) | Crea le flag. |
| [save(stream)](#save_stream_2) | Salva il blocco nello stream specificato. |


### Constructor: GifGraphicsControlBlock() {#GifGraphicsControlBlock__1}


```
 GifGraphicsControlBlock() 
```

Inizializza una nuova istanza della classe [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/).

### Constructor: GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) {#GifGraphicsControlBlock_delay_time_has_transparent_color_transparent_color_index_requires_user_input_disposal_method_2}


```
 GifGraphicsControlBlock(delay_time, has_transparent_color, transparent_color_index, requires_user_input, disposal_method) 
```

Inizializza una nuova istanza della classe [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| delay_time | int | Il tempo di ritardo espresso in 1/100 di secondo. |
| has_transparent_color | bool | se impostato su <c>true</c> l'_transparentColorIndex_ è valido. |
| transparent_color_index | System.Byte | L'indice di colore trasparente. |
| requires_user_input | bool | se impostato su <c>true</c> l'input dell'utente è previsto. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | Il metodo di smaltimento. |

### Constructor: GifGraphicsControlBlock(flags, delay_time, transparent_color_index) {#GifGraphicsControlBlock_flags_delay_time_transparent_color_index_3}


```
 GifGraphicsControlBlock(flags, delay_time, transparent_color_index) 
```

Inizializza una nuova istanza della classe [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| flag | System.Byte | I flag. |
| delay_time | int | Il tempo di ritardo espresso in 1/100 di secondo. |
| transparent_color_index | System.Byte | L'indice di colore trasparente. |

### Method: create_flags(has_transparent_color, requires_user_input, disposal_method)  [static] {#create_flags_has_transparent_color_requires_user_input_disposal_method_1}


```
 create_flags(has_transparent_color, requires_user_input, disposal_method) 
```

Crea le flag.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| has_transparent_color | bool | se impostato su <c>true</c> il [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) ha un indice di colore trasparente valido. |
| requires_user_input | bool | se impostato su <c>true</c> l'input dell'utente è previsto. |
| disposal_method | [DisposalMethod](/imaging/python-net/aspose.imaging.fileformats.gif/disposalmethod/) | Il metodo di smaltimento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Byte | I flag generati. |


### Method: save(stream) {#save_stream_2}


```
 save(stream) 
```

Salva il blocco nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati. |

