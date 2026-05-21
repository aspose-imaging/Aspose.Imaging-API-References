---
title: "EmfPlusFont"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmfPlusFont especifica propiedades que determinan la apariencia del texto, incluido el tamaño y el estilo de la tipografía."
type: docs
weight: 42
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusFont extends EmfPlusGraphicsObjectType
```

El objeto EmfPlusFont especifica propiedades que determinan la apariencia del texto, incluyendo la tipografía, el tamaño y el estilo.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusFont()](#EmfPlusFont--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Obtiene o establece una cadena de caracteres Unicode de longitud Length que contiene el nombre de la familia tipográfica |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | Obtiene o establece una cadena de caracteres Unicode de longitud Length que contiene el nombre de la familia tipográfica |
| [getFontStyleFlags()](#getFontStyleFlags--) | Obtiene o establece un entero con signo de 32 bits que especifica atributos de los glifos de caracteres que afectan la apariencia de la fuente, como negrita y cursiva. |
| [setFontStyleFlags(int value)](#setFontStyleFlags-int-) | Obtiene o establece un entero con signo de 32 bits que especifica atributos de los glifos de caracteres que afectan la apariencia de la fuente, como negrita y cursiva. |
| [getSizeUnit()](#getSizeUnit--) | Obtiene o establece un entero sin signo de 32 bits que especifica las unidades utilizadas para el campo EmSize. |
| [setSizeUnit(int value)](#setSizeUnit-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica las unidades utilizadas para el campo EmSize. |
| [getEmSize()](#getEmSize--) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el tamaño em de la fuente en unidades especificadas por el campo SizeUnit. |
| [setEmSize(float value)](#setEmSize-float-) | Obtiene o establece un valor de punto flotante de 32 bits que especifica el tamaño em de la fuente en unidades especificadas por el campo SizeUnit. |
### EmfPlusFont() {#EmfPlusFont--}
```
public EmfPlusFont()
```


### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Obtiene o establece una cadena de caracteres Unicode de longitud Length que contiene el nombre de la familia tipográfica

**Returns:**
java.lang.String
### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public void setFamilyName(String value)
```


Obtiene o establece una cadena de caracteres Unicode de longitud Length que contiene el nombre de la familia tipográfica

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getFontStyleFlags() {#getFontStyleFlags--}
```
public int getFontStyleFlags()
```


Obtiene o establece un entero con signo de 32 bits que especifica atributos de los glifos de caracteres que afectan la apariencia de la fuente, como negrita y cursiva. Este valor DEBE estar compuesto por banderas FontStyle (sección 2.1.2.4).

**Returns:**
int
### setFontStyleFlags(int value) {#setFontStyleFlags-int-}
```
public void setFontStyleFlags(int value)
```


Obtiene o establece un entero con signo de 32 bits que especifica atributos de los glifos de caracteres que afectan la apariencia de la fuente, como negrita y cursiva. Este valor DEBE estar compuesto por banderas FontStyle (sección 2.1.2.4).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSizeUnit() {#getSizeUnit--}
```
public int getSizeUnit()
```


Obtiene o establece un entero sin signo de 32 bits que especifica las unidades usadas para el campo EmSize. Estas son típicamente las unidades que se emplearon al diseñar la fuente. El valor DEBE estar en la enumeración UnitType (sección 2.1.1.33).

**Returns:**
int
### setSizeUnit(int value) {#setSizeUnit-int-}
```
public void setSizeUnit(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica las unidades usadas para el campo EmSize. Estas son típicamente las unidades que se emplearon al diseñar la fuente. El valor DEBE estar en la enumeración UnitType (sección 2.1.1.33).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getEmSize() {#getEmSize--}
```
public float getEmSize()
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el tamaño em de la fuente en unidades especificadas por el campo SizeUnit.

**Returns:**
float
### setEmSize(float value) {#setEmSize-float-}
```
public void setEmSize(float value)
```


Obtiene o establece un valor de punto flotante de 32 bits que especifica el tamaño em de la fuente en unidades especificadas por el campo SizeUnit.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float |  |

