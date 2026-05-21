---
title: "EmfSetTextJustification"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EMR_SETTEXTJUSTIFICATION spécifie la quantité d'espace supplémentaire à ajouter aux caractères de césure pour la justification du texte."
type: docs
weight: 141
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextJustification extends EmfStateRecordType
```

L'enregistrement EMR\_SETTEXTJUSTIFICATION spécifie la quantité d'espace supplémentaire à ajouter aux caractères de césure pour la justification du texte.

Au lieu d'utiliser un enregistrement EMR\_SETTEXTJUSTIFICATION, une implémentation DEVRAIT utiliser un enregistrement EMR\_EXTTEXTOUTW (section 2.3.5.8) pour réaliser cette fonction.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfSetTextJustification(EmfRecord source)](#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialise une nouvelle instance de la classe `EmfSetTextJustification`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getNBreakExtra()](#getNBreakExtra--) | Obtient ou définit un entier signé de 32 bits qui spécifie la quantité totale d'espace supplémentaire, en unités logiques, à ajouter. |
| [setNBreakExtra(int value)](#setNBreakExtra-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie la quantité totale d'espace supplémentaire, en unités logiques, à ajouter. |
| [getNBreakCount()](#getNBreakCount--) | Obtient ou définit un entier signé de 32 bits qui spécifie le nombre de caractères de rupture. |
| [setNBreakCount(int value)](#setNBreakCount-int-) | Obtient ou définit un entier signé de 32 bits qui spécifie le nombre de caractères de rupture. |
### EmfSetTextJustification(EmfRecord source) {#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextJustification(EmfRecord source)
```


Initialise une nouvelle instance de la classe `EmfSetTextJustification`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La source. |

### getNBreakExtra() {#getNBreakExtra--}
```
public int getNBreakExtra()
```


Obtient ou définit un entier signé de 32 bits qui spécifie la quantité totale d'espace supplémentaire, en unités logiques, à ajouter.

**Returns:**
int
### setNBreakExtra(int value) {#setNBreakExtra-int-}
```
public void setNBreakExtra(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie la quantité totale d'espace supplémentaire, en unités logiques, à ajouter.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getNBreakCount() {#getNBreakCount--}
```
public int getNBreakCount()
```


Obtient ou définit un entier signé de 32 bits qui spécifie le nombre de caractères de rupture.

**Returns:**
int
### setNBreakCount(int value) {#setNBreakCount-int-}
```
public void setNBreakCount(int value)
```


Obtient ou définit un entier signé de 32 bits qui spécifie le nombre de caractères de rupture.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

