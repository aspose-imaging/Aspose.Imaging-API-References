---
title: "EmfFormat"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El objeto EmrFormat contiene información que identifica el formato de los datos de imagen en un registro EMR_COMMENT_MULTIFORMATS sección 2.3.3.4.3."
type: docs
weight: 15
url: /es/java/com.aspose.imaging.fileformats.emf.emf.objects/emfformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfFormat extends EmfObject
```

El objeto EmrFormat contiene información que identifica el formato de los datos de imagen en un registro EMR\_COMMENT\_MULTIFORMATS (sección 2.3.3.4.3).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfFormat()](#EmfFormat--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getSignature()](#getSignature--) | Obtiene o establece un entero sin signo de 32 bits que especifica el formato de los datos de imagen. |
| [setSignature(int value)](#setSignature-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el formato de los datos de imagen. |
| [getVersion()](#getVersion--) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de versión del formato. |
| [setVersion(int value)](#setVersion-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de versión del formato. |
| [getSizeData()](#getSizeData--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos en bytes |
| [setSizeData(int value)](#setSizeData-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos en bytes |
| [getOffData()](#getOffData--) | Obtiene o establece un entero sin signo de 32 bits que especifica el desplazamiento a los datos desde el inicio del campo identificador en un registro EMR\_COMMENT\_PUBLIC (sección 2.3.3.4). |
| [setOffData(int value)](#setOffData-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el desplazamiento a los datos desde el inicio del campo identificador en un registro EMR\_COMMENT\_PUBLIC (sección 2.3.3.4). |
### EmfFormat() {#EmfFormat--}
```
public EmfFormat()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el formato de los datos de imagen. Este valor DEBE estar en la enumeración FormatSignature (sección 2.1.14).

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el formato de los datos de imagen. Este valor DEBE estar en la enumeración FormatSignature (sección 2.1.14).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de versión del formato. Si el campo Signature especifica PostScript encapsulado (EPS), este valor DEBE ser 0x00000001; de lo contrario, este valor DEBE ser ignorado.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de versión del formato. Si el campo Signature especifica PostScript encapsulado (EPS), este valor DEBE ser 0x00000001; de lo contrario, este valor DEBE ser ignorado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos en bytes

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos en bytes

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getOffData() {#getOffData--}
```
public int getOffData()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el desplazamiento a los datos desde el inicio del campo identificador en un registro EMR\_COMMENT\_PUBLIC (sección 2.3.3.4). El desplazamiento DEBE estar alineado a 32 bits.

**Returns:**
int
### setOffData(int value) {#setOffData-int-}
```
public void setOffData(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el desplazamiento a los datos desde el inicio del campo identificador en un registro EMR\_COMMENT\_PUBLIC (sección 2.3.3.4). El desplazamiento DEBE estar alineado a 32 bits.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

