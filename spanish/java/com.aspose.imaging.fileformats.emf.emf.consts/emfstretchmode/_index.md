---
title: "EmfStretchMode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración StretchMode se usa para especificar cómo se añaden o eliminan datos de color de los mapas de bits que se estiran o comprimen."
type: docs
weight: 43
url: /es/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStretchMode extends System.Enum
```

La enumeración StretchMode se usa para especificar cómo se añaden o eliminan datos de color de los mapas de bits que se estiran o comprimen.
## Campos

| Campo | Descripción |
| --- | --- |
| [STRETCH_ANDSCANS](#STRETCH-ANDSCANS) | Realiza una operación Boolean AND usando los valores de color de los píxeles eliminados y existentes. |
| [STRETCH_ORSCANS](#STRETCH-ORSCANS) | Realiza una operación Boolean OR usando los valores de color de los píxeles eliminados y existentes. |
| [STRETCH_DELETESCANS](#STRETCH-DELETESCANS) | Elimina los píxeles. |
| [STRETCH_HALFTONE](#STRETCH-HALFTONE) | Mapea los píxeles del rectángulo de origen a bloques de píxeles en el rectángulo de destino. |
### STRETCH_ANDSCANS {#STRETCH-ANDSCANS}
```
public static final int STRETCH_ANDSCANS
```


Realiza una operación Boolean AND usando los valores de color de los píxeles eliminados y existentes. Si el mapa de bits es monocromo, este modo conserva los píxeles negros a expensas de los píxeles blancos.

### STRETCH_ORSCANS {#STRETCH-ORSCANS}
```
public static final int STRETCH_ORSCANS
```


Realiza una operación Boolean OR usando los valores de color de los píxeles eliminados y existentes. Si el mapa de bits es monocromo, este modo conserva los píxeles blancos a expensas de los píxeles negros.

### STRETCH_DELETESCANS {#STRETCH-DELETESCANS}
```
public static final int STRETCH_DELETESCANS
```


Elimina los píxeles. Este modo elimina todas las líneas de píxeles eliminadas sin intentar conservar su información.

### STRETCH_HALFTONE {#STRETCH-HALFTONE}
```
public static final int STRETCH_HALFTONE
```


Mapea los píxeles del rectángulo de origen a bloques de píxeles en el rectángulo de destino. El color promedio del bloque de píxeles de destino aproxima el color de los píxeles de origen.

