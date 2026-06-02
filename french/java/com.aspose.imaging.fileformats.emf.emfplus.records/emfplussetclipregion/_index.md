---
title: "EmfPlusSetClipRegion"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusSetClipRegion combine la région de découpage actuelle avec une autre région graphique."
type: docs
weight: 57
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRegion extends EmfPlusClippingRecordType
```

L'enregistrement EmfPlusSetClipRegion combine la région de découpage actuelle avec une autre région graphique. La nouvelle région de découpage actuelle est définie comme le résultat de l'opération CombineMode appliquée à la région de découpage actuelle précédente et à l'objet EmfPlusRegion spécifié.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusSetClipRegion(EmfPlusRecord source)](#EmfPlusSetClipRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusSetClipRegion`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCm()](#getCm--) | Obtient ou définit le CM (4 bits) : spécifie l'opération logique de combinaison de deux régions. |
| [setCm(byte value)](#setCm-byte-) | Obtient ou définit le CM (4 bits) : spécifie l'opération logique de combinaison de deux régions. |
| [getObjectId()](#getObjectId--) | Obtient ou définit l'index d'un objet EmfPlusRegion (section 2.2.1.8) dans la table d'objets EMF+. La valeur DOIT être comprise entre 0 et 63, inclusivement. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtient ou définit l'index d'un objet EmfPlusRegion (section 2.2.1.8) dans la table d'objets EMF+. La valeur DOIT être comprise entre 0 et 63, inclusivement. |
### EmfPlusSetClipRegion(EmfPlusRecord source) {#EmfPlusSetClipRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRegion(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusSetClipRegion`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getCm() {#getCm--}
```
public byte getCm()
```


Obtient ou définit le CM (4 bits) : spécifie l'opération logique de combinaison de deux régions. Voir l'énumération CombineMode (section 2.1.1.4) pour la signification des valeurs.

Valeur : le cm.

**Returns:**
byte
### setCm(byte value) {#setCm-byte-}
```
public void setCm(byte value)
```


Obtient ou définit le CM (4 bits) : spécifie l'opération logique de combinaison de deux régions. Voir l'énumération CombineMode (section 2.1.1.4) pour la signification des valeurs.

Valeur : le cm.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtient ou définit l'index d'un objet EmfPlusRegion (section 2.2.1.8) dans la table d'objets EMF+. La valeur DOIT être comprise entre 0 et 63, inclusivement.

Valeur : l'identifiant de l'objet.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtient ou définit l'index d'un objet EmfPlusRegion (section 2.2.1.8) dans la table d'objets EMF+. La valeur DOIT être comprise entre 0 et 63, inclusivement.

Valeur : l'identifiant de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

