---
title: "WmfGamutMappingIntent"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La enumeración GamutMappingIntent especifica la relación entre colores lógicos y físicos."
type: docs
weight: 20
url: /es/java/com.aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfGamutMappingIntent extends System.Enum
```

La enumeración GamutMappingIntent especifica la relación entre colores lógicos y físicos.
## Campos

| Campo | Descripción |
| --- | --- |
| [LCS_GM_ABS_COLORIMETRIC](#LCS-GM-ABS-COLORIMETRIC) | Especifica que el punto blanco DEBERÍA mantenerse. |
| [LCS_GM_BUSINESS](#LCS-GM-BUSINESS) | Especifica que la saturación DEBE mantenerse. |
| [LCS_GM_GRAPHICS](#LCS-GM-GRAPHICS) | Especifica que una coincidencia colorimétrica DEBE mantenerse. |
| [LCS_GM_IMAGES](#LCS-GM-IMAGES) | Especifica que el contraste DEBE mantenerse. |
### LCS_GM_ABS_COLORIMETRIC {#LCS-GM-ABS-COLORIMETRIC}
```
public static final int LCS_GM_ABS_COLORIMETRIC
```


Especifica que el punto blanco DEBE mantenerse. Normalmente se usa cuando los colores lógicos DEBEN coincidir con su color físico más cercano en el gamut de color de destino. Intención: Match ICC name: Absolute Colorimetric

### LCS_GM_BUSINESS {#LCS-GM-BUSINESS}
```
public static final int LCS_GM_BUSINESS
```


Especifica que la saturación DEBE mantenerse. Normalmente se usa para gráficos empresariales y otras situaciones en las que no se requiere tramado. Intención: Graphic ICC name: Saturation

### LCS_GM_GRAPHICS {#LCS-GM-GRAPHICS}
```
public static final int LCS_GM_GRAPHICS
```


Especifica que una coincidencia colorimétrica DEBE mantenerse. Normalmente se usa para diseños gráficos y colores con nombre. Intención: Proof ICC name: Relative Colorimetric

### LCS_GM_IMAGES {#LCS-GM-IMAGES}
```
public static final int LCS_GM_IMAGES
```


Especifica que el contraste DEBE mantenerse. Normalmente se usa para fotografías e imágenes naturales. Intención: Picture ICC name: Perceptual

