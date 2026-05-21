---
title: "EmfExtSelectClipRgn"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_EXTSELECTCLIPRGN combine la région spécifiée avec la région de découpage actuelle en utilisant le mode spécifié."
type: docs
weight: 55
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfextselectcliprgn/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExtSelectClipRgn extends EmfClippingRecordType
```

L'enregistrement EMR\_EXTSELECTCLIPRGN combine la région spécifiée avec la région de découpage actuelle en utilisant le mode spécifié. Remarque : les champs qui ne sont pas décrits dans cette section sont spécifiés dans la section 2.3.2.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfExtSelectClipRgn(EmfRecord source)](#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfExtSelectClipRgn`. |
| [EmfExtSelectClipRgn()](#EmfExtSelectClipRgn--) | Initialise une nouvelle instance de la classe `EmfExtSelectClipRgn`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRgnDataSize()](#getRgnDataSize--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données de région en octets. |
| [setRgnDataSize(int value)](#setRgnDataSize-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données de région en octets. |
| [getRegionMode()](#getRegionMode--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la façon d'utiliser la région. |
| [setRegionMode(int value)](#setRegionMode-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la façon d'utiliser la région. |
| [getRgnData()](#getRgnData--) | Obtient ou définit un tableau d'octets de longueur RgnDataSize qui spécifie un objet RegionData en unités logiques. |
| [setRgnData(EmfRegionData value)](#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-) | Obtient ou définit un tableau d'octets de longueur RgnDataSize qui spécifie un objet RegionData en unités logiques. |
### EmfExtSelectClipRgn(EmfRecord source) {#EmfExtSelectClipRgn-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtSelectClipRgn(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfExtSelectClipRgn`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfExtSelectClipRgn() {#EmfExtSelectClipRgn--}
```
public EmfExtSelectClipRgn()
```


Initialise une nouvelle instance de la classe `EmfExtSelectClipRgn`.

### getRgnDataSize() {#getRgnDataSize--}
```
public int getRgnDataSize()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données de région en octets.

**Returns:**
int
### setRgnDataSize(int value) {#setRgnDataSize-int-}
```
public void setRgnDataSize(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données de région en octets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRegionMode() {#getRegionMode--}
```
public int getRegionMode()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la façon d'utiliser la région. La valeur DOIT appartenir à l'énumération RegionMode (section 2.1.29).

**Returns:**
int
### setRegionMode(int value) {#setRegionMode-int-}
```
public void setRegionMode(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la façon d'utiliser la région. La valeur DOIT appartenir à l'énumération RegionMode (section 2.1.29).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRgnData() {#getRgnData--}
```
public EmfRegionData getRgnData()
```


Obtient ou définit un tableau d'octets de longueur RgnDataSize qui spécifie un objet RegionData en unités logiques. Si RegionMode est RGN\_COPY, ces données peuvent être omises et la région de découpage DOIT être définie sur la région de découpage par défaut (NULL).

**Returns:**
[EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata)
### setRgnData(EmfRegionData value) {#setRgnData-com.aspose.imaging.fileformats.emf.emf.objects.EmfRegionData-}
```
public void setRgnData(EmfRegionData value)
```


Obtient ou définit un tableau d'octets de longueur RgnDataSize qui spécifie un objet RegionData en unités logiques. Si RegionMode est RGN\_COPY, ces données peuvent être omises et la région de découpage DOIT être définie sur la région de découpage par défaut (NULL).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfRegionData](../../com.aspose.imaging.fileformats.emf.emf.objects/emfregiondata) |  |

