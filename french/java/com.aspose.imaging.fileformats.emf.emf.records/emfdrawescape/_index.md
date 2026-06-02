---
title: "EmfDrawEscape"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_DRAWESCAPE transmet des informations arbitraires à un pilote d'imprimante."
type: docs
weight: 44
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfdrawescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfDrawEscape extends EmfEscapeRecordType
```

Le enregistrement EMR\_DRAWESCAPE transmet des informations arbitraires à un pilote d'imprimante. L'intention est que ces informations entraînent la réalisation du dessin.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfDrawEscape(EmfRecord source)](#EmfDrawEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfDrawEscape`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCjIn()](#getCjIn--) | Obtient ou définit un entier non signé de 32 bits spécifiant le nombre d'octets à transmettre au pilote d'imprimante. |
| [setCjIn(int value)](#setCjIn-int-) | Obtient ou définit un entier non signé de 32 bits spécifiant le nombre d'octets à transmettre au pilote d'imprimante. |
| [getData()](#getData--) | Obtient ou définit les données à transmettre au pilote d'imprimante. |
| [setData(byte[] value)](#setData-byte---) | Obtient ou définit les données à transmettre au pilote d'imprimante. |
### EmfDrawEscape(EmfRecord source) {#EmfDrawEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDrawEscape(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfDrawEscape`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


Obtient ou définit un entier non signé de 32 bits spécifiant le nombre d'octets à transmettre au pilote d'imprimante.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


Obtient ou définit un entier non signé de 32 bits spécifiant le nombre d'octets à transmettre au pilote d'imprimante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Obtient ou définit les données à transmettre au pilote d'imprimante. Il DOIT y avoir cjIn octets disponibles.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Obtient ou définit les données à transmettre au pilote d'imprimante. Il DOIT y avoir cjIn octets disponibles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

