---
title: "EmfExtCreateFontIndirectW"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L’enregistrement EMR_EXTCREATEFONTINDIRECTW définit une police logique pour les opérations graphiques."
type: docs
weight: 51
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreateFontIndirectW extends EmfObjectCreationRecordType
```

L'enregistrement EMR\_EXTCREATEFONTINDIRECTW définit une police logique pour les opérations graphiques.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfExtCreateFontIndirectW(EmfRecord source)](#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfExtCreateFontIndirectW`. |
| [EmfExtCreateFontIndirectW()](#EmfExtCreateFontIndirectW--) | Initialise une nouvelle instance de la classe `EmfExtCreateFontIndirectW`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getIhFonts()](#getIhFonts--) | Obtient ou définit un entier non signé de 32 bits qui indique l’indice de l’objet police logique dans la table d’objets EMF (section 3.1.1.1). |
| [setIhFonts(int value)](#setIhFonts-int-) | Obtient ou définit un entier non signé de 32 bits qui indique l’indice de l’objet police logique dans la table d’objets EMF (section 3.1.1.1). |
| [getElw()](#getElw--) | Obtient ou définit un objet LogFontExDv (section 2.2.15), qui indique la police logique. |
| [setElw(EmfLogFont value)](#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | Obtient ou définit un objet LogFontExDv (section 2.2.15), qui indique la police logique. |
### EmfExtCreateFontIndirectW(EmfRecord source) {#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreateFontIndirectW(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfExtCreateFontIndirectW`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfExtCreateFontIndirectW() {#EmfExtCreateFontIndirectW--}
```
public EmfExtCreateFontIndirectW()
```


Initialise une nouvelle instance de la classe `EmfExtCreateFontIndirectW`.

### getIhFonts() {#getIhFonts--}
```
public int getIhFonts()
```


Obtient ou définit un entier non signé de 32 bits qui indique l’indice de l’objet police logique dans la table d’objets EMF (section 3.1.1.1). Cet indice DOIT être enregistré afin que cet objet puisse être réutilisé ou modifié.

**Returns:**
int
### setIhFonts(int value) {#setIhFonts-int-}
```
public void setIhFonts(int value)
```


Obtient ou définit un entier non signé de 32 bits qui indique l’indice de l’objet police logique dans la table d’objets EMF (section 3.1.1.1). Cet indice DOIT être enregistré afin que cet objet puisse être réutilisé ou modifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getElw() {#getElw--}
```
public EmfLogFont getElw()
```


Obtient ou définit un objet LogFontExDv (section 2.2.15), qui indique la police logique. Un objet LogFont 2.2.13 PEUT être présent à la place.[90]Le processus de détermination du type d’objet dans ce champ est décrit ci‑dessous.

**Returns:**
[EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
### setElw(EmfLogFont value) {#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public void setElw(EmfLogFont value)
```


Obtient ou définit un objet LogFontExDv (section 2.2.15), qui indique la police logique. Un objet LogFont 2.2.13 PEUT être présent à la place.[90]Le processus de détermination du type d’objet dans ce champ est décrit ci‑dessous.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) |  |

