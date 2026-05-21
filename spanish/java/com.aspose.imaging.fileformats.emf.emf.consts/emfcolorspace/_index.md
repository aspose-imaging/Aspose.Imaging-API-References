---
title: "EmfColorSpace"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración ColorSpace se usa para especificar cuándo activar y desactivar la prueba de color y cuándo eliminar transformaciones."
type: docs
weight: 15
url: /es/java/com.aspose.imaging.fileformats.emf.emf.consts/emfcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfColorSpace extends System.Enum
```

La enumeración ColorSpace se usa para especificar cuándo activar o desactivar la prueba de color y cuándo eliminar transformaciones.
## Campos

| Campo | Descripción |
| --- | --- |
| [CS_ENABLE](#CS-ENABLE) | Mapea los colores al gamut de color del dispositivo objetivo. |
| [CS_DISABLE](#CS-DISABLE) | Desactiva la prueba de color. |
| [CS_DELETE_TRANSFORM](#CS-DELETE-TRANSFORM) | Si la gestión de color está habilitada para el perfil objetivo, la desactiva y elimina la transformación concatenada. |
### CS_ENABLE {#CS-ENABLE}
```
public static final int CS_ENABLE
```


Mapea los colores al gamut de color del dispositivo objetivo. Esto habilita la prueba de color. Todos los comandos de dibujo posteriores al contexto del dispositivo de reproducción renderizarán los colores como aparecerían en el dispositivo objetivo.

### CS_DISABLE {#CS-DISABLE}
```
public static final int CS_DISABLE
```


Desactiva la prueba de color.

### CS_DELETE_TRANSFORM {#CS-DELETE-TRANSFORM}
```
public static final int CS_DELETE_TRANSFORM
```


Si la gestión de color está habilitada para el perfil objetivo, la desactiva y elimina la transformación concatenada.

