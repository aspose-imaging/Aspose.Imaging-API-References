---
title: "SampleRoundingMode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Définit une méthode selon laquelle une valeur n bits est convertie en une valeur 8 bits."
type: docs
weight: 17
url: /fr/java/com.aspose.imaging.fileformats.jpeg/sampleroundingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SampleRoundingMode extends System.Enum
```

Définit une méthode selon laquelle une valeur n bits est convertie en une valeur 8 bits.
## Champs

| Champ | Description |
| --- | --- |
| [Extrapolate](#Extrapolate) | Extrapoler une valeur de 8 bits pour l'adapter à n bits, où 1 < n < 8. |
| [Truncate](#Truncate) | Tronquer une valeur de 8 bits pour l'adapter à n bits, où 1 < n < 8. |
### Extrapolate {#Extrapolate}
```
public static final int Extrapolate
```


Extrapoler une valeur de 8 bits pour l'adapter à n bits, où 1 < n < 8. Le nombre de toutes les valeurs possibles de 8 bits est 1 << 8 = 256, de 0 à 255. Le nombre de toutes les valeurs possibles de n bits est 1 << n, de 0 à (1 << n) - 1. La valeur n‑bit la plus raisonnable Vn correspondant à une valeur de 8 bits V8 est égale à Vn = V8 >> (8 - n).

### Truncate {#Truncate}
```
public static final int Truncate
```


Tronquer une valeur de 8 bits pour l'adapter à n bits, où 1 < n < 8. Le nombre de toutes les valeurs possibles de n bits est 1 << n, de 0 à (1 << n) - 1. La valeur n‑bit la plus raisonnable Vn correspondant à une valeur de 8 bits V8 est égale à Vn = V8 & ((1 << n) - 1).

