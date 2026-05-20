---
title: "EmfFrameRgn"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_FRAMERGN dessine une bordure autour de la région spécifiée en utilisant le pinceau spécifié."
type: docs
weight: 62
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfframergn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFrameRgn extends EmfDrawingRecordType
```

L'enregistrement EMR\_FRAMERGN dessine une bordure autour de la région spécifiée en utilisant la brosse spécifiée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfFrameRgn(EmfRecord source)](#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfFrameRgn`. |
| [EmfFrameRgn()](#EmfFrameRgn--) | Initialise une nouvelle instance de la classe [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui indique le rectangle englobant. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui indique le rectangle englobant. |
| [getRgnDataSize()](#getRgnDataSize--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données de région, en octets. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données de région, en octets. |
| [getIhBrush()](#getIhBrush--) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la table des objets EMF du pinceau. |
| [setIhBrush(int value)](#setIhBrush-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la table des objets EMF du pinceau. |
| [getWidth()](#getWidth--) | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur du trait de pinceau vertical, en unités logiques. |
| [setWidth(int value)](#setWidth-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la largeur du trait de pinceau vertical, en unités logiques. |
| [getHeight()](#getHeight--) | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur du trait de pinceau horizontal, en unités logiques. |
| [setHeight(int value)](#setHeight-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur du trait de pinceau horizontal, en unités logiques. |
| [getRgnData()](#getRgnData--) | Obtient ou définit un tableau d'octets de longueur RgnDataSize qui spécifie un objet RegionData, en unités logiques. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Obtient ou définit un tableau d'octets de longueur RgnDataSize qui spécifie un objet RegionData, en unités logiques. |
### EmfFrameRgn(EmfRecord source) {#EmfFrameRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFrameRgn(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfFrameRgn`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfFrameRgn() {#EmfFrameRgn--}
```
public EmfFrameRgn()
```


Initialise une nouvelle instance de la classe [EmfFrameRgn](../../com.aspose.imaging.fileformats.emf.emf.records/emfframergn).

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui indique le rectangle englobant.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui indique le rectangle englobant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données de région, en octets.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données de région, en octets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la table des objets EMF du pinceau.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la table des objets EMF du pinceau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la largeur du trait de pinceau vertical, en unités logiques.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la largeur du trait de pinceau vertical, en unités logiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur du trait de pinceau horizontal, en unités logiques.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la hauteur du trait de pinceau horizontal, en unités logiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Obtient ou définit un tableau d'octets de longueur RgnDataSize qui spécifie un objet RegionData, en unités logiques.

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Obtient ou définit un tableau d'octets de longueur RgnDataSize qui spécifie un objet RegionData, en unités logiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

