---
title: "EmfFormat"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet EmrFormat contient des informations qui identifient le format des données d'image dans un enregistrement EMR_COMMENT_MULTIFORMATS section 2.3.3.4.3."
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfFormat extends EmfObject
```

L'objet EmrFormat contient des informations qui identifient le format des données d'image dans un enregistrement EMR\_COMMENT\_MULTIFORMATS (section 2.3.3.4.3).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfFormat()](#EmfFormat--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSignature()](#getSignature--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le format des données d'image. |
| [setSignature(int value)](#setSignature-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le format des données d'image. |
| [getVersion()](#getVersion--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le numéro de version du format. |
| [setVersion(int value)](#setVersion-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le numéro de version du format. |
| [getSizeData()](#getSizeData--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données en octets |
| [setSizeData(int value)](#setSizeData-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données en octets |
| [getOffData()](#getOffData--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le décalage des données depuis le début du champ d'identifiant dans un enregistrement EMR\_COMMENT\_PUBLIC (section 2.3.3.4). |
| [setOffData(int value)](#setOffData-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le décalage des données depuis le début du champ d'identifiant dans un enregistrement EMR\_COMMENT\_PUBLIC (section 2.3.3.4). |
### EmfFormat() {#EmfFormat--}
```
public EmfFormat()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le format des données d'image. Cette valeur DOIT appartenir à l'énumération FormatSignature (section 2.1.14).

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le format des données d'image. Cette valeur DOIT appartenir à l'énumération FormatSignature (section 2.1.14).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le numéro de version du format. Si le champ Signature indique un PostScript encapsulé (EPS), cette valeur DOIT être 0x00000001 ; sinon, cette valeur DOIT être ignorée.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le numéro de version du format. Si le champ Signature indique un PostScript encapsulé (EPS), cette valeur DOIT être 0x00000001 ; sinon, cette valeur DOIT être ignorée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données en octets

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données en octets

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getOffData() {#getOffData--}
```
public int getOffData()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le décalage des données depuis le début du champ d'identifiant dans un enregistrement EMR\_COMMENT\_PUBLIC (section 2.3.3.4). Le décalage DOIT être aligné sur 32 bits.

**Returns:**
int
### setOffData(int value) {#setOffData-int-}
```
public void setOffData(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le décalage des données depuis le début du champ d'identifiant dans un enregistrement EMR\_COMMENT\_PUBLIC (section 2.3.3.4). Le décalage DOIT être aligné sur 32 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

