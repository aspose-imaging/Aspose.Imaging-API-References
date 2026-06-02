---
title: "EmfPlusSetCompositingMode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusSetCompositingMode spécifie comment les couleurs source sont combinées avec les couleurs d'arrière-plan."
type: docs
weight: 58
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetCompositingMode extends EmfPlusPropertyRecordType
```

L'enregistrement EmfPlusSetCompositingMode spécifie comment les couleurs source sont combinées avec les couleurs d'arrière-plan.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusSetCompositingMode(EmfPlusRecord source)](#EmfPlusSetCompositingMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusSetCompositingMode`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCompositingMode()](#getCompositingMode--) | Obtient ou définit la valeur du mode de composition, à partir de l'énumération CompositingMode (section 2.1.1.5). |
| [setCompositingMode(byte value)](#setCompositingMode-byte-) | Obtient ou définit la valeur du mode de composition, à partir de l'énumération CompositingMode (section 2.1.1.5). |
### EmfPlusSetCompositingMode(EmfPlusRecord source) {#EmfPlusSetCompositingMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetCompositingMode(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusSetCompositingMode`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getCompositingMode() {#getCompositingMode--}
```
public byte getCompositingMode()
```


Obtient ou définit la valeur du mode de composition, à partir de l'énumération CompositingMode (section 2.1.1.5). La composition peut être exprimée comme l'état du mélange alpha, qui peut être activé ou désactivé.

Valeur : le mode de composition.

**Returns:**
byte
### setCompositingMode(byte value) {#setCompositingMode-byte-}
```
public void setCompositingMode(byte value)
```


Obtient ou définit la valeur du mode de composition, à partir de l'énumération CompositingMode (section 2.1.1.5). La composition peut être exprimée comme l'état du mélange alpha, qui peut être activé ou désactivé.

Valeur : le mode de composition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

