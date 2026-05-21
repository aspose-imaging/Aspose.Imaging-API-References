---
title: "LimitMemoryException"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'exception de mémoire limitée."
type: docs
weight: 21
url: /fr/java/com.aspose.imaging.coreexceptions/limitmemoryexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Error, java.lang.VirtualMachineError, java.lang.OutOfMemoryError, com.aspose.ms.System.OutOfMemoryException
```
public class LimitMemoryException extends System.OutOfMemoryException
```

L'exception de mémoire limitée. Se produit lorsque l'utilisation de la mémoire doit être réduite.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LimitMemoryException(String message)](#LimitMemoryException-java.lang.String-) | Initialise une nouvelle instance de la classe `LimitMemoryException`. |
| [LimitMemoryException(String message, Throwable innerException)](#LimitMemoryException-java.lang.String-java.lang.Throwable-) | Initialise une nouvelle instance de la classe `LimitMemoryException`. |
| [LimitMemoryException(String message, long reduceMemoryFactor)](#LimitMemoryException-java.lang.String-long-) | Initialise une nouvelle instance de la classe `LimitMemoryException`. |
| [LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)](#LimitMemoryException-java.lang.String-java.lang.Throwable-int-) | Initialise une nouvelle instance de la classe `LimitMemoryException`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getReduceMemoryFactor()](#getReduceMemoryFactor--) | Obtient ou définit le facteur de réduction de mémoire. |
| [setReduceMemoryFactor(long value)](#setReduceMemoryFactor-long-) | Obtient ou définit le facteur de réduction de mémoire. |
### LimitMemoryException(String message) {#LimitMemoryException-java.lang.String-}
```
public LimitMemoryException(String message)
```


Initialise une nouvelle instance de la classe `LimitMemoryException`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message d'exception. |

### LimitMemoryException(String message, Throwable innerException) {#LimitMemoryException-java.lang.String-java.lang.Throwable-}
```
public LimitMemoryException(String message, Throwable innerException)
```


Initialise une nouvelle instance de la classe `LimitMemoryException`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message d'exception. |
| innerException | java.lang.Throwable | L'exception interne. |

### LimitMemoryException(String message, long reduceMemoryFactor) {#LimitMemoryException-java.lang.String-long-}
```
public LimitMemoryException(String message, long reduceMemoryFactor)
```


Initialise une nouvelle instance de la classe `LimitMemoryException`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message d'exception. |
| reduceMemoryFactor | long | Le facteur de réduction de mémoire. |

### LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor) {#LimitMemoryException-java.lang.String-java.lang.Throwable-int-}
```
public LimitMemoryException(String message, Throwable innerException, int reduceMemoryFactor)
```


Initialise une nouvelle instance de la classe `LimitMemoryException`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message d'exception. |
| innerException | java.lang.Throwable | L'exception interne. |
| reduceMemoryFactor | int | Le facteur de réduction de mémoire. |

### getReduceMemoryFactor() {#getReduceMemoryFactor--}
```
public long getReduceMemoryFactor()
```


Obtient ou définit le facteur de réduction de mémoire.

Valeur : Le facteur de réduction de mémoire.

**Returns:**
long
### setReduceMemoryFactor(long value) {#setReduceMemoryFactor-long-}
```
public void setReduceMemoryFactor(long value)
```


Obtient ou définit le facteur de réduction de mémoire.

Valeur : Le facteur de réduction de mémoire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

