---
title: "EmfFillRgn"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_FILLRGN remplit la région spécifiée en utilisant le pinceau spécifié."
type: docs
weight: 59
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emffillrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfFillRgn extends EmfDrawingRecordType
```

L'enregistrement EMR\_FILLRGN remplit la région spécifiée en utilisant la brosse spécifiée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfFillRgn(EmfRecord source)](#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfFillRgn`. |
| [EmfFillRgn()](#EmfFillRgn--) | Initialise une nouvelle instance de la classe `EmfFillRgn`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui spécifie le rectangle englobant. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui spécifie le rectangle englobant. |
| [getRgnDataSize()](#getRgnDataSize--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données de région, en octets. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données de région, en octets. |
| [getIhBrush()](#getIhBrush--) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la table d'objets EMF du pinceau pour remplir la région. |
| [setIhBrush(int value)](#setIhBrush-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la table d'objets EMF du pinceau pour remplir la région. |
| [getRgnData()](#getRgnData--) | Obtient ou définit un tableau d'octets de longueur RgnDataSize qui contient un objet RegionData (section 2.2.24). |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Obtient ou définit un tableau d'octets de longueur RgnDataSize qui contient un objet RegionData (section 2.2.24). |
### EmfFillRgn(EmfRecord source) {#EmfFillRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfFillRgn(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfFillRgn`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfFillRgn() {#EmfFillRgn--}
```
public EmfFillRgn()
```


Initialise une nouvelle instance de la classe `EmfFillRgn`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui spécifie le rectangle englobant.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui spécifie le rectangle englobant.

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


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la table d'objets EMF du pinceau pour remplir la région.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de la table d'objets EMF du pinceau pour remplir la région.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Obtient ou définit un tableau d'octets de longueur RgnDataSize qui contient un objet RegionData (section 2.2.24).

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Obtient ou définit un tableau d'octets de longueur RgnDataSize qui contient un objet RegionData (section 2.2.24).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

