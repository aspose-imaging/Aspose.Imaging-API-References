---
title: "EmfSetIcmProfileA"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_SETICMPROFILEA spécifie un profil couleur dans un fichier dont le nom est composé de caractères ASCII pour la sortie graphique."
type: docs
weight: 126
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmprofilea/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmProfileA extends EmfStateRecordType
```

L'enregistrement EMR\_SETICMPROFILEA spécifie un profil couleur dans un fichier dont le nom est composé de caractères ASCII, pour la sortie graphique.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSetIcmProfileA(EmfRecord source)](#EmfSetIcmProfileA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSetIcmProfileA`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDwFlags()](#getDwFlags--) | Obtient ou définit un entier non signé de 32 bits contenant les indicateurs du profil couleur. |
| [setDwFlags(int value)](#setDwFlags-int-) | Obtient ou définit un entier non signé de 32 bits contenant les indicateurs du profil couleur. |
| [getCbName()](#getCbName--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'octets dans le nom ASCII du profil couleur souhaité. |
| [setCbName(int value)](#setCbName-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'octets dans le nom ASCII du profil couleur souhaité. |
| [getCbData()](#getCbData--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données du profil couleur, si elles sont contenues dans le champ Data. |
| [setCbData(int value)](#setCbData-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données du profil couleur, si elles sont contenues dans le champ Data. |
| [getData()](#getData--) | Obtient ou définit un tableau de taille (cbName + cbData) octets, qui spécifie le nom ASCII et les données brutes du profil couleur souhaité. |
| [setData(byte[] value)](#setData-byte---) | Obtient ou définit un tableau de taille (cbName + cbData) octets, qui spécifie le nom ASCII et les données brutes du profil couleur souhaité. |
| [getName()](#getName--) | Obtient le nom |
| [getRawData()](#getRawData--) | Obtient les données brutes |
### EmfSetIcmProfileA(EmfRecord source) {#EmfSetIcmProfileA-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmProfileA(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSetIcmProfileA`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Obtient ou définit un entier non signé de 32 bits contenant les indicateurs du profil couleur.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Obtient ou définit un entier non signé de 32 bits contenant les indicateurs du profil couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'octets dans le nom ASCII du profil couleur souhaité.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le nombre d'octets dans le nom ASCII du profil couleur souhaité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données du profil couleur, si elles sont contenues dans le champ Data.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille des données du profil couleur, si elles sont contenues dans le champ Data.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Obtient ou définit un tableau de taille (cbName + cbData) octets, qui spécifie le nom ASCII et les données brutes du profil couleur souhaité.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Obtient ou définit un tableau de taille (cbName + cbData) octets, qui spécifie le nom ASCII et les données brutes du profil couleur souhaité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

### getName() {#getName--}
```
public String getName()
```


Obtient le nom

**Returns:**
java.lang.String
### getRawData() {#getRawData--}
```
public byte[] getRawData()
```


Obtient les données brutes

**Returns:**
byte[]
