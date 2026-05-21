---
title: "EmfCreatePalette"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_CREATEPALETTE définit une palette logique pour les opérations graphiques."
type: docs
weight: 40
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePalette extends EmfObjectCreationRecordType
```

L'enregistrement EMR\_CREATEPALETTE définit une palette logique pour les opérations graphiques.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfCreatePalette(EmfRecord source)](#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfCreatePalette`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getIhPal()](#getIhPal--) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet palette logique dans la table d'objets EMF (section 3.1.1.1). |
| [setIhPal(int value)](#setIhPal-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet palette logique dans la table d'objets EMF (section 3.1.1.1). |
| [getLogPalette()](#getLogPalette--) | Obtient ou définit un objet LogPalette (section 2.2.17). |
| [setLogPalette(EmfLogPalette value)](#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-) | Obtient ou définit un objet LogPalette (section 2.2.17). |
### EmfCreatePalette(EmfRecord source) {#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePalette(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfCreatePalette`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet palette logique dans la table d'objets EMF (section 3.1.1.1). Cet index DOIT être enregistré afin que cet objet puisse être réutilisé ou modifié.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie l'index de l'objet palette logique dans la table d'objets EMF (section 3.1.1.1). Cet index DOIT être enregistré afin que cet objet puisse être réutilisé ou modifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLogPalette() {#getLogPalette--}
```
public EmfLogPalette getLogPalette()
```


Obtient ou définit un objet LogPalette (section 2.2.17). Le champ Version de cet objet DOIT être fixé à 0x0300. Si la valeur NumberOfEntries de cet objet est zéro, le traitement de cet enregistrement DOIT échouer.

**Returns:**
[EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette)
### setLogPalette(EmfLogPalette value) {#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-}
```
public void setLogPalette(EmfLogPalette value)
```


Obtient ou définit un objet LogPalette (section 2.2.17). Le champ Version de cet objet DOIT être fixé à 0x0300. Si la valeur NumberOfEntries de cet objet est zéro, le traitement de cet enregistrement DOIT échouer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) |  |

