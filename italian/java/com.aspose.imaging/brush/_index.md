---
title: "Brush"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La classe base del pennello."
type: docs
weight: 13
url: /it/java/com.aspose.imaging/brush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class Brush extends DisposableObject
```

La classe base del pennello.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Brush()](#Brush--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getOpacity()](#getOpacity--) | Restituisce l'opacità del pennello. |
| [setOpacity(float value)](#setOpacity-float-) | Imposta l'opacità del pennello. |
| [deepClone()](#deepClone--) | Crea una nuova clone profonda dell'`Brush` corrente. |
| [equals(Object o)](#equals-java.lang.Object-) | Verifica se gli oggetti sono uguali. |
| [hashCode()](#hashCode--) | Ottieni il codice hash dell'oggetto corrente. |
### Brush() {#Brush--}
```
public Brush()
```


### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Restituisce l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che il pennello è completamente visibile, un valore di 1 indica che il pennello è completamente opaco.

**Returns:**
float - Il valore di opacità del pennello.
### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Imposta l'opacità del pennello. Il valore deve essere compreso tra 0 e 1. Un valore di 0 indica che il pennello è completamente visibile, un valore di 1 indica che il pennello è completamente opaco.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Il valore di opacità del pennello. |

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Crea una nuova clone profonda dell'`Brush` corrente.

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A new `Brush` which is the deep clone of this `Brush` instance.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Verifica se gli oggetti sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| o | java.lang.Object | L'altro oggetto. |

**Returns:**
boolean - Il risultato del confronto di uguaglianza.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ottieni il codice hash dell'oggetto corrente.

**Returns:**
int - Il codice hash.
