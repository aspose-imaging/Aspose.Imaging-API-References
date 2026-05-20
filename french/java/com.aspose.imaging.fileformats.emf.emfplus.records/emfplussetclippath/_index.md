---
title: "EmfPlusSetClipPath"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusSetClipPath combine la région de découpage actuelle avec un chemin graphique."
type: docs
weight: 55
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipPath extends EmfPlusClippingRecordType
```

L'enregistrement EmfPlusSetClipPath combine la région de découpage actuelle avec un chemin graphique. La nouvelle région de découpage actuelle est définie sur le résultat de l'opération CombineMode.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusSetClipPath(EmfPlusRecord source)](#EmfPlusSetClipPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusSetClipPath`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCm()](#getCm--) | Obtient ou définit le CM (4 bits) : spécifie l'opération logique de combinaison de deux régions. |
| [setCm(byte value)](#setCm-byte-) | Obtient ou définit le CM (4 bits) : spécifie l'opération logique de combinaison de deux régions. |
| [getObjectId()](#getObjectId--) | Obtient ou définit l'indice d'un objet EmfPlusPath (section 2.2.1.6) dans la table d'objets EMF+. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtient ou définit l'indice d'un objet EmfPlusPath (section 2.2.1.6) dans la table d'objets EMF+. |
### EmfPlusSetClipPath(EmfPlusRecord source) {#EmfPlusSetClipPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipPath(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusSetClipPath`.

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


Obtient ou définit l'indice d'un objet EmfPlusPath (section 2.2.1.6) dans la table d'objets EMF+. La valeur DOIT être comprise entre 0 et 63, inclus.

Valeur : l'identifiant de l'objet.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtient ou définit l'indice d'un objet EmfPlusPath (section 2.2.1.6) dans la table d'objets EMF+. La valeur DOIT être comprise entre 0 et 63, inclus.

Valeur : l'identifiant de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

