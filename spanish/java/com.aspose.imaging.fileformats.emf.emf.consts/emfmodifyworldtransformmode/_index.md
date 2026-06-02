---
title: "EmfModifyWorldTransformMode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración ModifyWorldTransformMode define modos para usar datos de transformación especificados y modificar la transformación de espacio mundial a espacio de página que está actualmente definida en el contexto del dispositivo de reproducción."
type: docs
weight: 33
url: /es/java/com.aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfModifyWorldTransformMode extends System.Enum
```

La enumeración ModifyWorldTransformMode define modos para usar datos de transformación especificados y modificar la transformación de espacio mundial a espacio de página que está actualmente definida en el contexto del dispositivo de reproducción.
## Campos

| Campo | Descripción |
| --- | --- |
| [MWT_IDENTITY](#MWT-IDENTITY) | Restablecer la transformación actual usando la matriz identidad. |
| [MWT_LEFTMULTIPLY](#MWT-LEFTMULTIPLY) | Multiplicar la transformación actual. |
| [MWT_RIGHTMULTIPLY](#MWT-RIGHTMULTIPLY) | Multiplicar la transformación actual. |
| [MWT_SET](#MWT-SET) | Ejecutar la función de un registro EMR\_SETWORLDTRANSFORM (sección 2.3.12.2). |
### MWT_IDENTITY {#MWT-IDENTITY}
```
public static final int MWT_IDENTITY
```


Restablecer la transformación actual usando la matriz de identidad. En este modo, los datos de transformación especificados se ignoran

### MWT_LEFTMULTIPLY {#MWT-LEFTMULTIPLY}
```
public static final int MWT_LEFTMULTIPLY
```


Multiplicar la transformación actual. En este modo, los datos de transformación especificados son el multiplicando izquierdo, y la transformación que está actualmente definida en el contexto del dispositivo de reproducción es el multiplicando derecho

### MWT_RIGHTMULTIPLY {#MWT-RIGHTMULTIPLY}
```
public static final int MWT_RIGHTMULTIPLY
```


Multiplicar la transformación actual. En este modo, los datos de transformación especificados son el multiplicando derecho, y la transformación que está actualmente definida en el contexto del dispositivo de reproducción es el multiplicando izquierdo

### MWT_SET {#MWT-SET}
```
public static final int MWT_SET
```


Ejecutar la función de un registro EMR\_SETWORLDTRANSFORM (sección 2.3.12.2).

