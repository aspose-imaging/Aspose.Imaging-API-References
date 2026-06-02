---
title: "EmfCreateColorSpaceW"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_CREATECOLORSPACEW crée un objet d'espace colorimétrique logique à partir d'un profil couleur dont le nom est composé de caractères Unicode."
type: docs
weight: 37
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpaceW extends EmfObjectCreationRecordType
```

L'enregistrement EMR\_CREATECOLORSPACEW crée un objet d'espace colorimétrique logique à partir d'un profil couleur dont le nom est composé de caractères Unicode.

L'objet d'espace colorimétrique logique défini par cet enregistrement peut être sélectionné dans le contexte du dispositif de lecture par un enregistrement EMR\_SETCOLORSPACE (section 2.3.8.7), qui définit l'espace colorimétrique logique à utiliser dans les opérations graphiques ultérieures.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfCreateColorSpaceW(EmfRecord source)](#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfCreateColorSpaceW`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getIhCS()](#getIhCS--) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet d'espace colorimétrique logique dans la table d'objets EMF (section 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet d'espace colorimétrique logique dans la table d'objets EMF (section 3.1.1.1). |
| [getLcs()](#getLcs--) | Obtient ou définit un objet WMF LogColorSpaceW ([MS-WMF] section 2.2.2.12) qui peut spécifier le nom d'un profil couleur en caractères Unicode UTF16-LE |
| [setLcs(WmfLogColorSpaceW value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-) | Obtient ou définit un objet WMF LogColorSpaceW ([MS-WMF] section 2.2.2.12) qui peut spécifier le nom d'un profil couleur en caractères Unicode UTF16-LE |
| [getDwFlags()](#getDwFlags--) | Obtient ou définit un entier non signé de 32 bits qui fournit des informations sur les données de cet enregistrement. |
| [setDwFlags(int value)](#setDwFlags-int-) | Obtient ou définit un entier non signé de 32 bits qui fournit des informations sur les données de cet enregistrement. |
| [getCbData()](#getCbData--) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, du champ Data. |
| [setCbData(int value)](#setCbData-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, du champ Data. |
| [getData()](#getData--) | Obtient ou définit un tableau d'octets optionnel qui spécifie les données du profil couleur. |
| [setData(byte[] value)](#setData-byte---) | Obtient ou définit un tableau d'octets optionnel qui spécifie les données du profil couleur. |
### EmfCreateColorSpaceW(EmfRecord source) {#EmfCreateColorSpaceW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpaceW(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfCreateColorSpaceW`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getIhCS() {#getIhCS--}
```
public int getIhCS()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet d'espace colorimétrique logique dans la table d'objets EMF (section 3.1.1.1). Cet index DOIT être enregistré afin que cet objet puisse être réutilisé ou modifié.

**Returns:**
int
### setIhCS(int value) {#setIhCS-int-}
```
public void setIhCS(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet d'espace colorimétrique logique dans la table d'objets EMF (section 3.1.1.1). Cet index DOIT être enregistré afin que cet objet puisse être réutilisé ou modifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLcs() {#getLcs--}
```
public WmfLogColorSpaceW getLcs()
```


Obtient ou définit un objet WMF LogColorSpaceW ([MS-WMF] section 2.2.2.12) qui peut spécifier le nom d'un profil couleur en caractères Unicode UTF16-LE

**Returns:**
[WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew)
### setLcs(WmfLogColorSpaceW value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpaceW-}
```
public void setLcs(WmfLogColorSpaceW value)
```


Obtient ou définit un objet WMF LogColorSpaceW ([MS-WMF] section 2.2.2.12) qui peut spécifier le nom d'un profil couleur en caractères Unicode UTF16-LE

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfLogColorSpaceW](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew) |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Obtient ou définit un entier non signé de 32 bits qui fournit des informations sur les données de cet enregistrement.

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Obtient ou définit un entier non signé de 32 bits qui fournit des informations sur les données de cet enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, du champ Data.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie la taille, en octets, du champ Data.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Obtient ou définit un tableau d'octets optionnel qui spécifie les données du profil couleur.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Obtient ou définit un tableau d'octets optionnel qui spécifie les données du profil couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] |  |

