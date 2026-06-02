---
title: "Brush"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La classe de pinceau de base."
type: docs
weight: 13
url: /fr/java/com.aspose.imaging/brush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class Brush extends DisposableObject
```

La classe de pinceau de base.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Brush()](#Brush--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOpacity()](#getOpacity--) | Obtient l'opacité du pinceau. |
| [setOpacity(float value)](#setOpacity-float-) | Définit l'opacité du pinceau. |
| [deepClone()](#deepClone--) | Crée un nouveau clone profond du `Brush` actuel. |
| [equals(Object o)](#equals-java.lang.Object-) | Vérifie si les objets sont égaux. |
| [hashCode()](#hashCode--) | Obtient le code de hachage de l'objet actuel. |
### Brush() {#Brush--}
```
public Brush()
```


### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Obtient l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est totalement opaque.

**Returns:**
float - La valeur d'opacité du pinceau.
### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Définit l'opacité du pinceau. La valeur doit être comprise entre 0 et 1. Une valeur de 0 signifie que le pinceau est entièrement visible, une valeur de 1 signifie que le pinceau est totalement opaque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | La valeur d'opacité du pinceau. |

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Crée un nouveau clone profond du `Brush` actuel.

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A new `Brush` which is the deep clone of this `Brush` instance.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Vérifie si les objets sont égaux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | L'autre objet. |

**Returns:**
boolean - Le résultat de la comparaison d'égalité.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage de l'objet actuel.

**Returns:**
int - Le code de hachage.
