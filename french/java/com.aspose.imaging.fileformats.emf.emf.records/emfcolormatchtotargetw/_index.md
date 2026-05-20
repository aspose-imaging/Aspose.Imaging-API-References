---
title: "EmfColorMatchToTargetW"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_COLORMATCHTOTargetW spécifie s'il faut effectuer une correspondance des couleurs avec un profil couleur qui est spécifié dans un fichier dont le nom est composé de caractères Unicode."
type: docs
weight: 24
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfColorMatchToTargetW extends EmfStateRecordType
```

L'enregistrement EMR\_COLORMATCHTOTargetW spécifie s'il faut effectuer une correspondance de couleur avec un profil couleur spécifié dans un fichier dont le nom est composé de caractères Unicode.

Un enregistrement EMR\_COLORMATCHTOTargetW peut être utilisé pour contrôler l'application de la transformation de couleur actuelle dans le contexte du dispositif de lecture. Si la valeur dwAction est CS\_ENABLE, la correspondance des couleurs est activée et la transformation de couleur actuelle DOIT être appliquée aux opérations graphiques suivantes. Si dwAction est réglé sur CS\_DISABLE, la transformation de couleur NE DOIT PAS être appliquée. Tant que la correspondance des couleurs vers la cible est activée par une valeur dwAction de CS\_ENABLE, les modifications de l'espace colorimétrique ou du mappage du gamut de couleur ne sont pas appliquées. Cependant, ces modifications DOIVENT prendre effet lorsque la correspondance des couleurs vers la cible est désactivée. Le champ dwAction NE DOIT PAS être réglé sur CS\_DELETE\_TRANSFORM à moins que la gestion des couleurs n'ait déjà été activée avec un enregistrement EMR\_SETICMMODE (section 2.3.11.14).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfColorMatchToTargetW(EmfRecord source)](#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfColorMatchToTargetW`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDwAction()](#getDwAction--) | Obtient ou définit un entier non signé de 32 bits qui indique une valeur de l'énumération ColorSpace (section 2.1.7). |
| [setDwAction(int value)](#setDwAction-int-) | Obtient ou définit un entier non signé de 32 bits qui indique une valeur de l'énumération ColorSpace (section 2.1.7). |
| [getDwFlags()](#getDwFlags--) | Obtient ou définit un entier non signé de 32 bits qui indique une valeur de l'énumération ColorMatchToTarget (section 2.1.6). |
| [setDwFlags(int value)](#setDwFlags-int-) | Obtient ou définit un entier non signé de 32 bits qui indique une valeur de l'énumération ColorMatchToTarget (section 2.1.6). |
| [getCbName()](#getCbName--) | Obtient ou définit un entier non signé de 32 bits qui indique le nombre d'octets du nom Unicode UTF16-LE du profil couleur souhaité. |
| [setCbName(int value)](#setCbName-int-) | Obtient ou définit un entier non signé de 32 bits qui indique le nombre d'octets du nom Unicode UTF16-LE du profil couleur souhaité. |
| [getCbData()](#getCbData--) | Obtient ou définit un entier non signé de 32 bits qui indique la taille des données brutes du profil couleur cible, si elles sont contenues dans le champ Data. |
| [setCbData(int value)](#setCbData-int-) | Obtient ou définit un entier non signé de 32 bits qui indique la taille des données brutes du profil couleur cible, si elles sont contenues dans le champ Data. |
| [getData()](#getData--) | Obtient ou définit un tableau de taille (cbName + cbData) en octets, qui spécifie le nom UTF16-LE et les données brutes du profil couleur souhaité. |
| [setData(byte[] value)](#setData-byte---) | Obtient ou définit un tableau de taille (cbName + cbData) en octets, qui spécifie le nom UTF16-LE et les données brutes du profil couleur souhaité. |
| [getName()](#getName--) | Obtient le nom |
| [getRawData()](#getRawData--) | Obtient les données brutes |
### EmfColorMatchToTargetW(EmfRecord source) {#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorMatchToTargetW(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfColorMatchToTargetW`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getDwAction() {#getDwAction--}
```
public int getDwAction()
```


Obtient ou définit un entier non signé de 32 bits qui indique une valeur de l'énumération ColorSpace (section 2.1.7).

**Returns:**
int
### setDwAction(int value) {#setDwAction-int-}
```
public void setDwAction(int value)
```


Obtient ou définit un entier non signé de 32 bits qui indique une valeur de l'énumération ColorSpace (section 2.1.7).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Obtient ou définit un entier non signé de 32 bits qui indique une valeur de l'énumération ColorMatchToTarget (section 2.1.6).

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Obtient ou définit un entier non signé de 32 bits qui indique une valeur de l'énumération ColorMatchToTarget (section 2.1.6).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


Obtient ou définit un entier non signé de 32 bits qui indique le nombre d'octets du nom Unicode UTF16-LE du profil couleur souhaité.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


Obtient ou définit un entier non signé de 32 bits qui indique le nombre d'octets du nom Unicode UTF16-LE du profil couleur souhaité.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Obtient ou définit un entier non signé de 32 bits qui indique la taille des données brutes du profil couleur cible, si elles sont contenues dans le champ Data.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Obtient ou définit un entier non signé de 32 bits qui indique la taille des données brutes du profil couleur cible, si elles sont contenues dans le champ Data.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Obtient ou définit un tableau de taille (cbName + cbData) en octets, qui spécifie le nom UTF16-LE et les données brutes du profil couleur souhaité.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Obtient ou définit un tableau de taille (cbName + cbData) en octets, qui spécifie le nom UTF16-LE et les données brutes du profil couleur souhaité.

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
