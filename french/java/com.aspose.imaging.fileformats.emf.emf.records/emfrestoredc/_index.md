---
title: "EmfRestoreDc"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_RESTOREDC restaure le contexte de périphérique de lecture à l'état spécifié."
type: docs
weight: 109
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfRestoreDc extends EmfStateRecordType
```

L'enregistrement EMR\_RESTOREDC restaure le contexte de périphérique de lecture à l'état spécifié. Le contexte de périphérique de lecture est restauré en dépilant les informations d'état d'une pile qui a été créée par les enregistrements EMR\_SAVEDC précédents (section 2.3.11).

La pile peut contenir des informations d'état pour plusieurs instances du contexte de périphérique de lecture. Lorsqu'un état est restauré, toutes les instances d'état sauvegardées plus récemment DOIVENT être abandonnées.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfRestoreDc(EmfRecord source)](#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfRestoreDc`. |
| [EmfRestoreDc()](#EmfRestoreDc--) | Initialise une nouvelle instance de la classe `EmfRestoreDc`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSavedDc()](#getSavedDc--) | Obtient ou définit un entier signé de 32 bits qui spécifie l'état sauvegardé à restaurer par rapport à l'état actuel. |
| [setSavedDc(int value)](#setSavedDc-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie l'état sauvegardé à restaurer par rapport à l'état actuel. |
### EmfRestoreDc(EmfRecord source) {#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRestoreDc(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfRestoreDc`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfRestoreDc() {#EmfRestoreDc--}
```
public EmfRestoreDc()
```


Initialise une nouvelle instance de la classe `EmfRestoreDc`.

### getSavedDc() {#getSavedDc--}
```
public int getSavedDc()
```


Obtient ou définit un entier signé de 32 bits qui spécifie l'état sauvegardé à restaurer par rapport à l'état actuel. Cette valeur DOIT être négative ; \\u20131 représente l'état qui a été le plus récemment sauvegardé sur la pile, \\u20132 celui qui le précède, etc.

**Returns:**
int
### setSavedDc(int value) {#setSavedDc-int-}
```
public void setSavedDc(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie l'état sauvegardé à restaurer par rapport à l'état actuel. Cette valeur DOIT être négative ; \\u20131 représente l'état qui a été le plus récemment sauvegardé sur la pile, \\u20132 celui qui le précède, etc.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

