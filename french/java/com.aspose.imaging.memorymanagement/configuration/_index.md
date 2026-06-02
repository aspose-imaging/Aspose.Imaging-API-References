---
title: "Configuration"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "La configuration globale de la gestion de la mémoire"
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.memorymanagement/configuration/
---
**Inheritance:**
java.lang.Object
```
public final class Configuration
```

La configuration globale de la gestion de la mémoire
## Méthodes

| Méthode | Description |
| --- | --- |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtient l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Définit l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
### getBufferSizeHint() {#getBufferSizeHint--}
```
public static int getBufferSizeHint()
```


Obtient l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes.

Valeur : L’indice de taille du tampon, en mégaoctets. Une valeur non positive signifie aucune limitation de mémoire pour les tampons internes

**Returns:**
int - l’indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public static void setBufferSizeHint(int value)
```


Définit l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes.

Valeur : L’indice de taille du tampon, en mégaoctets. Une valeur non positive signifie aucune limitation de mémoire pour les tampons internes

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | l’indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |

