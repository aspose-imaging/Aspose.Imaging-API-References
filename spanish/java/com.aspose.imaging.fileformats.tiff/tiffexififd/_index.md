---
title: "TiffExifIfd"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La clase de directorio de archivo de imagen TIFF Exif."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.tiff/tiffexififd/
---
**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

La clase de directorio de archivo de imagen TIFF Exif.

Encapsula un puntero al IFD Exif. Interoperabilidad, el IFD Exif tiene la misma estructura que el IFD especificado en TIFF. Sin embargo, normalmente no contiene datos de imagen como ocurre en el caso de TIFF. Consulte http://www.exiv2.org/tags.html y http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html para obtener más detalles.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | Inicializa una nueva instancia de la clase `TiffExifIfd`. |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | Inicializa una nueva instancia de la clase `TiffExifIfd`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [hasValue()](#hasValue--) | Obtiene un valor que indica si esta instancia tiene valor. |
| [getOffset()](#getOffset--) | Obtiene o establece el puntero al IFD EXIF. |
| [setOffset(long value)](#setOffset-long-) | Obtiene o establece el puntero al IFD EXIF. |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


Inicializa una nueva instancia de la clase `TiffExifIfd`.

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


Inicializa una nueva instancia de la clase `TiffExifIfd`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | ifdOffset | long | Un puntero al IFD Exif. |

Interoperabilidad, el IFD Exif tiene la misma estructura que el IFD especificado en TIFF. Sin embargo, normalmente no contiene datos de imagen como ocurre en el caso de TIFF. |

### hasValue() {#hasValue--}
```
public boolean hasValue()
```


Obtiene un valor que indica si esta instancia tiene valor.

**Returns:**
boolean - `true` si esta instancia tiene valor; de lo contrario, `false`.
### getOffset() {#getOffset--}
```
public long getOffset()
```


Obtiene o establece el puntero al IFD EXIF.

**Returns:**
long - El puntero al IFD EXIF.
### setOffset(long value) {#setOffset-long-}
```
public void setOffset(long value)
```


Obtiene o establece el puntero al IFD EXIF.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long | El puntero al IFD EXIF. |

