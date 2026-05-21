---
title: "EmfPlusSetAntiAliasMode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusSetAntiAliasMode especifica el modo de antialiasing para la salida de texto."
type: docs
weight: 54
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetAntiAliasMode extends EmfPlusPropertyRecordType
```

El registro EmfPlusSetAntiAliasMode especifica el modo de antialiasing para la salida de texto.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusSetAntiAliasMode(EmfPlusRecord source)](#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusSetAntiAliasMode`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | Obtiene o establece el modo de suavizado. |
| [setSmoothingMode(byte value)](#setSmoothingMode-byte-) | Obtiene o establece el modo de suavizado. |
| [getAntiAliasing()](#getAntiAliasing--) | Obtiene o establece un valor que indica si [anti aliasing]. |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | Obtiene o establece un valor que indica si [anti aliasing]. |
### EmfPlusSetAntiAliasMode(EmfPlusRecord source) {#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetAntiAliasMode(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusSetAntiAliasMode`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### getSmoothingMode() {#getSmoothingMode--}
```
public byte getSmoothingMode()
```


Obtiene o establece el modo de suavizado. (7 bits): El valor del modo de suavizado, de la enumeración SmoothingMode (sección 2.1.1.28).

Valor: El modo de suavizado.

**Returns:**
byte
### setSmoothingMode(byte value) {#setSmoothingMode-byte-}
```
public void setSmoothingMode(byte value)
```


Obtiene o establece el modo de suavizado. (7 bits): El valor del modo de suavizado, de la enumeración SmoothingMode (sección 2.1.1.28).

Valor: El modo de suavizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getAntiAliasing() {#getAntiAliasing--}
```
public boolean getAntiAliasing()
```


Obtiene o establece un valor que indica si [anti aliasing]. Si está activado, se DEBE realizar anti-aliasing. Si está desactivado, NO SE DEBE realizar anti-aliasing.

Valor: `true` si [anti aliasing]; de lo contrario, `false`.

**Returns:**
boolean
### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public void setAntiAliasing(boolean value)
```


Obtiene o establece un valor que indica si [anti aliasing]. Si está activado, se DEBE realizar anti-aliasing. Si está desactivado, NO SE DEBE realizar anti-aliasing.

Valor: `true` si [anti aliasing]; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

