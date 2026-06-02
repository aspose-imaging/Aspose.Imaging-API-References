---
title: "EmfPixelFormatDescriptor"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto PixelFormatDescriptor può essere usato nei record EMR_HEADER sezione 2.3.4.2 per specificare il formato pixel della superficie di output per il contesto del dispositivo di riproduzione."
type: docs
weight: 31
url: /it/java/com.aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfPixelFormatDescriptor extends EmfObject
```

L'oggetto PixelFormatDescriptor può essere usato nei record EMR\_HEADER (sezione 2.3.4.2) per specificare il formato pixel della superficie di output per il contesto del dispositivo di riproduzione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getNSize()](#getNSize--) | Ottiene o imposta un intero a 16 bit che specifica la dimensione, in byte, di questa struttura dati. |
| [setNSize(short value)](#setNSize-short-) | Ottiene o imposta un intero a 16 bit che specifica la dimensione, in byte, di questa struttura dati. |
| [getNVersion()](#getNVersion--) | Ottiene o imposta un intero a 16 bit che DEVE essere impostato a 0x0001. |
| [setNVersion(short value)](#setNVersion-short-) | Ottiene o imposta un intero a 16 bit che DEVE essere impostato a 0x0001. |
| [getDwFlags()](#getDwFlags--) | Ottiene o imposta flag bit che specificano le proprietà del buffer pixel utilizzato per l'output sulla superficie di disegno. |
| [setDwFlags(int value)](#setDwFlags-int-) | Ottiene o imposta flag bit che specificano le proprietà del buffer pixel utilizzato per l'output sulla superficie di disegno. |
| [getIPixelType()](#getIPixelType--) | Ottiene o imposta il tipo di dati pixel PFD\_TYPE\_RGBA 0x00 Il formato pixel è RGBA. |
| [setIPixelType(byte value)](#setIPixelType-byte-) | Ottiene o imposta il tipo di dati pixel PFD\_TYPE\_RGBA 0x00 Il formato pixel è RGBA. |
| [getCColorBits()](#getCColorBits--) | Ottiene o imposta il numero di bit per pixel per i tipi di pixel RGBA, escludendo i piani di bit alfa. |
| [setCColorBits(byte value)](#setCColorBits-byte-) | Ottiene o imposta il numero di bit per pixel per i tipi di pixel RGBA, escludendo i piani di bit alfa. |
| [getCRedBits()](#getCRedBits--) | Ottiene o imposta Specifica il numero di piani di bit rosso in ciascun buffer colore RGBA |
| [setCRedBits(byte value)](#setCRedBits-byte-) | Ottiene o imposta Specifica il numero di piani di bit rosso in ciascun buffer colore RGBA |
| [getCRedShift()](#getCRedShift--) | Ottiene o imposta Specifica il conteggio di spostamento in bit per i piani di bit rosso in ciascun buffer colore RGBA. |
| [setCRedShift(byte value)](#setCRedShift-byte-) | Ottiene o imposta Specifica il conteggio di spostamento in bit per i piani di bit rosso in ciascun buffer colore RGBA. |
| [getCGreenBits()](#getCGreenBits--) | Ottiene o imposta Specifica il numero di piani di bit verde in ciascun buffer colore RGBA |
| [setCGreenBits(byte value)](#setCGreenBits-byte-) | Ottiene o imposta Specifica il numero di piani di bit verde in ciascun buffer colore RGBA |
| [getCGreenShift()](#getCGreenShift--) | Ottiene o imposta Specifica il conteggio di spostamento per i piani di bit verde in ciascun buffer colore RGBA. |
| [setCGreenShift(byte value)](#setCGreenShift-byte-) | Ottiene o imposta Specifica il conteggio di spostamento per i piani di bit verde in ciascun buffer colore RGBA. |
| [getCBlueBits()](#getCBlueBits--) | Ottiene o imposta Specifica il numero di piani di bit blu in ciascun buffer colore RGBA. |
| [setCBlueBits(byte value)](#setCBlueBits-byte-) | Ottiene o imposta Specifica il numero di piani di bit blu in ciascun buffer colore RGBA. |
| [getCBlueShift()](#getCBlueShift--) | Ottiene o imposta Specifica il conteggio di spostamento per i piani di bit blu in ciascun buffer colore RGBA. |
| [setCBlueShift(byte value)](#setCBlueShift-byte-) | Ottiene o imposta Specifica il conteggio di spostamento per i piani di bit blu in ciascun buffer colore RGBA. |
| [getCAlphaBits()](#getCAlphaBits--) | Ottiene o imposta Specifica il numero di piani di bit alfa in ciascun buffer colore RGBA |
| [setCAlphaBits(byte value)](#setCAlphaBits-byte-) | Ottiene o imposta Specifica il numero di piani di bit alfa in ciascun buffer colore RGBA |
| [getCAlphaShift()](#getCAlphaShift--) | Ottiene o imposta Specifica il conteggio di spostamento per i piani di bit alfa in ciascun buffer colore RGBA |
| [setCAlphaShift(byte value)](#setCAlphaShift-byte-) | Ottiene o imposta Specifica il conteggio di spostamento per i piani di bit alfa in ciascun buffer colore RGBA |
| [getCAccumBits()](#getCAccumBits--) | Ottiene o imposta specifica il numero totale di piani di bit nel buffer di accumulazione. |
| [setCAccumBits(byte value)](#setCAccumBits-byte-) | Ottiene o imposta specifica il numero totale di piani di bit nel buffer di accumulazione. |
| [getCAccumRedBits()](#getCAccumRedBits--) | Ottiene o imposta specifica il numero di piani di bit rosso nel buffer di accumulazione |
| [setCAccumRedBits(byte value)](#setCAccumRedBits-byte-) | Ottiene o imposta specifica il numero di piani di bit rosso nel buffer di accumulazione |
| [getCAccumGreenBits()](#getCAccumGreenBits--) | Ottiene o imposta specifica il numero di piani di bit verde nell'accumulazione |
| [setCAccumGreenBits(byte value)](#setCAccumGreenBits-byte-) | Ottiene o imposta specifica il numero di piani di bit verde nell'accumulazione |
| [getCAccumBlueBits()](#getCAccumBlueBits--) | Ottiene o imposta specifica il numero di piani di bit blu nel buffer di accumulazione. |
| [setCAccumBlueBits(byte value)](#setCAccumBlueBits-byte-) | Ottiene o imposta specifica il numero di piani di bit blu nel buffer di accumulazione. |
| [getCAccumAlphaBits()](#getCAccumAlphaBits--) | Ottiene o imposta specifica il numero di piani di bit alfa nel buffer di accumulazione |
| [setCAccumAlphaBits(byte value)](#setCAccumAlphaBits-byte-) | Ottiene o imposta specifica il numero di piani di bit alfa nel buffer di accumulazione |
| [getCDepthBits()](#getCDepthBits--) | Ottiene o imposta specifica la profondità del buffer di profondità (asse z). |
| [setCDepthBits(byte value)](#setCDepthBits-byte-) | Ottiene o imposta specifica la profondità del buffer di profondità (asse z). |
| [getCStencilBits()](#getCStencilBits--) | Ottiene o imposta specifica la profondità del buffer stencil. |
| [setCStencilBits(byte value)](#setCStencilBits-byte-) | Ottiene o imposta specifica la profondità del buffer stencil. |
| [getCAuxBuffers()](#getCAuxBuffers--) | Ottiene o imposta specifica il numero di buffer ausiliari. |
| [setCAuxBuffers(byte value)](#setCAuxBuffers-byte-) | Ottiene o imposta specifica il numero di buffer ausiliari. |
| [getILayerType()](#getILayerType--) | Ottiene o imposta questo campo MAY essere ignorato |
| [setILayerType(byte value)](#setILayerType-byte-) | Ottiene o imposta questo campo MAY essere ignorato |
| [getBReserved()](#getBReserved--) | Ottiene o imposta specifica il numero di piani di sovrapposizione e di sottofondo. |
| [setBReserved(byte value)](#setBReserved-byte-) | Ottiene o imposta specifica il numero di piani di sovrapposizione e di sottofondo. |
| [getDwLayerMask()](#getDwLayerMask--) | Ottiene o imposta questo campo MAY essere ignorato. |
| [setDwLayerMask(int value)](#setDwLayerMask-int-) | Ottiene o imposta questo campo MAY essere ignorato. |
| [getDwVisibleMask()](#getDwVisibleMask--) | Ottiene o imposta specifica il colore trasparente o l'indice di un piano di sottofondo. |
| [setDwVisibleMask(int value)](#setDwVisibleMask-int-) | Ottiene o imposta specifica il colore trasparente o l'indice di un piano di sottofondo. |
| [getDwDamageMask()](#getDwDamageMask--) | Ottiene o imposta questo campo MAY essere ignorato |
| [setDwDamageMask(int value)](#setDwDamageMask-int-) | Ottiene o imposta questo campo MAY essere ignorato |
### EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor--}
```
public EmfPixelFormatDescriptor()
```


### getNSize() {#getNSize--}
```
public short getNSize()
```


Ottiene o imposta un intero a 16 bit che specifica la dimensione, in byte, di questa struttura dati.

**Returns:**
short
### setNSize(short value) {#setNSize-short-}
```
public void setNSize(short value)
```


Ottiene o imposta un intero a 16 bit che specifica la dimensione, in byte, di questa struttura dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getNVersion() {#getNVersion--}
```
public short getNVersion()
```


Ottiene o imposta un intero a 16 bit che DEVE essere impostato a 0x0001.

**Returns:**
short
### setNVersion(short value) {#setNVersion-short-}
```
public void setNVersion(short value)
```


Ottiene o imposta un intero a 16 bit che DEVE essere impostato a 0x0001.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Ottiene o imposta flag di bit che specificano le proprietà del buffer di pixel utilizzato per l'output sulla superficie di disegno. Queste proprietà non sono tutte mutualmente esclusive; sono consentite combinazioni di flag, eccetto dove indicato diversamente.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Ottiene o imposta flag di bit che specificano le proprietà del buffer di pixel utilizzato per l'output sulla superficie di disegno. Queste proprietà non sono tutte mutualmente esclusive; sono consentite combinazioni di flag, eccetto dove indicato diversamente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getIPixelType() {#getIPixelType--}
```
public byte getIPixelType()
```


Ottiene o imposta il tipo di dati pixel PFD\_TYPE\_RGBA 0x00 Il formato pixel è RGBA. PFD\_TYPE\_COLORINDEX 0x01 Ogni pixel è un indice in una tavola dei colori.

**Returns:**
byte
### setIPixelType(byte value) {#setIPixelType-byte-}
```
public void setIPixelType(byte value)
```


Ottiene o imposta il tipo di dati pixel PFD\_TYPE\_RGBA 0x00 Il formato pixel è RGBA. PFD\_TYPE\_COLORINDEX 0x01 Ogni pixel è un indice in una tavola dei colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCColorBits() {#getCColorBits--}
```
public byte getCColorBits()
```


Ottiene o imposta il numero di bit per pixel per i tipi di pixel RGBA, escludendo i piani di bit alfa. Per i pixel della tavola dei colori, è la dimensione di ciascun indice della tavola dei colori.

**Returns:**
byte
### setCColorBits(byte value) {#setCColorBits-byte-}
```
public void setCColorBits(byte value)
```


Ottiene o imposta il numero di bit per pixel per i tipi di pixel RGBA, escludendo i piani di bit alfa. Per i pixel della tavola dei colori, è la dimensione di ciascun indice della tavola dei colori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCRedBits() {#getCRedBits--}
```
public byte getCRedBits()
```


Ottiene o imposta Specifica il numero di piani di bit rosso in ciascun buffer colore RGBA

**Returns:**
byte
### setCRedBits(byte value) {#setCRedBits-byte-}
```
public void setCRedBits(byte value)
```


Ottiene o imposta Specifica il numero di piani di bit rosso in ciascun buffer colore RGBA

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCRedShift() {#getCRedShift--}
```
public byte getCRedShift()
```


Ottiene o imposta Specifica il conteggio di spostamento in bit per i piani di bit rosso in ciascun buffer colore RGBA.

**Returns:**
byte
### setCRedShift(byte value) {#setCRedShift-byte-}
```
public void setCRedShift(byte value)
```


Ottiene o imposta Specifica il conteggio di spostamento in bit per i piani di bit rosso in ciascun buffer colore RGBA.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCGreenBits() {#getCGreenBits--}
```
public byte getCGreenBits()
```


Ottiene o imposta Specifica il numero di piani di bit verde in ciascun buffer colore RGBA

**Returns:**
byte
### setCGreenBits(byte value) {#setCGreenBits-byte-}
```
public void setCGreenBits(byte value)
```


Ottiene o imposta Specifica il numero di piani di bit verde in ciascun buffer colore RGBA

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCGreenShift() {#getCGreenShift--}
```
public byte getCGreenShift()
```


Ottiene o imposta Specifica il conteggio di spostamento per i piani di bit verde in ciascun buffer colore RGBA.

**Returns:**
byte
### setCGreenShift(byte value) {#setCGreenShift-byte-}
```
public void setCGreenShift(byte value)
```


Ottiene o imposta Specifica il conteggio di spostamento per i piani di bit verde in ciascun buffer colore RGBA.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCBlueBits() {#getCBlueBits--}
```
public byte getCBlueBits()
```


Ottiene o imposta Specifica il numero di piani di bit blu in ciascun buffer colore RGBA.

**Returns:**
byte
### setCBlueBits(byte value) {#setCBlueBits-byte-}
```
public void setCBlueBits(byte value)
```


Ottiene o imposta Specifica il numero di piani di bit blu in ciascun buffer colore RGBA.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCBlueShift() {#getCBlueShift--}
```
public byte getCBlueShift()
```


Ottiene o imposta Specifica il conteggio di spostamento per i piani di bit blu in ciascun buffer colore RGBA.

**Returns:**
byte
### setCBlueShift(byte value) {#setCBlueShift-byte-}
```
public void setCBlueShift(byte value)
```


Ottiene o imposta Specifica il conteggio di spostamento per i piani di bit blu in ciascun buffer colore RGBA.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCAlphaBits() {#getCAlphaBits--}
```
public byte getCAlphaBits()
```


Ottiene o imposta Specifica il numero di piani di bit alfa in ciascun buffer colore RGBA

**Returns:**
byte
### setCAlphaBits(byte value) {#setCAlphaBits-byte-}
```
public void setCAlphaBits(byte value)
```


Ottiene o imposta Specifica il numero di piani di bit alfa in ciascun buffer colore RGBA

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCAlphaShift() {#getCAlphaShift--}
```
public byte getCAlphaShift()
```


Ottiene o imposta Specifica il conteggio di spostamento per i piani di bit alfa in ciascun buffer colore RGBA

**Returns:**
byte
### setCAlphaShift(byte value) {#setCAlphaShift-byte-}
```
public void setCAlphaShift(byte value)
```


Ottiene o imposta Specifica il conteggio di spostamento per i piani di bit alfa in ciascun buffer colore RGBA

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCAccumBits() {#getCAccumBits--}
```
public byte getCAccumBits()
```


Ottiene o imposta specifica il numero totale di piani di bit nel buffer di accumulazione.

**Returns:**
byte
### setCAccumBits(byte value) {#setCAccumBits-byte-}
```
public void setCAccumBits(byte value)
```


Ottiene o imposta specifica il numero totale di piani di bit nel buffer di accumulazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCAccumRedBits() {#getCAccumRedBits--}
```
public byte getCAccumRedBits()
```


Ottiene o imposta specifica il numero di piani di bit rosso nel buffer di accumulazione

**Returns:**
byte
### setCAccumRedBits(byte value) {#setCAccumRedBits-byte-}
```
public void setCAccumRedBits(byte value)
```


Ottiene o imposta specifica il numero di piani di bit rosso nel buffer di accumulazione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCAccumGreenBits() {#getCAccumGreenBits--}
```
public byte getCAccumGreenBits()
```


Ottiene o imposta specifica il numero di piani di bit verde nell'accumulazione

**Returns:**
byte
### setCAccumGreenBits(byte value) {#setCAccumGreenBits-byte-}
```
public void setCAccumGreenBits(byte value)
```


Ottiene o imposta specifica il numero di piani di bit verde nell'accumulazione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCAccumBlueBits() {#getCAccumBlueBits--}
```
public byte getCAccumBlueBits()
```


Ottiene o imposta specifica il numero di piani di bit blu nel buffer di accumulazione.

**Returns:**
byte
### setCAccumBlueBits(byte value) {#setCAccumBlueBits-byte-}
```
public void setCAccumBlueBits(byte value)
```


Ottiene o imposta specifica il numero di piani di bit blu nel buffer di accumulazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCAccumAlphaBits() {#getCAccumAlphaBits--}
```
public byte getCAccumAlphaBits()
```


Ottiene o imposta specifica il numero di piani di bit alfa nel buffer di accumulazione

**Returns:**
byte
### setCAccumAlphaBits(byte value) {#setCAccumAlphaBits-byte-}
```
public void setCAccumAlphaBits(byte value)
```


Ottiene o imposta specifica il numero di piani di bit alfa nel buffer di accumulazione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCDepthBits() {#getCDepthBits--}
```
public byte getCDepthBits()
```


Ottiene o imposta specifica la profondità del buffer di profondità (asse z).

**Returns:**
byte
### setCDepthBits(byte value) {#setCDepthBits-byte-}
```
public void setCDepthBits(byte value)
```


Ottiene o imposta specifica la profondità del buffer di profondità (asse z).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCStencilBits() {#getCStencilBits--}
```
public byte getCStencilBits()
```


Ottiene o imposta specifica la profondità del buffer stencil.

**Returns:**
byte
### setCStencilBits(byte value) {#setCStencilBits-byte-}
```
public void setCStencilBits(byte value)
```


Ottiene o imposta specifica la profondità del buffer stencil.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getCAuxBuffers() {#getCAuxBuffers--}
```
public byte getCAuxBuffers()
```


Ottiene o imposta specifica il numero di buffer ausiliari. I buffer ausiliari non sono supportati.

**Returns:**
byte
### setCAuxBuffers(byte value) {#setCAuxBuffers-byte-}
```
public void setCAuxBuffers(byte value)
```


Ottiene o imposta specifica il numero di buffer ausiliari. I buffer ausiliari non sono supportati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getILayerType() {#getILayerType--}
```
public byte getILayerType()
```


Ottiene o imposta questo campo MAY essere ignorato

**Returns:**
byte
### setILayerType(byte value) {#setILayerType-byte-}
```
public void setILayerType(byte value)
```


Ottiene o imposta questo campo MAY essere ignorato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getBReserved() {#getBReserved--}
```
public byte getBReserved()
```


Ottiene o imposta specifica il numero di piani di sovrapposizione e di sottofondo. I bit da 0 a 3 specificano fino a 15 piani di sovrapposizione e i bit da 4 a 7 specificano fino a 15 piani di sottofondo.

**Returns:**
byte
### setBReserved(byte value) {#setBReserved-byte-}
```
public void setBReserved(byte value)
```


Ottiene o imposta specifica il numero di piani di sovrapposizione e di sottofondo. I bit da 0 a 3 specificano fino a 15 piani di sovrapposizione e i bit da 4 a 7 specificano fino a 15 piani di sottofondo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte |  |

### getDwLayerMask() {#getDwLayerMask--}
```
public int getDwLayerMask()
```


Ottiene o imposta questo campo MAY essere ignorato.

**Returns:**
int
### setDwLayerMask(int value) {#setDwLayerMask-int-}
```
public void setDwLayerMask(int value)
```


Ottiene o imposta questo campo MAY essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDwVisibleMask() {#getDwVisibleMask--}
```
public int getDwVisibleMask()
```


Ottiene o imposta specifica il colore trasparente o l'indice di un piano di sottofondo. Quando il tipo di pixel è RGBA, dwVisibleMask è un valore di colore RGB trasparente. Quando il tipo di pixel è indice di colore, è un valore di indice trasparente.

**Returns:**
int
### setDwVisibleMask(int value) {#setDwVisibleMask-int-}
```
public void setDwVisibleMask(int value)
```


Ottiene o imposta specifica il colore trasparente o l'indice di un piano di sottofondo. Quando il tipo di pixel è RGBA, dwVisibleMask è un valore di colore RGB trasparente. Quando il tipo di pixel è indice di colore, è un valore di indice trasparente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getDwDamageMask() {#getDwDamageMask--}
```
public int getDwDamageMask()
```


Ottiene o imposta questo campo MAY essere ignorato

**Returns:**
int
### setDwDamageMask(int value) {#setDwDamageMask-int-}
```
public void setDwDamageMask(int value)
```


Ottiene o imposta questo campo MAY essere ignorato

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

