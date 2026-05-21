---
title: "EmfPlusPathPointFlags"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Un entero sin signo de 32 bits que especifica cómo interpretar los puntos y los tipos de punto asociados que están definidos por este objeto."
type: docs
weight: 38
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPathPointFlags extends System.Enum
```

Un entero sin signo de 32 bits que especifica cómo interpretar los puntos y los tipos de punto asociados que define este objeto. C (1 bit): Si está activado, la matriz PathPoints especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas enteras de 16 bits. Si está desactivado, la matriz PathPoints especifica ubicaciones absolutas en el espacio de coordenadas con coordenadas de punto flotante de 32 bits. Nota: Si el indicador P (abajo) está activado, este indicador PUEDE estar desactivado y DEBE ser ignorado. R (1 bit): Si está activado, los tipos de punto en la matriz PathPointTypes son especificados por objetos EmfPlusPathPointTypeRle (sección 2.2.2.32), que utilizan compresión de codificación por longitud de ejecución (RLE), y/o por objetos EmfPlusPathPointType (sección 2.2.2.31). Consulte la sección 3.1.6 de [MS-WMF] para más información sobre la compresión RLE. Si está desactivado, los tipos de punto en la matriz PathPointTypes son especificados por objetos EmfPlusPathPointType. P (1 bit): Si está activado, cada elemento de la matriz PathPoints especifica una ubicación en el espacio de coordenadas que es relativa a la ubicación especificada por el elemento anterior en la matriz. En el caso del primer elemento de PathPoints, se asume una ubicación previa en las coordenadas (0,0). Si está desactivado, cada elemento de la matriz PathPoints especifica una ubicación absoluta.
## Campos

| Campo | Descripción |
| --- | --- |
| [C](#C) | El indicador c |
| [R](#R) | El indicador r |
| [P](#P) | El indicador p |
### C {#C}
```
public static final short C
```


El indicador c

### R {#R}
```
public static final short R
```


El indicador r

### P {#P}
```
public static final short P
```


El indicador p

