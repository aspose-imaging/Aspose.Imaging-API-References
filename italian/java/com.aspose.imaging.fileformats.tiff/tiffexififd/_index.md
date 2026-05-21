---
title: "TiffExifIfd"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La classe della directory dei file immagine TIFF Exif."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.tiff/tiffexififd/
---
**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

La classe della directory dei file immagine TIFF Exif.

Incapsula un puntatore all'Exif IFD. Interoperabilità, l'Exif IFD ha la stessa struttura di quella dell'IFD specificato nel TIFF. Tuttavia, normalmente non contiene dati immagine come nel caso del TIFF. Vedi http://www.exiv2.org/tags.html e http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html per maggiori dettagli.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | Inizializza una nuova istanza della classe `TiffExifIfd`. |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | Inizializza una nuova istanza della classe `TiffExifIfd`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [hasValue()](#hasValue--) | Ottiene un valore che indica se questa istanza ha un valore. |
| [getOffset()](#getOffset--) | Ottiene o imposta il puntatore all'EXIF IFD. |
| [setOffset(long value)](#setOffset-long-) | Ottiene o imposta il puntatore all'EXIF IFD. |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


Inizializza una nuova istanza della classe `TiffExifIfd`.

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


Inizializza una nuova istanza della classe `TiffExifIfd`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | ifdOffset | long | Un puntatore all'Exif IFD. |

Interoperabilità, l'Exif IFD ha la stessa struttura di quella dell'IFD specificato nel TIFF. Tuttavia, normalmente non contiene dati immagine come nel caso del TIFF. |

### hasValue() {#hasValue--}
```
public boolean hasValue()
```


Ottiene un valore che indica se questa istanza ha un valore.

**Returns:**
boolean - `true` se questa istanza ha valore; altrimenti, `false`.
### getOffset() {#getOffset--}
```
public long getOffset()
```


Ottiene o imposta il puntatore all'EXIF IFD.

**Returns:**
long - Il puntatore all'EXIF IFD.
### setOffset(long value) {#setOffset-long-}
```
public void setOffset(long value)
```


Ottiene o imposta il puntatore all'EXIF IFD.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | Il puntatore all'EXIF IFD. |

