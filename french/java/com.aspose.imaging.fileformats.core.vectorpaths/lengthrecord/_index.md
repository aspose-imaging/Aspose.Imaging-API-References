---
title: "LengthRecord"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Classe d'enregistrement de longueur de sous-chemin"
type: docs
weight: 13
url: /fr/java/com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.core.vectorpaths.VectorPathRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/vectorpathrecord)
```
public class LengthRecord extends VectorPathRecord
```

Classe d'enregistrement de longueur de sous-chemin
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LengthRecord(byte[] data)](#LengthRecord-byte---) | Initialise une nouvelle instance de la classe [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord). |
| [LengthRecord()](#LengthRecord--) | Initialise une nouvelle instance de la classe [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [isClosed()](#isClosed--) | Obtient une valeur indiquant si cette instance est fermée. |
| [setClosed(boolean value)](#setClosed-boolean-) | Définit une valeur indiquant si cette instance est fermée. |
| [isOpen()](#isOpen--) | Obtient une valeur indiquant si cette instance est ouverte. |
| [setOpen(boolean value)](#setOpen-boolean-) | Définit une valeur indiquant si cette instance est ouverte. |
| [getRecordCount()](#getRecordCount--) | Obtient le nombre d'enregistrements. |
| [setRecordCount(int value)](#setRecordCount-int-) | Définit le nombre d'enregistrements. |
| [getType()](#getType--) | Obtient le type. |
| [getBezierKnotRecordsCount()](#getBezierKnotRecordsCount--) | Obtient le nombre d'enregistrements de nœuds de Bézier. |
| [setBezierKnotRecordsCount(int value)](#setBezierKnotRecordsCount-int-) | Définit le nombre d'enregistrements de nœuds de Bézier. |
| [getPathOperations()](#getPathOperations--) | Obtient les opérations de chemin. |
| [setPathOperations(int value)](#setPathOperations-int-) | Définit les opérations de chemin. |
| [getShapeIndex()](#getShapeIndex--) | Obtient l'index de la forme de chemin actuelle dans le calque. |
| [setShapeIndex(int value)](#setShapeIndex-int-) | Définit l'index de la forme de chemin actuelle dans le calque. |
### LengthRecord(byte[] data) {#LengthRecord-byte---}
```
public LengthRecord(byte[] data)
```


Initialise une nouvelle instance de la classe [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données de l'enregistrement. |

### LengthRecord() {#LengthRecord--}
```
public LengthRecord()
```


Initialise une nouvelle instance de la classe [LengthRecord](../../com.aspose.imaging.fileformats.core.vectorpaths/lengthrecord).

### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


Obtient une valeur indiquant si cette instance est fermée.

Valeur : `true` si cette instance est fermée ; sinon, `false`.

**Returns:**
boolean - une valeur indiquant si cette instance est fermée.
### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


Définit une valeur indiquant si cette instance est fermée.

Valeur : `true` si cette instance est fermée ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si cette instance est fermée. |

### isOpen() {#isOpen--}
```
public final boolean isOpen()
```


Obtient une valeur indiquant si cette instance est ouverte.

Valeur : `true` si cette instance est ouverte ; sinon, `false`.

**Returns:**
boolean - une valeur indiquant si cette instance est ouverte.
### setOpen(boolean value) {#setOpen-boolean-}
```
public final void setOpen(boolean value)
```


Définit une valeur indiquant si cette instance est ouverte.

Valeur : `true` si cette instance est ouverte ; sinon, `false`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | une valeur indiquant si cette instance est ouverte. |

### getRecordCount() {#getRecordCount--}
```
public final int getRecordCount()
```


Obtient le nombre d'enregistrements.

Valeur : le nombre d'enregistrements.

**Returns:**
int - le nombre d'enregistrements.
### setRecordCount(int value) {#setRecordCount-int-}
```
public final void setRecordCount(int value)
```


Définit le nombre d'enregistrements.

Valeur : le nombre d'enregistrements.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le nombre d'enregistrements. |

### getType() {#getType--}
```
public short getType()
```


Obtient le type.

Valeur: le type.

**Returns:**
short - le type.
### getBezierKnotRecordsCount() {#getBezierKnotRecordsCount--}
```
public final int getBezierKnotRecordsCount()
```


Obtient le nombre d'enregistrements de nœuds de Bézier.

**Returns:**
int - le nombre d'enregistrements de nœuds de Bézier.
### setBezierKnotRecordsCount(int value) {#setBezierKnotRecordsCount-int-}
```
public final void setBezierKnotRecordsCount(int value)
```


Définit le nombre d'enregistrements de nœuds de Bézier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | le nombre d'enregistrements de nœuds de Bézier. |

### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


Obtient les opérations de chemin.

**Returns:**
int - les opérations de chemin.
### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


Définit les opérations de chemin.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | les opérations de chemin. |

### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


Obtient l'index de la forme de chemin actuelle dans le calque.

**Returns:**
int - l'index de la forme de chemin actuelle dans le calque.
### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


Définit l'index de la forme de chemin actuelle dans le calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | l'index de la forme de chemin actuelle dans le calque. |

