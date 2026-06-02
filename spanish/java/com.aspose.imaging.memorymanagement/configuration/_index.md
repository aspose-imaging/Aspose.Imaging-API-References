---
title: "Configuración"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La configuración global de gestión de memoria"
type: docs
weight: 10
url: /es/java/com.aspose.imaging.memorymanagement/configuration/
---
**Inheritance:**
java.lang.Object
```
public final class Configuration
```

La configuración global de gestión de memoria
## Métodos

| Método | Descripción |
| --- | --- |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtiene la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos. |
### getBufferSizeHint() {#getBufferSizeHint--}
```
public static int getBufferSizeHint()
```


Obtiene la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos.

Valor: La sugerencia de tamaño del búfer, en megabytes. Un valor no positivo significa que no hay limitación de memoria para los búferes internos

**Returns:**
int - la sugerencia de tamaño del búfer que define el tamaño máximo permitido para todos los búferes internos.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public static void setBufferSizeHint(int value)
```


Establece la sugerencia de tamaño del búfer, que define el tamaño máximo permitido para todos los búferes internos.

Valor: La sugerencia de tamaño del búfer, en megabytes. Un valor no positivo significa que no hay limitación de memoria para los búferes internos

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | la sugerencia de tamaño del búfer que define el tamaño máximo permitido para todos los búferes internos. |

