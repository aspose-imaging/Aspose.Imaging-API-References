---
title: "Blend"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Définit un motif de mélange."
type: docs
weight: 12
url: /fr/java/com.aspose.imaging/blend/
---
**Inheritance:**
java.lang.Object
```
public final class Blend
```

Définit un motif de mélange. Cette classe ne peut pas être héritée.

L'utilisation typique de la classe blend consiste à définir un motif de mélange pour le pinceau. Ainsi, les propriétés de mélange doivent être initialisées avec soin. Les tableaux nuls ne sont pas autorisés. Le pinceau lèvera l'exception appropriée si les facteurs de mélange ou le tableau des positions sont vides ou si leur longueur n'est pas identique. S'il y a deux éléments ou plus dans le tableau des positions, le premier élément doit être 0 et le dernier doit être 1.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Blend()](#Blend--) | Initialise une nouvelle instance de la classe `Blend`. |
| [Blend(int count)](#Blend-int-) | Initialise une nouvelle instance de la classe `Blend` avec le nombre spécifié de facteurs et de positions. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFactors()](#getFactors--) | Obtient le tableau des facteurs de mélange pour le dégradé. |
| [setFactors(float[] value)](#setFactors-float---) | Définit le tableau des facteurs de mélange pour le dégradé. |
| [getPositions()](#getPositions--) | Obtient le tableau des positions de mélange pour le dégradé. |
| [setPositions(float[] value)](#setPositions-float---) | Définit le tableau des positions de mélange pour le dégradé. |
| [equals(Object obj)](#equals-java.lang.Object-) | Teste si l'objet spécifié est une classe `com.aspose.imaging.Blend` et est équivalente à cette classe `com.aspose.imaging.Blend`. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
### Blend() {#Blend--}
```
public Blend()
```


Initialise une nouvelle instance de la classe `Blend`. Le nombre d'éléments dans les tableaux des facteurs et des mélanges sera égal à 1.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


Initialise une nouvelle instance de la classe `Blend` avec le nombre spécifié de facteurs et de positions.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| count | int | Le nombre d'éléments dans les tableaux des facteurs et des positions. |

### getFactors() {#getFactors--}
```
public float[] getFactors()
```


Obtient le tableau des facteurs de mélange pour le dégradé.

**Returns:**
float[] - Le tableau des facteurs de mélange qui spécifient les pourcentages de la couleur de départ et de la couleur d'arrivée à utiliser à la position correspondante.
### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


Définit le tableau des facteurs de mélange pour le dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float[] | Le tableau des facteurs de mélange qui spécifient les pourcentages de la couleur de départ et de la couleur d'arrivée à utiliser à la position correspondante. |

### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Obtient le tableau des positions de mélange pour le dégradé.

**Returns:**
float[] - Le tableau des positions de mélange qui spécifient les pourcentages de distance le long de la ligne de dégradé.
### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


Définit le tableau des positions de mélange pour le dégradé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float[] | Le tableau des positions de mélange qui spécifient les pourcentages de distance le long de la ligne de dégradé. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Teste si l'objet spécifié est une classe `com.aspose.imaging.Blend` et est équivalente à cette classe `com.aspose.imaging.Blend`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à tester. |

**Returns:**
boolean - Vrai si `obj` est une classe `com.aspose.imaging.Blend` équivalente à cette classe `com.aspose.imaging.Blend` ; sinon, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance.

**Returns:**
int - Un code de hachage pour cette instance, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.
