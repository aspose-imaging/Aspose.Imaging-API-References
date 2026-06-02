---
title: "EmfCreateColorSpace"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_CREATECOLORSPACE crée un objet d'espace colorimétrique logique à partir d'un profil couleur dont le nom est composé de caractères ASCII."
type: docs
weight: 36
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatecolorspace/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateColorSpace extends EmfObjectCreationRecordType
```

L'enregistrement EMR\_CREATECOLORSPACE crée un objet d'espace colorimétrique logique à partir d'un profil couleur dont le nom est composé de caractères ASCII.

L'objet d'espace colorimétrique logique défini par cet enregistrement peut être sélectionné dans le contexte du dispositif de lecture par un enregistrement EMR\_SETCOLORSPACE (section 2.3.8.7), qui définit l'espace colorimétrique logique à utiliser dans les opérations graphiques ultérieures.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfCreateColorSpace(EmfRecord source)](#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfCreateColorSpace`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getIhCS()](#getIhCS--) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet d'espace colorimétrique logique dans la table d'objets EMF (section 3.1.1.1). |
| [setIhCS(int value)](#setIhCS-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet d'espace colorimétrique logique dans la table d'objets EMF (section 3.1.1.1). |
| [getLcs()](#getLcs--) | Obtient ou définit un objet WMF LogColorSpace ([MS-WMF] section 2.2.2.11), qui peut spécifier le nom d'un profil couleur en caractères ASCII. |
| [setLcs(WmfLogColorSpace value)](#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-) | Obtient ou définit un objet WMF LogColorSpace ([MS-WMF] section 2.2.2.11), qui peut spécifier le nom d'un profil couleur en caractères ASCII. |
### EmfCreateColorSpace(EmfRecord source) {#EmfCreateColorSpace-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateColorSpace(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfCreateColorSpace`.

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
public WmfLogColorSpace getLcs()
```


Obtient ou définit un objet WMF LogColorSpace ([MS-WMF] section 2.2.2.11), qui peut spécifier le nom d'un profil couleur en caractères ASCII.

**Returns:**
[WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace)
### setLcs(WmfLogColorSpace value) {#setLcs-com.aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace-}
```
public void setLcs(WmfLogColorSpace value)
```


Obtient ou définit un objet WMF LogColorSpace ([MS-WMF] section 2.2.2.11), qui peut spécifier le nom d'un profil couleur en caractères ASCII.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WmfLogColorSpace](../../com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspace) |  |

