---
title: "EmfPlusDriverStringOptionsFlags"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Los indicadores DriverStringOptions especifican propiedades del posicionamiento y renderizado del texto gráfico."
type: docs
weight: 21
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusDriverStringOptionsFlags extends System.Enum
```

Los indicadores DriverStringOptions especifican propiedades del posicionamiento y renderizado de texto gráfico. Estos indicadores pueden combinarse para especificar múltiples opciones.

--------------------

La salida de texto gráfico se especifica en los registros [EmfPlusDrawDriverString](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring)
## Campos

| Campo | Descripción |
| --- | --- |
| [DriverStringOptionsCmapLookup](#DriverStringOptionsCmapLookup) | Si está establecido, las posiciones de los glifos de caracteres DEBERÍAN especificarse en una tabla de búsqueda de mapa de caracteres. |
| [DriverStringOptionsVertical](#DriverStringOptionsVertical) | Si está establecido, la cadena DEBERÍA renderizarse verticalmente. |
| [DriverStringOptionsRealizedAdvance](#DriverStringOptionsRealizedAdvance) | Si está establecido, las posiciones de los glifos de caracteres DEBERÍAN calcularse en relación con la posición del primer glifo. |
| [DriverStringOptionsLimitSubpixel](#DriverStringOptionsLimitSubpixel) | Si está establecido, se DEBERÍA usar menos memoria para almacenar en caché glifos suavizados, lo que produce un renderizado de texto de menor calidad. |
### DriverStringOptionsCmapLookup {#DriverStringOptionsCmapLookup}
```
public static final int DriverStringOptionsCmapLookup
```


Si está establecido, las posiciones de los glifos de caracteres DEBERÍAN especificarse en una tabla de búsqueda de mapa de caracteres. Si está desactivado, las posiciones de los glifos DEBERÍAN obtenerse de una matriz de coordenadas.

### DriverStringOptionsVertical {#DriverStringOptionsVertical}
```
public static final int DriverStringOptionsVertical
```


Si está establecido, la cadena DEBERÍA renderizarse verticalmente. Si está desactivado, la cadena DEBERÍA renderizarse horizontalmente.

### DriverStringOptionsRealizedAdvance {#DriverStringOptionsRealizedAdvance}
```
public static final int DriverStringOptionsRealizedAdvance
```


Si está establecido, las posiciones de los glifos de caracteres DEBERÍAN calcularse en relación con la posición del primer glifo. Si está desactivado, las posiciones de los glifos DEBERÍAN obtenerse de una matriz de coordenadas.

### DriverStringOptionsLimitSubpixel {#DriverStringOptionsLimitSubpixel}
```
public static final int DriverStringOptionsLimitSubpixel
```


Si está establecido, se DEBERÍA usar menos memoria para almacenar en caché glifos suavizados, lo que produce un renderizado de texto de menor calidad. Si está desactivado, se DEBERÍA usar más memoria, lo que produce un renderizado de texto de mayor calidad.

