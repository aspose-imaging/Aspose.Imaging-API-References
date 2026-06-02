---
title: "LineJoin"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Especifica cómo unir segmentos consecutivos de línea o curva en una subruta de figura contenida en un objeto GraphicsPath."
type: docs
weight: 69
url: /es/java/com.aspose.imaging/linejoin/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class LineJoin extends System.Enum
```

Especifica cómo unir segmentos consecutivos de línea o curva en una figura (subruta) contenida en un objeto `GraphicsPath`.
## Campos

| Campo | Descripción |
| --- | --- |
| [Miter](#Miter) | Especifica una unión en inglete. |
| [Bevel](#Bevel) | Especifica una unión biselada. |
| [Round](#Round) | Especifica una unión circular. |
| [MiterClipped](#MiterClipped) | Especifica una unión en inglete. |
### Miter {#Miter}
```
public static final int Miter
```


Especifica una unión en inglete. Esto produce una esquina aguda o una esquina recortada, dependiendo de si la longitud del inglete supera el límite del inglete.

### Bevel {#Bevel}
```
public static final int Bevel
```


Especifica una unión biselada. Esto produce una esquina diagonal.

### Round {#Round}
```
public static final int Round
```


Especifica una unión circular. Esto produce un arco circular y suave entre las líneas.

### MiterClipped {#MiterClipped}
```
public static final int MiterClipped
```


Especifica una unión en inglete. Esto produce una esquina aguda o una esquina biselada, dependiendo de si la longitud del inglete supera el límite del inglete.

