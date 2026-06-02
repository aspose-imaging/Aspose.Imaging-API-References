---
title: "EmfPaintRgn"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_PAINTRGN peint la région spécifiée en utilisant le pinceau actuellement sélectionné dans le contexte de périphérique de lecture."
type: docs
weight: 80
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfpaintrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfPaintRgn extends EmfDrawingRecordType
```

L'enregistrement EMR\_PAINTRGN peint la région spécifiée en utilisant la brosse actuellement sélectionnée dans le contexte du dispositif de lecture.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPaintRgn(EmfRecord source)](#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfPaintRgn`. |
| [EmfPaintRgn()](#EmfPaintRgn--) | Initialise une nouvelle instance de la classe `EmfPaintRgn`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Obtient un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui indique le rectangle englobant. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui indique le rectangle englobant. |
| [getRgnDataSize()](#getRgnDataSize--) | Obtient un entier non signé de 32 bits qui spécifie la taille des données de région, en octets. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Définit un entier non signé de 32 bits qui spécifie la taille des données de région, en octets. |
| [getRgnData()](#getRgnData--) | Obtient un tableau d'octets de longueur RgnDataSize qui spécifie un objet RegionData (section 2.2.24), en unités logiques. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Définit un tableau d'octets de longueur RgnDataSize qui spécifie un objet RegionData (section 2.2.24), en unités logiques. |
### EmfPaintRgn(EmfRecord source) {#EmfPaintRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPaintRgn(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfPaintRgn`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfPaintRgn() {#EmfPaintRgn--}
```
public EmfPaintRgn()
```


Initialise une nouvelle instance de la classe `EmfPaintRgn`.

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtient un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui indique le rectangle englobant.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui indique le rectangle englobant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Obtient un entier non signé de 32 bits qui spécifie la taille des données de région, en octets.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Définit un entier non signé de 32 bits qui spécifie la taille des données de région, en octets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Obtient un tableau d'octets de longueur RgnDataSize qui spécifie un objet RegionData (section 2.2.24), en unités logiques.

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Définit un tableau d'octets de longueur RgnDataSize qui spécifie un objet RegionData (section 2.2.24), en unités logiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

