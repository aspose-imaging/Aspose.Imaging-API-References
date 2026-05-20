---
title: "TiffFloatType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il tipo TIFF float."
type: docs
weight: 14
url: /it/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tifffloattype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffFloatType extends TiffCommonArrayType
```

Il tipo TIFF float.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffFloatType(int tagId)](#TiffFloatType-int-) | Inizializza una nuova istanza della classe `TiffFloatType`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getValues()](#getValues--) | Ottiene i valori. |
| [setValues(float[] value)](#setValues-float---) | Imposta i valori. |
| [getElementSize()](#getElementSize--) | Ottiene la dimensione dell'elemento in byte. |
| [getValuesContainer()](#getValuesContainer--) | Ottiene il contenitore dei valori. |
| [getTagType()](#getTagType--) | Ottiene il tipo del tag. |
| [getValue()](#getValue--) | Ottiene il valore contenuto da questo tipo di dati. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Imposta il valore contenuto da questo tipo di dati. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Scrive i dati aggiuntivi del tag. |
### TiffFloatType(int tagId) {#TiffFloatType-int-}
```
public TiffFloatType(int tagId)
```


Inizializza una nuova istanza della classe `TiffFloatType`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagId | int | L'ID del tag. |

### getValues() {#getValues--}
```
public float[] getValues()
```


Ottiene i valori.

**Returns:**
float[] - I valori.
### setValues(float[] value) {#setValues-float---}
```
public void setValues(float[] value)
```


Imposta i valori.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float[] | I valori. |

### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Ottiene la dimensione dell'elemento in byte.

**Returns:**
byte - La dimensione dell'elemento in byte.
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
