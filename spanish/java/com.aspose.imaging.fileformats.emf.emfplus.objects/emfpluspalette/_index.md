---
title: "EmfPlusPalette"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusPalette especifica los colores que componen una paleta."
type: docs
weight: 57
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPalette extends EmfPlusStructureObjectType
```

El objeto EmfPlusPalette especifica los colores que componen una paleta.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusPalette()](#EmfPlusPalette--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getPaletteStyleFlags()](#getPaletteStyleFlags--) | Obtiene o establece los indicadores de estilo de la paleta. |
| [setPaletteStyleFlags(int value)](#setPaletteStyleFlags-int-) | Obtiene o establece los indicadores de estilo de la paleta. |
| [getArgb32Entries()](#getArgb32Entries--) | Obtiene o establece las entradas de la paleta. |
| [setArgb32Entries(int[] value)](#setArgb32Entries-int---) | Obtiene o establece las entradas de la paleta. |
### EmfPlusPalette() {#EmfPlusPalette--}
```
public EmfPlusPalette()
```


### getPaletteStyleFlags() {#getPaletteStyleFlags--}
```
public int getPaletteStyleFlags()
```


Obtiene o establece los indicadores de estilo de la paleta.

Valor: PaletteStyleFlags (4 bytes): Un entero sin signo de 32 bits que especifica los atributos de los datos en la paleta. Este valor DEBE estar compuesto por los indicadores `EmfPlusPaletteStyleFlags`.

**Returns:**
int
### setPaletteStyleFlags(int value) {#setPaletteStyleFlags-int-}
```
public void setPaletteStyleFlags(int value)
```


Obtiene o establece los indicadores de estilo de la paleta.

Valor: PaletteStyleFlags (4 bytes): Un entero sin signo de 32 bits que especifica los atributos de los datos en la paleta. Este valor DEBE estar compuesto por los indicadores `EmfPlusPaletteStyleFlags`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getArgb32Entries() {#getArgb32Entries--}
```
public int[] getArgb32Entries()
```


Obtiene o establece las entradas de la paleta.

Valor: PaletteEntries (variable): Una matriz de PaletteCount objetos ARGB de 32 bits que especifican los datos en la paleta.

**Returns:**
int[] - La copia de las entradas de la paleta.
### setArgb32Entries(int[] value) {#setArgb32Entries-int---}
```
public void setArgb32Entries(int[] value)
```


Obtiene o establece las entradas de la paleta.

Valor: PaletteEntries (variable): Una matriz de PaletteCount objetos ARGB de 32 bits que especifican los datos en la paleta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int[] |  |

