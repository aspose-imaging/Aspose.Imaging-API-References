---
title: "EmfInvertRgn"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_INVERTRGN inverse les couleurs dans la région spécifiée."
type: docs
weight: 67
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfinvertrgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfInvertRgn extends EmfStateRecordType
```

L'enregistrement EMR\_INVERTRGN inverse les couleurs dans la région spécifiée.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfInvertRgn(EmfRecord source)](#EmfInvertRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfInvertRgn`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBounds()](#getBounds--) | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui spécifie le rectangle englobant. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Obtient ou définit un objet WMF RectL de 128 bits, spécifié dans [MS-WMF] section 2.2.2.19, qui spécifie le rectangle englobant. |
| [getRgnDataSize()](#getRgnDataSize--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données de région, en octets. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données de région, en octets. |
| [getRgnData()](#getRgnData--) | Obtient ou définit un tableau d'octets de longueur RgnDataSize qui spécifie un objet RegionData, en unités logiques. |
| [setRgnData(byte[] value)](#setRgnData-byte---) | Obtient ou définit un tableau d'octets de longueur RgnDataSize qui spécifie un objet RegionData, en unités logiques. |
### EmfInvertRgn(EmfRecord source) {#EmfInvertRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfInvertRgn(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfInvertRgn`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

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

### getRgnData() {#getRgnData--}
```
public byte[] getRgnData()
```


Obtient ou définit un tableau d'octets de longueur RgnDataSize qui spécifie un objet RegionData, en unités logiques.

**Returns:**
byte[]
### setRgnData(byte[] value) {#setRgnData-byte---}
```
public void setRgnData(byte[] value)
```


Obtient ou définit un tableau d'octets de longueur RgnDataSize qui spécifie un objet RegionData, en unités logiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

