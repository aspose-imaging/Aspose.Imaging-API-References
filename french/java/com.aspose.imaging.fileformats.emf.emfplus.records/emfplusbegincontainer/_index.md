---
title: "EmfPlusBeginContainer"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'enregistrement EmfPlusBeginContainer ouvre un nouveau conteneur d'état graphique et spécifie une transformation pour celui-ci."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainer extends EmfPlusStateRecordType
```

L'enregistrement EmfPlusBeginContainer ouvre un nouveau conteneur d'état graphique et spécifie une transformation pour celui-ci.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfPlusBeginContainer(EmfPlusRecord source)](#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialise une nouvelle instance de la classe `EmfPlusBeginContainer`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | Obtient l'unité de page. |
| [getDestRect()](#getDestRect--) | Obtient ou définit un objet EmfPlusRectF (section 2.2.2.39) qui, avec SrcRect, spécifie une transformation pour le conteneur. |
| [setDestRect(RectangleF value)](#setDestRect-com.aspose.imaging.RectangleF-) | Obtient ou définit un objet EmfPlusRectF (section 2.2.2.39) qui, avec SrcRect, spécifie une transformation pour le conteneur. |
| [getSrcRect()](#getSrcRect--) | Obtient ou définit un rectangle EmfPlusRectF qui, avec DestRect, spécifie une transformation pour le conteneur. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Obtient ou définit un rectangle EmfPlusRectF qui, avec DestRect, spécifie une transformation pour le conteneur. |
| [getStackIndex()](#getStackIndex--) | Obtient ou définit un entier non signé de 32 bits qui spécifie un indice à associer au conteneur d'état graphique. |
| [setStackIndex(int value)](#setStackIndex-int-) | Obtient ou définit un entier non signé de 32 bits qui spécifie un indice à associer au conteneur d'état graphique. |
### EmfPlusBeginContainer(EmfPlusRecord source) {#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainer(EmfPlusRecord source)
```


Initialise une nouvelle instance de la classe `EmfPlusBeginContainer`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | La source. |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Obtient l'unité de page.

Valeur : l'unité de page.

**Returns:**
int
### getDestRect() {#getDestRect--}
```
public RectangleF getDestRect()
```


Obtient ou définit un objet EmfPlusRectF (section 2.2.2.39) qui, avec SrcRect, spécifie une transformation pour le conteneur. Cette transformation donne SrcRect lorsqu'elle est appliquée à DestRect.

Valeur : le rectangle de destination.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setDestRect(RectangleF value) {#setDestRect-com.aspose.imaging.RectangleF-}
```
public void setDestRect(RectangleF value)
```


Obtient ou définit un objet EmfPlusRectF (section 2.2.2.39) qui, avec SrcRect, spécifie une transformation pour le conteneur. Cette transformation donne SrcRect lorsqu'elle est appliquée à DestRect.

Valeur : le rectangle de destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Obtient ou définit un rectangle EmfPlusRectF qui, avec DestRect, spécifie une transformation pour le conteneur. Cette transformation donne SrcRect lorsqu'elle est appliquée à DestRect.

Valeur : le rectangle source.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Obtient ou définit un rectangle EmfPlusRectF qui, avec DestRect, spécifie une transformation pour le conteneur. Cette transformation donne SrcRect lorsqu'elle est appliquée à DestRect.

Valeur : le rectangle source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Obtient ou définit un entier non signé de 32 bits qui spécifie un indice à associer au conteneur d'état graphique. L'indice DOIT être référencé par un enregistrement EmfPlusEndContainer ultérieur (section 2.3.7.3) pour fermer le conteneur d'état graphique.

Valeur : l'indice de la pile.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Obtient ou définit un entier non signé de 32 bits qui spécifie un indice à associer au conteneur d'état graphique. L'indice DOIT être référencé par un enregistrement EmfPlusEndContainer ultérieur (section 2.3.7.3) pour fermer le conteneur d'état graphique.

Valeur : l'indice de la pile.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

