---
title: "TiffASCIIType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il tipo TIFF ASCII."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffASCIIType extends TiffDataType
```

Il tipo TIFF ASCII.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffASCIIType(int tagId)](#TiffASCIIType-int-) | Inizializza una nuova istanza della classe `TiffASCIIType`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getText()](#getText--) | Ottiene o imposta il testo. |
| [setText(String value)](#setText-java.lang.String-) | Ottiene o imposta il testo. |
| [getCount()](#getCount--) | Ottiene il conteggio degli elementi. |
| [getTagType()](#getTagType--) | Ottiene il tipo del tag. |
| [getValue()](#getValue--) | Ottiene o imposta il valore che questo tipo di dati contiene. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Ottiene o imposta il valore che questo tipo di dati contiene. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Scrive i dati aggiuntivi del tag. |
### TiffASCIIType(int tagId) {#TiffASCIIType-int-}
```
public TiffASCIIType(int tagId)
```


Inizializza una nuova istanza della classe `TiffASCIIType`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| tagId | int | L'ID del tag. |

### getText() {#getText--}
```
public String getText()
```


Ottiene o imposta il testo.

**Returns:**
java.lang.String - Il testo.
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Ottiene o imposta il testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Il testo. |

### getCount() {#getCount--}
```
public long getCount()
```


Ottiene il conteggio degli elementi.

**Returns:**
long - Il conteggio degli elementi.
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


Ottiene o imposta il valore che questo tipo di dati contiene.

**Returns:**
java.lang.Object - Il valore.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Ottiene o imposta il valore che questo tipo di dati contiene.

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
