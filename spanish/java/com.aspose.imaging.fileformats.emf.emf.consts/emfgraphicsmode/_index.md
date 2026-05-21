---
title: "EmfGraphicsMode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración GraphicsMode se usa para especificar cómo interpretar los datos de forma, como las coordenadas de rectángulos."
type: docs
weight: 24
url: /es/java/com.aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfGraphicsMode extends System.Enum
```

La enumeración GraphicsMode se usa para especificar cómo interpretar los datos de forma, como las coordenadas de rectángulos.
## Campos

| Campo | Descripción |
| --- | --- |
| [GM_COMPATIBLE](#GM-COMPATIBLE) | El texto TrueType MUST escribirse de izquierda a derecha y con la parte derecha hacia arriba, incluso si el resto de los gráficos están rotados alrededor del eje x o del eje y debido a la transformación world-to-device actual en el contexto del dispositivo de reproducción. |
| [GM_ADVANCED](#GM-ADVANCED) | La salida de texto TrueType MUST ajustarse completamente a la transformación world-to-device actual en el contexto del dispositivo de reproducción. |
### GM_COMPATIBLE {#GM-COMPATIBLE}
```
public static final int GM_COMPATIBLE
```


El texto TrueType MUST escribirse de izquierda a derecha y con la parte derecha hacia arriba, incluso si el resto de los gráficos están rotados alrededor del eje x o del eje y debido a la transformación world-to-device actual en el contexto del dispositivo de reproducción. Sólo la altura del texto SHOULD escalarse. Los arcos MUST dibujarse usando la dirección actual del arco en el contexto del dispositivo de reproducción, pero ellos MUST NOT respetar la transformación world-to-device actual, lo que podría requerir una rotación a lo largo del eje x o del eje y. La transformación world-to-device SHOULD modificarse solo cambiando las extensiones y orígenes de la ventana y del viewport, usando los registros EMR\_SETWINDOWEXTEX (sección 2.3.11.30) y EMR\_SETVIEWPORTEXTEX (sección 2.3.11.28), y los registros EMR\_SETWINDOWORGEX (sección 2.3.11.31) y EMR\_SETVIEWPORTORGEX (sección 2.3.11.30), respectivamente. bChanging la transformación directamente mediante los registros EMR\_MODIFYWORLDTRANSFORM (sección 2.3.12.1) o EMR\_SETWORLDTRANSFORM (sección 2.3.12.2) MAY NOT ser soportado. En el modo gráfico GM\_COMPATIBLE, los bordes inferior y derecho MUST excluirse cuando se dibujan rectángulos

### GM_ADVANCED {#GM-ADVANCED}
```
public static final int GM_ADVANCED
```


La salida de texto TrueType MUST ajustarse completamente a la transformación world-to-device actual en el contexto del dispositivo de reproducción. Los arcos MUST dibujarse en dirección antihoraria en el espacio mundial; sin embargo, tanto los puntos de control de los arcos como los propios arcos MUST respetar plenamente la transformación world-to-device actual en el contexto del dispositivo de reproducción. La transformación world-to-device MAY modificarse directamente usando los registros EMR\_MODIFYWORLDTRANSFORM o EMR\_SETWORLDTRANSFORM, o indirectamente cambiando las extensiones y orígenes de la ventana y del viewport, usando los registros EMR\_SETWINDOWEXTEX (sección 2.3.11.30) y EMR\_SETVIEWPORTEXTEX (sección 2.3.11.28), y los registros EMR\_SETWINDOWORGEX (sección 2.3.11.31) y EMR\_SETVIEWPORTORGEX (sección 2.3.11.30), respectivamente. En el modo gráfico GM\_ADVANCED, los bordes inferior y derecho MUST incluirse cuando se dibujan rectángulos.

