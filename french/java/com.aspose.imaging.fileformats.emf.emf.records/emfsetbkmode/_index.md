---
title: "EmfSetBkMode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_SETBKMODE spécifie le mode de mélange d'arrière-plan du contexte de périphérique de lecture."
type: docs
weight: 120
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetBkMode extends EmfStateRecordType
```

L'enregistrement EMR\_SETBKMODE spécifie le mode de mélange d'arrière-plan du contexte de périphérique de lecture. Le mode de mélange d'arrière-plan est utilisé avec le texte, les pinceaux hachurés et les styles de crayon qui ne sont pas des lignes pleines.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSetBkMode(EmfRecord source)](#EmfSetBkMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSetBkMode`. |
| [EmfSetBkMode()](#EmfSetBkMode--) | Initialise une nouvelle instance de la classe `EmfSetBkMode`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBackgroundMode()](#getBackgroundMode--) | Obtient ou définit un entier non signé de 32 bits qui spécifie le mode d'arrière-plan et DOIT appartenir à l'énumération BackgroundMode (section 2.1.4). |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie le mode d'arrière-plan et DOIT appartenir à l'énumération BackgroundMode (section 2.1.4). |
### EmfSetBkMode(EmfRecord source) {#EmfSetBkMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetBkMode(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSetBkMode`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### EmfSetBkMode() {#EmfSetBkMode--}
```
public EmfSetBkMode()
```


Initialise une nouvelle instance de la classe `EmfSetBkMode`.

### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le mode d'arrière-plan et DOIT appartenir à l'énumération BackgroundMode (section 2.1.4).

**Returns:**
int
### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie le mode d'arrière-plan et DOIT appartenir à l'énumération BackgroundMode (section 2.1.4).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

