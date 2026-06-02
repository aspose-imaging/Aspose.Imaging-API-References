---
title: "EmfSetMapperFlags"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le enregistrement EMR_SETMAPPERFLAGS spécifie les paramètres du processus d'appariement des polices logiques aux polices physiques qui est effectué par le mappeur de polices."
type: docs
weight: 131
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetmapperflags/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetMapperFlags extends EmfStateRecordType
```

L'enregistrement EMR\_SETMAPPERFLAGS spécifie les paramètres du processus d'appariement des polices logiques aux polices physiques, effectué par le mappeur de polices.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSetMapperFlags(EmfRecord source)](#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSetMapperFlags`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFlags()](#getFlags--) | Obtient ou définit un entier non signé de 32 bits qui spécifie les paramètres du processus d'appariement des polices. |
| [setFlags(int value)](#setFlags-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie les paramètres du processus d'appariement des polices. |
### EmfSetMapperFlags(EmfRecord source) {#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetMapperFlags(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSetMapperFlags`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie les paramètres du processus d'appariement des polices.

0x00000001 Le mappeur de polices DOIT sélectionner uniquement les polices qui correspondent au rapport d'aspect du dispositif de sortie, tel qu'il est actuellement défini dans le contexte du dispositif de lecture.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie les paramètres du processus d'appariement des polices.

0x00000001 Le mappeur de polices DOIT sélectionner uniquement les polices qui correspondent au rapport d'aspect du dispositif de sortie, tel qu'il est actuellement défini dans le contexte du dispositif de lecture.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

