---
title: "EmfPixelFormatDescriptor"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet PixelFormatDescriptor peut être utilisé dans les enregistrements EMR_HEADER section 2.3.4.2 pour spécifier le format de pixel de la surface de sortie pour le contexte de périphérique de lecture."
type: docs
weight: 31
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfPixelFormatDescriptor extends EmfObject
```

L'objet PixelFormatDescriptor peut être utilisé dans les enregistrements EMR\_HEADER (section 2.3.4.2) pour spécifier le format de pixel de la surface de sortie pour le contexte de dispositif de lecture.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getNSize()](#getNSize--) | Obtient ou définit un entier de 16 bits qui indique la taille, en octets, de cette structure de données. |
| [setNSize(short value)](#setNSize-short-) | Obtient ou définit un entier de 16 bits qui indique la taille, en octets, de cette structure de données. |
| [getNVersion()](#getNVersion--) | Obtient ou définit un entier de 16 bits qui DOIT être fixé à 0x0001. |
| [setNVersion(short value)](#setNVersion-short-) | Obtient ou définit un entier de 16 bits qui DOIT être fixé à 0x0001. |
| [getDwFlags()](#getDwFlags--) | Obtient ou définit des indicateurs binaires qui spécifient les propriétés du tampon de pixels utilisé pour la sortie vers la surface de dessin. |
| [setDwFlags(int value)](#setDwFlags-int-) | Obtient ou définit des indicateurs binaires qui spécifient les propriétés du tampon de pixels utilisé pour la sortie vers la surface de dessin. |
| [getIPixelType()](#getIPixelType--) | Obtient ou définit le type de données de pixel PFD\_TYPE\_RGBA 0x00 Le format de pixel est RGBA. |
| [setIPixelType(byte value)](#setIPixelType-byte-) | Obtient ou définit le type de données de pixel PFD\_TYPE\_RGBA 0x00 Le format de pixel est RGBA. |
| [getCColorBits()](#getCColorBits--) | Obtient ou définit le nombre de bits par pixel pour les types de pixels RGBA, à l'exclusion des plans de bits alpha. |
| [setCColorBits(byte value)](#setCColorBits-byte-) | Obtient ou définit le nombre de bits par pixel pour les types de pixels RGBA, à l'exclusion des plans de bits alpha. |
| [getCRedBits()](#getCRedBits--) | Obtient ou définit le nombre de plans de bits rouges dans chaque tampon couleur RGBA |
| [setCRedBits(byte value)](#setCRedBits-byte-) | Obtient ou définit le nombre de plans de bits rouges dans chaque tampon couleur RGBA |
| [getCRedShift()](#getCRedShift--) | Obtient ou définit le nombre de décalage en bits pour les plans de bits rouges dans chaque tampon couleur RGBA. |
| [setCRedShift(byte value)](#setCRedShift-byte-) | Obtient ou définit le nombre de décalage en bits pour les plans de bits rouges dans chaque tampon couleur RGBA. |
| [getCGreenBits()](#getCGreenBits--) | Obtient ou définit le nombre de plans de bits verts dans chaque tampon couleur RGBA |
| [setCGreenBits(byte value)](#setCGreenBits-byte-) | Obtient ou définit le nombre de plans de bits verts dans chaque tampon couleur RGBA |
| [getCGreenShift()](#getCGreenShift--) | Obtient ou définit le nombre de décalage pour les plans de bits verts dans chaque tampon couleur RGBA. |
| [setCGreenShift(byte value)](#setCGreenShift-byte-) | Obtient ou définit le nombre de décalage pour les plans de bits verts dans chaque tampon couleur RGBA. |
| [getCBlueBits()](#getCBlueBits--) | Obtient ou définit le nombre de plans de bits bleus dans chaque tampon couleur RGBA. |
| [setCBlueBits(byte value)](#setCBlueBits-byte-) | Obtient ou définit le nombre de plans de bits bleus dans chaque tampon couleur RGBA. |
| [getCBlueShift()](#getCBlueShift--) | Obtient ou définit le nombre de décalage pour les plans de bits bleus dans chaque tampon couleur RGBA. |
| [setCBlueShift(byte value)](#setCBlueShift-byte-) | Obtient ou définit le nombre de décalage pour les plans de bits bleus dans chaque tampon couleur RGBA. |
| [getCAlphaBits()](#getCAlphaBits--) | Obtient ou définit le nombre de plans de bits alpha dans chaque tampon couleur RGBA |
| [setCAlphaBits(byte value)](#setCAlphaBits-byte-) | Obtient ou définit le nombre de plans de bits alpha dans chaque tampon couleur RGBA |
| [getCAlphaShift()](#getCAlphaShift--) | Obtient ou définit le nombre de décalage pour les plans de bits alpha dans chaque tampon couleur RGBA |
| [setCAlphaShift(byte value)](#setCAlphaShift-byte-) | Obtient ou définit le nombre de décalage pour les plans de bits alpha dans chaque tampon couleur RGBA |
| [getCAccumBits()](#getCAccumBits--) | Obtient ou définit le nombre total de plans de bits dans le tampon d'accumulation. |
| [setCAccumBits(byte value)](#setCAccumBits-byte-) | Obtient ou définit le nombre total de plans de bits dans le tampon d'accumulation. |
| [getCAccumRedBits()](#getCAccumRedBits--) | Obtient ou définit le nombre de plans de bits rouges dans le tampon d'accumulation |
| [setCAccumRedBits(byte value)](#setCAccumRedBits-byte-) | Obtient ou définit le nombre de plans de bits rouges dans le tampon d'accumulation |
| [getCAccumGreenBits()](#getCAccumGreenBits--) | Obtient ou définit le nombre de plans de bits verts dans le tampon d'accumulation |
| [setCAccumGreenBits(byte value)](#setCAccumGreenBits-byte-) | Obtient ou définit le nombre de plans de bits verts dans le tampon d'accumulation |
| [getCAccumBlueBits()](#getCAccumBlueBits--) | Obtient ou définit le nombre de plans de bits bleus dans le tampon d'accumulation. |
| [setCAccumBlueBits(byte value)](#setCAccumBlueBits-byte-) | Obtient ou définit le nombre de plans de bits bleus dans le tampon d'accumulation. |
| [getCAccumAlphaBits()](#getCAccumAlphaBits--) | Obtient ou définit le nombre de plans de bits alpha dans le tampon d'accumulation |
| [setCAccumAlphaBits(byte value)](#setCAccumAlphaBits-byte-) | Obtient ou définit le nombre de plans de bits alpha dans le tampon d'accumulation |
| [getCDepthBits()](#getCDepthBits--) | Obtient ou définit la profondeur du tampon de profondeur (axe z). |
| [setCDepthBits(byte value)](#setCDepthBits-byte-) | Obtient ou définit la profondeur du tampon de profondeur (axe z). |
| [getCStencilBits()](#getCStencilBits--) | Obtient ou définit la profondeur du tampon de pochoir. |
| [setCStencilBits(byte value)](#setCStencilBits-byte-) | Obtient ou définit la profondeur du tampon de pochoir. |
| [getCAuxBuffers()](#getCAuxBuffers--) | Obtient ou définit le nombre de tampons auxiliaires. |
| [setCAuxBuffers(byte value)](#setCAuxBuffers-byte-) | Obtient ou définit le nombre de tampons auxiliaires. |
| [getILayerType()](#getILayerType--) | Obtient ou définit Ce champ PEUT être ignoré |
| [setILayerType(byte value)](#setILayerType-byte-) | Obtient ou définit Ce champ PEUT être ignoré |
| [getBReserved()](#getBReserved--) | Obtient ou définit le nombre de plans de superposition et de sous‑couche. |
| [setBReserved(byte value)](#setBReserved-byte-) | Obtient ou définit le nombre de plans de superposition et de sous‑couche. |
| [getDwLayerMask()](#getDwLayerMask--) | Obtient ou définit Ce champ PEUT être ignoré. |
| [setDwLayerMask(int value)](#setDwLayerMask-int-) | Obtient ou définit Ce champ PEUT être ignoré. |
| [getDwVisibleMask()](#getDwVisibleMask--) | Obtient ou définit la couleur transparente ou l'index d'un plan de sous-couche. |
| [setDwVisibleMask(int value)](#setDwVisibleMask-int-) | Obtient ou définit la couleur transparente ou l'index d'un plan de sous-couche. |
| [getDwDamageMask()](#getDwDamageMask--) | Obtient ou définit Ce champ PEUT être ignoré |
| [setDwDamageMask(int value)](#setDwDamageMask-int-) | Obtient ou définit Ce champ PEUT être ignoré |
### EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor--}
```
public EmfPixelFormatDescriptor()
```


### getNSize() {#getNSize--}
```
public short getNSize()
```


Obtient ou définit un entier de 16 bits qui indique la taille, en octets, de cette structure de données.

**Returns:**
short
### setNSize(short value) {#setNSize-short-}
```
public void setNSize(short value)
```


Obtient ou définit un entier de 16 bits qui indique la taille, en octets, de cette structure de données.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getNVersion() {#getNVersion--}
```
public short getNVersion()
```


Obtient ou définit un entier de 16 bits qui DOIT être fixé à 0x0001.

**Returns:**
short
### setNVersion(short value) {#setNVersion-short-}
```
public void setNVersion(short value)
```


Obtient ou définit un entier de 16 bits qui DOIT être fixé à 0x0001.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Obtient ou définit les indicateurs binaires qui spécifient les propriétés du tampon de pixels utilisé pour la sortie vers la surface de dessin. Ces propriétés ne sont pas toutes mutuellement exclusives ; des combinaisons d'indicateurs sont autorisées, sauf indication contraire.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Obtient ou définit les indicateurs binaires qui spécifient les propriétés du tampon de pixels utilisé pour la sortie vers la surface de dessin. Ces propriétés ne sont pas toutes mutuellement exclusives ; des combinaisons d'indicateurs sont autorisées, sauf indication contraire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getIPixelType() {#getIPixelType--}
```
public byte getIPixelType()
```


Obtient ou définit le type de données de pixel PFD\_TYPE\_RGBA 0x00 Le format de pixel est RGBA. PFD\_TYPE\_COLORINDEX 0x01 Chaque pixel est un index dans une table de couleurs.

**Returns:**
byte
### setIPixelType(byte value) {#setIPixelType-byte-}
```
public void setIPixelType(byte value)
```


Obtient ou définit le type de données de pixel PFD\_TYPE\_RGBA 0x00 Le format de pixel est RGBA. PFD\_TYPE\_COLORINDEX 0x01 Chaque pixel est un index dans une table de couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCColorBits() {#getCColorBits--}
```
public byte getCColorBits()
```


Obtient ou définit le nombre de bits par pixel pour les types de pixels RGBA, en excluant les plans de bits alpha. Pour les pixels de table de couleurs, il s'agit de la taille de chaque index de la table de couleurs.

**Returns:**
byte
### setCColorBits(byte value) {#setCColorBits-byte-}
```
public void setCColorBits(byte value)
```


Obtient ou définit le nombre de bits par pixel pour les types de pixels RGBA, en excluant les plans de bits alpha. Pour les pixels de table de couleurs, il s'agit de la taille de chaque index de la table de couleurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCRedBits() {#getCRedBits--}
```
public byte getCRedBits()
```


Obtient ou définit le nombre de plans de bits rouges dans chaque tampon couleur RGBA

**Returns:**
byte
### setCRedBits(byte value) {#setCRedBits-byte-}
```
public void setCRedBits(byte value)
```


Obtient ou définit le nombre de plans de bits rouges dans chaque tampon couleur RGBA

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCRedShift() {#getCRedShift--}
```
public byte getCRedShift()
```


Obtient ou définit le nombre de décalage en bits pour les plans de bits rouges dans chaque tampon couleur RGBA.

**Returns:**
byte
### setCRedShift(byte value) {#setCRedShift-byte-}
```
public void setCRedShift(byte value)
```


Obtient ou définit le nombre de décalage en bits pour les plans de bits rouges dans chaque tampon couleur RGBA.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCGreenBits() {#getCGreenBits--}
```
public byte getCGreenBits()
```


Obtient ou définit le nombre de plans de bits verts dans chaque tampon couleur RGBA

**Returns:**
byte
### setCGreenBits(byte value) {#setCGreenBits-byte-}
```
public void setCGreenBits(byte value)
```


Obtient ou définit le nombre de plans de bits verts dans chaque tampon couleur RGBA

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCGreenShift() {#getCGreenShift--}
```
public byte getCGreenShift()
```


Obtient ou définit le nombre de décalage pour les plans de bits verts dans chaque tampon couleur RGBA.

**Returns:**
byte
### setCGreenShift(byte value) {#setCGreenShift-byte-}
```
public void setCGreenShift(byte value)
```


Obtient ou définit le nombre de décalage pour les plans de bits verts dans chaque tampon couleur RGBA.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCBlueBits() {#getCBlueBits--}
```
public byte getCBlueBits()
```


Obtient ou définit le nombre de plans de bits bleus dans chaque tampon couleur RGBA.

**Returns:**
byte
### setCBlueBits(byte value) {#setCBlueBits-byte-}
```
public void setCBlueBits(byte value)
```


Obtient ou définit le nombre de plans de bits bleus dans chaque tampon couleur RGBA.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCBlueShift() {#getCBlueShift--}
```
public byte getCBlueShift()
```


Obtient ou définit le nombre de décalage pour les plans de bits bleus dans chaque tampon couleur RGBA.

**Returns:**
byte
### setCBlueShift(byte value) {#setCBlueShift-byte-}
```
public void setCBlueShift(byte value)
```


Obtient ou définit le nombre de décalage pour les plans de bits bleus dans chaque tampon couleur RGBA.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCAlphaBits() {#getCAlphaBits--}
```
public byte getCAlphaBits()
```


Obtient ou définit le nombre de plans de bits alpha dans chaque tampon couleur RGBA

**Returns:**
byte
### setCAlphaBits(byte value) {#setCAlphaBits-byte-}
```
public void setCAlphaBits(byte value)
```


Obtient ou définit le nombre de plans de bits alpha dans chaque tampon couleur RGBA

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCAlphaShift() {#getCAlphaShift--}
```
public byte getCAlphaShift()
```


Obtient ou définit le nombre de décalage pour les plans de bits alpha dans chaque tampon couleur RGBA

**Returns:**
byte
### setCAlphaShift(byte value) {#setCAlphaShift-byte-}
```
public void setCAlphaShift(byte value)
```


Obtient ou définit le nombre de décalage pour les plans de bits alpha dans chaque tampon couleur RGBA

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCAccumBits() {#getCAccumBits--}
```
public byte getCAccumBits()
```


Obtient ou définit le nombre total de plans de bits dans le tampon d'accumulation.

**Returns:**
byte
### setCAccumBits(byte value) {#setCAccumBits-byte-}
```
public void setCAccumBits(byte value)
```


Obtient ou définit le nombre total de plans de bits dans le tampon d'accumulation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCAccumRedBits() {#getCAccumRedBits--}
```
public byte getCAccumRedBits()
```


Obtient ou définit le nombre de plans de bits rouges dans le tampon d'accumulation

**Returns:**
byte
### setCAccumRedBits(byte value) {#setCAccumRedBits-byte-}
```
public void setCAccumRedBits(byte value)
```


Obtient ou définit le nombre de plans de bits rouges dans le tampon d'accumulation

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCAccumGreenBits() {#getCAccumGreenBits--}
```
public byte getCAccumGreenBits()
```


Obtient ou définit le nombre de plans de bits verts dans le tampon d'accumulation

**Returns:**
byte
### setCAccumGreenBits(byte value) {#setCAccumGreenBits-byte-}
```
public void setCAccumGreenBits(byte value)
```


Obtient ou définit le nombre de plans de bits verts dans le tampon d'accumulation

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCAccumBlueBits() {#getCAccumBlueBits--}
```
public byte getCAccumBlueBits()
```


Obtient ou définit le nombre de plans de bits bleus dans le tampon d'accumulation.

**Returns:**
byte
### setCAccumBlueBits(byte value) {#setCAccumBlueBits-byte-}
```
public void setCAccumBlueBits(byte value)
```


Obtient ou définit le nombre de plans de bits bleus dans le tampon d'accumulation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCAccumAlphaBits() {#getCAccumAlphaBits--}
```
public byte getCAccumAlphaBits()
```


Obtient ou définit le nombre de plans de bits alpha dans le tampon d'accumulation

**Returns:**
byte
### setCAccumAlphaBits(byte value) {#setCAccumAlphaBits-byte-}
```
public void setCAccumAlphaBits(byte value)
```


Obtient ou définit le nombre de plans de bits alpha dans le tampon d'accumulation

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCDepthBits() {#getCDepthBits--}
```
public byte getCDepthBits()
```


Obtient ou définit la profondeur du tampon de profondeur (axe z).

**Returns:**
byte
### setCDepthBits(byte value) {#setCDepthBits-byte-}
```
public void setCDepthBits(byte value)
```


Obtient ou définit la profondeur du tampon de profondeur (axe z).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCStencilBits() {#getCStencilBits--}
```
public byte getCStencilBits()
```


Obtient ou définit la profondeur du tampon de pochoir.

**Returns:**
byte
### setCStencilBits(byte value) {#setCStencilBits-byte-}
```
public void setCStencilBits(byte value)
```


Obtient ou définit la profondeur du tampon de pochoir.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getCAuxBuffers() {#getCAuxBuffers--}
```
public byte getCAuxBuffers()
```


Obtient ou définit le nombre de tampons auxiliaires. Les tampons auxiliaires ne sont pas pris en charge.

**Returns:**
byte
### setCAuxBuffers(byte value) {#setCAuxBuffers-byte-}
```
public void setCAuxBuffers(byte value)
```


Obtient ou définit le nombre de tampons auxiliaires. Les tampons auxiliaires ne sont pas pris en charge.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getILayerType() {#getILayerType--}
```
public byte getILayerType()
```


Obtient ou définit Ce champ PEUT être ignoré

**Returns:**
byte
### setILayerType(byte value) {#setILayerType-byte-}
```
public void setILayerType(byte value)
```


Obtient ou définit Ce champ PEUT être ignoré

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getBReserved() {#getBReserved--}
```
public byte getBReserved()
```


Obtient ou définit le nombre de plans de superposition et de sous-couche. Les bits 0 à 3 spécifient jusqu'à 15 plans de superposition et les bits 4 à 7 spécifient jusqu'à 15 plans de sous-couche.

**Returns:**
byte
### setBReserved(byte value) {#setBReserved-byte-}
```
public void setBReserved(byte value)
```


Obtient ou définit le nombre de plans de superposition et de sous-couche. Les bits 0 à 3 spécifient jusqu'à 15 plans de superposition et les bits 4 à 7 spécifient jusqu'à 15 plans de sous-couche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getDwLayerMask() {#getDwLayerMask--}
```
public int getDwLayerMask()
```


Obtient ou définit Ce champ PEUT être ignoré.

**Returns:**
int
### setDwLayerMask(int value) {#setDwLayerMask-int-}
```
public void setDwLayerMask(int value)
```


Obtient ou définit Ce champ PEUT être ignoré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDwVisibleMask() {#getDwVisibleMask--}
```
public int getDwVisibleMask()
```


Obtient ou définit la couleur transparente ou l'index d'un plan de sous-couche. Lorsque le type de pixel est RGBA, dwVisibleMask est une valeur de couleur RGB transparente. Lorsque le type de pixel est un index de couleur, il s'agit d'une valeur d'index transparente.

**Returns:**
int
### setDwVisibleMask(int value) {#setDwVisibleMask-int-}
```
public void setDwVisibleMask(int value)
```


Obtient ou définit la couleur transparente ou l'index d'un plan de sous-couche. Lorsque le type de pixel est RGBA, dwVisibleMask est une valeur de couleur RGB transparente. Lorsque le type de pixel est un index de couleur, il s'agit d'une valeur d'index transparente.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDwDamageMask() {#getDwDamageMask--}
```
public int getDwDamageMask()
```


Obtient ou définit Ce champ PEUT être ignoré

**Returns:**
int
### setDwDamageMask(int value) {#setDwDamageMask-int-}
```
public void setDwDamageMask(int value)
```


Obtient ou définit Ce champ PEUT être ignoré

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

