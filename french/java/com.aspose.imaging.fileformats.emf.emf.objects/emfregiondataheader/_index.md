---
title: "EmfRegionDataHeader"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet RegionDataHeader décrit les propriétés d'un objet RegionData."
type: docs
weight: 34
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfRegionDataHeader extends EmfObject
```

L'objet RegionDataHeader décrit les propriétés d'un objet RegionData.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfRegionDataHeader()](#EmfRegionDataHeader--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSize()](#getSize--) | Obtient un entier non signé de 32 bits qui spécifie la taille de cet objet en octets. |
| [setSize(int value)](#setSize-int-) | Définit un entier non signé de 32 bits qui spécifie la taille de cet objet en octets. |
| [getType()](#getType--) | Obtient un entier non signé de 32 bits qui spécifie le type de région. |
| [setType(int value)](#setType-int-) | Définit un entier non signé de 32 bits qui spécifie le type de région. |
| [getCountRects()](#getCountRects--) | Obtient un entier non signé de 32 bits qui spécifie le nombre de rectangles dans cette région. |
| [setCountRects(int value)](#setCountRects-int-) | Définit un entier non signé de 32 bits qui spécifie le nombre de rectangles dans cette région. |
| [getRgnSize()](#getRgnSize--) | Obtient un entier non signé de 32 bits qui spécifie la taille du tampon de rectangles en octets. |
| [setRgnSize(int value)](#setRgnSize-int-) | Définit un entier non signé de 32 bits qui spécifie la taille du tampon de rectangles en octets. |
| [getBounds()](#getBounds--) | Obtient un objet WMF RectL de 128 bits ([MS-WMF] section 2.2.2.19), qui spécifie les limites de la région. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Définit un objet WMF RectL de 128 bits ([MS-WMF] section 2.2.2.19), qui spécifie les limites de la région. |
### EmfRegionDataHeader() {#EmfRegionDataHeader--}
```
public EmfRegionDataHeader()
```


### getSize() {#getSize--}
```
public int getSize()
```


Obtient un entier non signé de 32 bits qui spécifie la taille de cet objet en octets. Cette valeur DOIT être 0x00000020.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Définit un entier non signé de 32 bits qui spécifie la taille de cet objet en octets. Cette valeur DOIT être 0x00000020.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getType() {#getType--}
```
public int getType()
```


Obtient un entier non signé de 32 bits qui spécifie le type de région. Cette valeur DEVRAIT être RDH\_RECTANGLES (0x00000001).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Définit un entier non signé de 32 bits qui spécifie le type de région. Cette valeur DEVRAIT être RDH\_RECTANGLES (0x00000001).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCountRects() {#getCountRects--}
```
public int getCountRects()
```


Obtient un entier non signé de 32 bits qui spécifie le nombre de rectangles dans cette région.

**Returns:**
int
### setCountRects(int value) {#setCountRects-int-}
```
public void setCountRects(int value)
```


Définit un entier non signé de 32 bits qui spécifie le nombre de rectangles dans cette région.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRgnSize() {#getRgnSize--}
```
public int getRgnSize()
```


Obtient un entier non signé de 32 bits qui spécifie la taille du tampon de rectangles en octets.

**Returns:**
int
### setRgnSize(int value) {#setRgnSize-int-}
```
public void setRgnSize(int value)
```


Définit un entier non signé de 32 bits qui spécifie la taille du tampon de rectangles en octets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtient un objet WMF RectL de 128 bits ([MS-WMF] section 2.2.2.19), qui spécifie les limites de la région.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Définit un objet WMF RectL de 128 bits ([MS-WMF] section 2.2.2.19), qui spécifie les limites de la région.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

