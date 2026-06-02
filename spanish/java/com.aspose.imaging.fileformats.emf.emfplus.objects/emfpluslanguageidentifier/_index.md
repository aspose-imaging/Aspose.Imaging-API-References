---
title: "EmfPlusLanguageIdentifier"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusLanguageIdentifier especifica un identificador de idioma que corresponde al idioma natural en una configuración regional, incluyendo países, regiones geográficas y distritos administrativos."
type: docs
weight: 50
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslanguageidentifier/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusLanguageIdentifier extends EmfPlusStructureObjectType
```

El objeto EmfPlusLanguageIdentifier especifica un identificador de idioma que corresponde al idioma natural en una configuración regional, incluyendo países, regiones geográficas y distritos administrativos. Cada identificador de idioma es una codificación de un valor de idioma principal y un valor de subidioma.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusLanguageIdentifier()](#EmfPlusLanguageIdentifier--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getValue()](#getValue--) | Gets or sets the value of the field 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId | PrimaryLanguageId | SubLanguageId (6 bits): El país, región geográfica o distrito administrativo para el idioma natural especificado en el campo PrimaryLanguageId. |
| [setValue(short value)](#setValue-short-) | Gets or sets the value of the field 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId | PrimaryLanguageId | SubLanguageId (6 bits): El país, región geográfica o distrito administrativo para el idioma natural especificado en el campo PrimaryLanguageId. |
### EmfPlusLanguageIdentifier() {#EmfPlusLanguageIdentifier--}
```
public EmfPlusLanguageIdentifier()
```


### getValue() {#getValue--}
```
public short getValue()
```


Obtiene o establece el valor del campo 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId| PrimaryLanguageId | SubLanguageId (6 bits): El país, región geográfica o distrito administrativo para el idioma natural especificado en el campo PrimaryLanguageId. Los identificadores de subidioma son extensibles por el proveedor. Los identificadores de subidioma definidos por el proveedor DEBEN estar en el rango 0x20 a 0x3F, inclusive. PrimaryLanguageId (10 bits): El idioma natural. Los identificadores de idioma principal son extensibles por el proveedor. Los identificadores de idioma principal definidos por el proveedor DEBEN estar en el rango 0x0200 a 0x03FF, inclusive.

**Returns:**
short
### setValue(short value) {#setValue-short-}
```
public void setValue(short value)
```


Obtiene o establece el valor del campo 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SubLanguageId| PrimaryLanguageId | SubLanguageId (6 bits): El país, región geográfica o distrito administrativo para el idioma natural especificado en el campo PrimaryLanguageId. Los identificadores de subidioma son extensibles por el proveedor. Los identificadores de subidioma definidos por el proveedor DEBEN estar en el rango 0x20 a 0x3F, inclusive. PrimaryLanguageId (10 bits): El idioma natural. Los identificadores de idioma principal son extensibles por el proveedor. Los identificadores de idioma principal definidos por el proveedor DEBEN estar en el rango 0x0200 a 0x03FF, inclusive.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | short |  |

