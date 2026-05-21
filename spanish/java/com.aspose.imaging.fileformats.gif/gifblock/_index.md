---
title: "GifBlock"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La implementación predeterminada del bloque gif."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.gif/gifblock/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock)
```
public abstract class GifBlock implements IGifBlock
```

La implementación predeterminada del bloque gif.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [GifBlock()](#GifBlock--) |  |
## Campos

| Campo | Descripción |
| --- | --- |
| [EXTENSION_INTRODUCER](#EXTENSION-INTRODUCER) | Introducción de extensión. |
## Métodos

| Método | Descripción |
| --- | --- |
| [isChanged()](#isChanged--) | Obtiene o establece un valor que indica si el bloque ha cambiado y requiere guardado. |
| [setChanged(boolean value)](#setChanged-boolean-) | Obtiene o establece un valor que indica si el bloque ha cambiado y requiere guardado. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Guarda el bloque en el flujo especificado. |
### GifBlock() {#GifBlock--}
```
public GifBlock()
```


### EXTENSION_INTRODUCER {#EXTENSION-INTRODUCER}
```
public static final byte EXTENSION_INTRODUCER
```


Introducción de extensión.

### isChanged() {#isChanged--}
```
public boolean isChanged()
```


Obtiene o establece un valor que indica si el bloque ha cambiado y requiere guardado.

Valor: `true` si el bloque ha cambiado; de lo contrario, `false`.

**Returns:**
boolean
### setChanged(boolean value) {#setChanged-boolean-}
```
public void setChanged(boolean value)
```


Obtiene o establece un valor que indica si el bloque ha cambiado y requiere guardado.

Valor: `true` si el bloque ha cambiado; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Guarda el bloque en el flujo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | java.io.OutputStream | El flujo donde guardar los datos. |

