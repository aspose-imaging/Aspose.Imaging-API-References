---
title: "EmfPlusSetTextContrast"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusSetTextContrast spécifie le contraste du texte selon la valeur de correction gamma."
type: docs
weight: 64
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettextcontrast/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetTextContrast extends EmfPlusPropertyRecordType
```

L'enregistrement EmfPlusSetTextContrast spécifie le contraste du texte selon la valeur de correction gamma.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusSetTextContrast(EmfPlusRecord source)](#EmfPlusSetTextContrast-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusSetTextContrast`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTextContrast()](#getTextContrast--) | Obtient ou définit la valeur de correction gamma X 1000, qui sera appliquée aux opérations de rendu de texte ultérieures. |
| [setTextContrast(short value)](#setTextContrast-short-) | Obtient ou définit la valeur de correction gamma X 1000, qui sera appliquée aux opérations de rendu de texte ultérieures. |
### EmfPlusSetTextContrast(EmfPlusRecord source) {#EmfPlusSetTextContrast-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTextContrast(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusSetTextContrast`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getTextContrast() {#getTextContrast--}
```
public short getTextContrast()
```


Obtient ou définit la valeur de correction gamma X 1000, qui sera appliquée aux opérations de rendu de texte ultérieures. La plage autorisée est de 1000 à 2200, représentant des valeurs gamma de texte de 1,0 à 2,2.

**Returns:**
short
### setTextContrast(short value) {#setTextContrast-short-}
```
public void setTextContrast(short value)
```


Obtient ou définit la valeur de correction gamma X 1000, qui sera appliquée aux opérations de rendu de texte ultérieures. La plage autorisée est de 1000 à 2200, représentant des valeurs gamma de texte de 1,0 à 2,2.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

