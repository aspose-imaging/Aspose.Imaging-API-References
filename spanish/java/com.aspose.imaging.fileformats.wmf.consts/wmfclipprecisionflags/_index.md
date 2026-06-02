---
title: "WmfClipPrecisionFlags"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Los indicadores ClipPrecision especifican la precisión de recorte, lo que define cómo recortar caracteres que están parcialmente fuera de una región de recorte."
type: docs
weight: 14
url: /es/java/com.aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfClipPrecisionFlags extends System.Enum
```

Los indicadores ClipPrecision especifican la precisión de recorte, lo que define cómo recortar caracteres que están parcialmente fuera de una región de recorte. Estos indicadores pueden combinarse para especificar múltiples opciones.
## Campos

| Campo | Descripción |
| --- | --- |
| [Default](#Default) | Especifica que se DEBE usar el recorte predeterminado. |
| [Character](#Character) | Este valor NO DEBERÍA ser utilizado. |
| [Stroke](#Stroke) | Este valor PUEDE ser devuelto al enumerar fuentes rasterizadas, TrueType y vectoriales. |
| [LhAngles](#LhAngles) | Este valor se usa para controlar la rotación de fuentes, de la siguiente manera: - Si está establecido, la rotación de todas las fuentes DEBERÍA determinarse por la orientación del sistema de coordenadas; es decir, si la orientación es zurda o diestra. |
| [TtAlways](#TtAlways) | Este valor NO DEBERÍA [34] ser utilizado. |
| [DfaDisable](#DfaDisable) | Este valor especifica que la asociación de fuentes DEBERÍA [35] desactivarse. |
| [Embedded](#Embedded) | Este valor especifica que la incrustación de fuentes DEBE usarse para renderizar el contenido del documento; las fuentes incrustadas son de solo lectura. |
### Default {#Default}
```
public static final byte Default
```


Especifica que se DEBE usar el recorte predeterminado.

### Character {#Character}
```
public static final byte Character
```


Este valor NO DEBERÍA ser utilizado.

### Stroke {#Stroke}
```
public static final byte Stroke
```


Este valor PUEDE ser devuelto al enumerar fuentes rasterizadas, TrueType y vectoriales. [33] (Windows NT 3.1, Windows NT 3.5, Windows NT 3.51, Windows NT 4.0, Windows 2000 y Windows XP: este valor siempre se devuelve al enumerar fuentes.)

### LhAngles {#LhAngles}
```
public static final byte LhAngles
```


Este valor se usa para controlar la rotación de fuentes, de la siguiente manera: - Si está establecido, la rotación de todas las fuentes DEBERÍA determinarse por la orientación del sistema de coordenadas; es decir, si la orientación es zurda o diestra. - Si está despejado, las fuentes del dispositivo DEBERÍAN rotar en sentido antihorario, pero la rotación de otras fuentes DEBERÍA determinarse por la orientación del sistema de coordenadas.

### TtAlways {#TtAlways}
```
public static final byte TtAlways
```


Este valor NO DEBERÍA [34] ser utilizado. [34] Este valor se ignora en las siguientes versiones de Windows: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### DfaDisable {#DfaDisable}
```
public static final byte DfaDisable
```


Este valor especifica que la asociación de fuentes DEBERÍA [35] desactivarse. [35] Este valor no es compatible en Windows 95, Windows 98 y Windows Millennium Edition. La asociación de fuentes está desactivada en Windows 2000, Windows XP y Windows Server 2003. Este valor se ignora en estas versiones de Windows: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### Embedded {#Embedded}
```
public static final byte Embedded
```


Este valor especifica que la incrustación de fuentes DEBE usarse para renderizar el contenido del documento; las fuentes incrustadas son de solo lectura.

