---
title: "IntRange"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Classe représentant une séquence d'éléments"
type: docs
weight: 64
url: /fr/java/com.aspose.imaging/intrange/
---
**Inheritance:**
java.lang.Object
```
public class IntRange
```

Classe représentant une séquence d'éléments
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [IntRange(int start, int count)](#IntRange-int-int-) | Initialise une nouvelle instance de la classe `IntRange`. |
| [IntRange(int start, int count, int delta)](#IntRange-int-int-int-) | Initialise une nouvelle instance de la classe `IntRange`. |
| [IntRange(int[] range)](#IntRange-int---) | Initialise une nouvelle instance de la classe `IntRange`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getRange()](#getRange--) | Obtient la plage. |
| [setRange(int[] value)](#setRange-int---) | Définit la plage. |
| [getArrayOneItemFromIndex(int index)](#getArrayOneItemFromIndex-int-) | Renvoie un tableau d'un élément à partir de l'index spécifié |
| [getRange(int start, int count, int delta)](#getRange-int-int-int-) | Obtient la plage de comptage des éléments int commençant à start |
### IntRange(int start, int count) {#IntRange-int-int-}
```
public IntRange(int start, int count)
```


Initialise une nouvelle instance de la classe `IntRange`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| start | int | Le début. |
| count | int | Le nombre. |

### IntRange(int start, int count, int delta) {#IntRange-int-int-int-}
```
public IntRange(int start, int count, int delta)
```


Initialise une nouvelle instance de la classe `IntRange`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| start | int | Le début. |
| count | int | Le nombre. |
| delta | int | Le delta. |

### IntRange(int[] range) {#IntRange-int---}
```
public IntRange(int[] range)
```


Initialise une nouvelle instance de la classe `IntRange`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| range | int[] | La plage. |

### getRange() {#getRange--}
```
public int[] getRange()
```


Obtient la plage.

**Returns:**
int[] - La plage.
### setRange(int[] value) {#setRange-int---}
```
public void setRange(int[] value)
```


Définit la plage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int[] | La plage. |

### getArrayOneItemFromIndex(int index) {#getArrayOneItemFromIndex-int-}
```
public int[] getArrayOneItemFromIndex(int index)
```


Renvoie un tableau d'un élément à partir de l'index spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index de la plage. |

**Returns:**
int[] - Le tableau de `System.Int32`
### getRange(int start, int count, int delta) {#getRange-int-int-int-}
```
public static int[] getRange(int start, int count, int delta)
```


Obtient la plage de comptage des éléments int commençant à start

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| start | int | Le début. |
| count | int | Le nombre. |
| delta | int | Le delta. |

**Returns:**
int[] - Tableau d'éléments
