---
title: "TiffDoubleType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il tipo TIFF double."
type: docs
weight: 13
url: /it/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffdoubletype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffDoubleType extends TiffCommonArrayType
```

Il tipo TIFF double.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffDoubleType(int tagId)](#TiffDoubleType-int-) | Inizializza una nuova istanza della classe `TiffDoubleType`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getValues()](#getValues--) | Ottiene i valori. |
| [setValues(double[] value)](#setValues-double---) | Imposta i valori. |
| [getValuesContainer()](#getValuesContainer--) | Ottiene il contenitore dei valori. |
| [getTagType()](#getTagType--) | Ottiene il tipo del tag. |
| [getElementSize()](#getElementSize--) | Ottiene la dimensione dell'elemento in byte. |
| [getValue()](#getValue--) | Ottiene il valore contenuto da questo tipo di dati. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Imposta il valore contenuto da questo tipo di dati. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Scrive i dati aggiuntivi del tag. |
### TiffDoubleType(int tagId) {#TiffDoubleType-int-}
```
public TiffDoubleType(int tagId)
```


Inizializza una nuova istanza della classe `TiffDoubleType`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagId | int | L'ID del tag. |

### getValues() {#getValues--}
```
public double[] getValues()
```


Ottiene i valori.

**Returns:**
double[] - I valori.
### setValues(double[] value) {#setValues-double---}
```
public void setValues(double[] value)
```


Imposta i valori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double[] | I valori. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Ottiene il contenitore dei valori.

**Returns:**
com.aspose.ms.System.Array - Il contenitore dei valori.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Ottiene il tipo del tag.

**Returns:**
int - Il tipo di tag.
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Ottiene la dimensione dell'elemento in byte.

**Returns:**
byte - La dimensione dell'elemento in byte.
### getValue() {#getValue--}
```
public Object getValue()
```


Ottiene il valore contenuto da questo tipo di dati.

**Returns:**
java.lang.Object - Il valore.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Imposta il valore contenuto da questo tipo di dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.Object | Il valore. |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public long writeAdditionalData(TiffStreamWriter dataStream)
```


Scrive i dati aggiuntivi del tag.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | Il flusso di dati. |

**Returns:**
long - I byte effettivamente scritti.
