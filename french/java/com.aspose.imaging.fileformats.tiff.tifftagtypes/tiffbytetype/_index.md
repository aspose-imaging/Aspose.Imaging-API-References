---
title: "TiffByteType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le type octet tiff."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.fileformats.tiff.tifftagtypes/tiffbytetype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.tiff.TiffDataType](../../com.aspose.imaging/fileformats/tiff/tiffdatatype), [com.aspose.imaging.fileformats.tiff.tifftagtypes.TiffCommonArrayType](../../com.aspose.imaging/fileformats/tiff/tifftagtypes/tiffcommonarraytype)
```
public final class TiffByteType extends TiffCommonArrayType
```

Le type octet tiff.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffByteType(int tagId)](#TiffByteType-int-) | Initialise une nouvelle instance de la classe `TiffByteType`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getValues()](#getValues--) | Obtient ou définit les valeurs. |
| [setValues(byte[] value)](#setValues-byte---) | Obtient ou définit les valeurs. |
| [getValuesContainer()](#getValuesContainer--) | Obtient le conteneur de valeurs. |
| [getElementSize()](#getElementSize--) | Obtient la taille de l'élément en octets. |
| [getTagType()](#getTagType--) | Obtient le type de la balise. |
| [getValue()](#getValue--) | Obtient ou définit la valeur que ce type de données contient. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Obtient ou définit la valeur que ce type de données contient. |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.imaging.fileformats.tiff.filemanagement.TiffStreamWriter-) | Écrit les données d'étiquette supplémentaires. |
### TiffByteType(int tagId) {#TiffByteType-int-}
```
public TiffByteType(int tagId)
```


Initialise une nouvelle instance de la classe `TiffByteType`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tagId | int | L'identifiant du tag. |

### getValues() {#getValues--}
```
public byte[] getValues()
```


Obtient ou définit les valeurs.

**Returns:**
byte[] - Les données.
### setValues(byte[] value) {#setValues-byte---}
```
public void setValues(byte[] value)
```


Obtient ou définit les valeurs.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] | Les données. |

### getValuesContainer() {#getValuesContainer--}
```
public System.Array getValuesContainer()
```


Obtient le conteneur de valeurs.

**Returns:**
com.aspose.ms.System.Array - Le conteneur de valeurs.
### getElementSize() {#getElementSize--}
```
public byte getElementSize()
```


Obtient la taille de l'élément en octets.

**Returns:**
byte - La taille de l'élément en octets.
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
