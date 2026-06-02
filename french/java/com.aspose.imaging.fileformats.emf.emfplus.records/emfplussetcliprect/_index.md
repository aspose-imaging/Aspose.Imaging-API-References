---
title: "EmfPlusSetClipRect"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusSetClipRect combine la région de découpage actuelle avec un rectangle."
type: docs
weight: 56
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRect extends EmfPlusClippingRecordType
```

L'enregistrement EmfPlusSetClipRect combine la région de découpage actuelle avec un rectangle.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusSetClipRect(EmfPlusRecord source)](#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusSetClipRect`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getCm()](#getCm--) | Obtient ou définit le CM (4 bits) : spécifie l'opération logique de combinaison de deux régions. |
| [setCm(byte value)](#setCm-byte-) | Obtient ou définit le CM (4 bits) : spécifie l'opération logique de combinaison de deux régions. |
| [getClipRect()](#getClipRect--) | Obtient ou définit un objet EmfPlusRectF (section 2.2.2.39) qui définit le rectangle à utiliser dans l'opération CombineMode. |
| [setClipRect(RectangleF value)](#setClipRect-com.aspose.imaging.RectangleF-) | Obtient ou définit un objet EmfPlusRectF (section 2.2.2.39) qui définit le rectangle à utiliser dans l'opération CombineMode. |
### EmfPlusSetClipRect(EmfPlusRecord source) {#EmfPlusSetClipRect-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRect(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusSetClipRect`.

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

### getClipRect() {#getClipRect--}
```
public RectangleF getClipRect()
```


Obtient ou définit un objet EmfPlusRectF (section 2.2.2.39) qui définit le rectangle à utiliser dans l'opération CombineMode.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setClipRect(RectangleF value) {#setClipRect-com.aspose.imaging.RectangleF-}
```
public void setClipRect(RectangleF value)
```


Obtient ou définit un objet EmfPlusRectF (section 2.2.2.39) qui définit le rectangle à utiliser dans l'opération CombineMode.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

