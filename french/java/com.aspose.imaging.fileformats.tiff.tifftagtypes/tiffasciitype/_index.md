---
title: "TiffASCIIType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le type ascii tiff."
type: docs
weight: 10
url: /fr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype)
```
public final class TiffASCIIType extends TiffDataType
```

Le type ascii tiff.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffASCIIType(int tagId)](#TiffASCIIType-int-) | Initialise une nouvelle instance de la classe `TiffASCIIType`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getText()](#getText--) | Obtient ou définit le texte. |
| [setText(String value)](#setText-java.lang.String-) | Obtient ou définit le texte. |
| [getCount()](#getCount--) | Obtient le nombre d'éléments. |
| [getTagType()](#getTagType--) | Obtient le type de la balise. |
| [getValue()](#getValue--) | Obtient ou définit la valeur que ce type de données contient. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Obtient ou définit la valeur que ce type de données contient. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Écrit les données d'étiquette supplémentaires. |
### TiffASCIIType(int tagId) {#TiffASCIIType-int-}
```
public TiffASCIIType(int tagId)
```


Initialise une nouvelle instance de la classe `TiffASCIIType`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagId | int | L'identifiant du tag. |

### getText() {#getText--}
```
public String getText()
```


Obtient ou définit le texte.

**Returns:**
java.lang.String - Le texte.
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Obtient ou définit le texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Le texte. |

### getCount() {#getCount--}
```
public long getCount()
```


Obtient le nombre d'éléments.

**Returns:**
long - Le nombre d'éléments.
### getTagType() {#getTagType--}
```
public int getTagType()
```


Obtient le type de la balise.

**Returns:**
int - Le type d'étiquette.
### getValue() {#getValue--}
```
public Object getValue()
```


Obtient ou définit la valeur que ce type de données contient.

**Returns:**
java.lang.Object - La valeur.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public void setValue(Object value)
```


Obtient ou définit la valeur que ce type de données contient.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Object | La valeur. |

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public long writeAdditionalData(TiffStreamWriter dataStream)
```


Écrit les données d'étiquette supplémentaires.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.imaging.fileformats.tiff.filemanagement/tiffstreamwriter) | Le flux de données. |

**Returns:**
long - Le nombre réel d'octets écrits.
