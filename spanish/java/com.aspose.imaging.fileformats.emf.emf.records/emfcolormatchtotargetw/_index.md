---
title: "EmfColorMatchToTargetW"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EMR_COLORMATCHTOTargetW especifica si se debe realizar la coincidencia de color con un perfil de color que está especificado en un archivo cuyo nombre consta de caracteres Unicode."
type: docs
weight: 24
url: /es/java/com.aspose.imaging.fileformats.emf.emf.records/emfcolormatchtotargetw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfColorMatchToTargetW extends EmfStateRecordType
```

El registro EMR\_COLORMATCHTOTargetW especifica si se debe realizar la coincidencia de color con un perfil de color que está especificado en un archivo cuyo nombre consiste en caracteres Unicode.

Un registro EMR\_COLORMATCHTOTargetW puede usarse para controlar si se aplica la transformación de color actual en el contexto del dispositivo de reproducción. Si el valor dwAction es CS\_ENABLE, el mapeo de color está habilitado, y la transformación de color actual DEBE aplicarse a las operaciones gráficas subsecuentes. Si dwAction se establece en CS\_DISABLE, la transformación de color NO DEBE aplicarse. Mientras el mapeo de color al objetivo está habilitado mediante un valor dwAction de CS\_ENABLE, los cambios en el espacio de color o en el mapeo de gamut de color no se aplican. Sin embargo, esos cambios DEBEN surtir efecto cuando el mapeo de color al objetivo se deshabilita. El campo dwAction NO DEBE establecerse en CS\_DELETE\_TRANSFORM a menos que la gestión de color ya haya sido habilitada con un registro EMR\_SETICMMODE (sección 2.3.11.14).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfColorMatchToTargetW(EmfRecord source)](#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inicializa una nueva instancia de la clase `EmfColorMatchToTargetW`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getDwAction()](#getDwAction--) | Obtiene o establece un entero sin signo de 32 bits que especifica un valor de la enumeración ColorSpace (sección 2.1.7). |
| [setDwAction(int value)](#setDwAction-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica un valor de la enumeración ColorSpace (sección 2.1.7). |
| [getDwFlags()](#getDwFlags--) | Obtiene o establece un entero sin signo de 32 bits que especifica un valor de la enumeración ColorMatchToTarget (sección 2.1.6). |
| [setDwFlags(int value)](#setDwFlags-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica un valor de la enumeración ColorMatchToTarget (sección 2.1.6). |
| [getCbName()](#getCbName--) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes en el nombre Unicode UTF16-LE del perfil de color deseado. |
| [setCbName(int value)](#setCbName-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes en el nombre Unicode UTF16-LE del perfil de color deseado. |
| [getCbData()](#getCbData--) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos sin procesar del perfil de color objetivo, si está contenido en el campo Data. |
| [setCbData(int value)](#setCbData-int-) | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos sin procesar del perfil de color objetivo, si está contenido en el campo Data. |
| [getData()](#getData--) | Obtiene o establece una matriz de tamaño (cbName + cbData) en bytes, que especifica el nombre UTF16-LE y los datos sin procesar del perfil de color deseado. |
| [setData(byte[] value)](#setData-byte---) | Obtiene o establece una matriz de tamaño (cbName + cbData) en bytes, que especifica el nombre UTF16-LE y los datos sin procesar del perfil de color deseado. |
| [getName()](#getName--) | Obtiene el nombre |
| [getRawData()](#getRawData--) | Obtiene los datos sin procesar |
### EmfColorMatchToTargetW(EmfRecord source) {#EmfColorMatchToTargetW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfColorMatchToTargetW(EmfRecord source)
```


Inicializa una nueva instancia de la clase `EmfColorMatchToTargetW`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | El origen. |

### getDwAction() {#getDwAction--}
```
public int getDwAction()
```


Obtiene o establece un entero sin signo de 32 bits que especifica un valor de la enumeración ColorSpace (sección 2.1.7).

**Returns:**
int
### setDwAction(int value) {#setDwAction-int-}
```
public void setDwAction(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica un valor de la enumeración ColorSpace (sección 2.1.7).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDwFlags() {#getDwFlags--}
```
public int getDwFlags()
```


Obtiene o establece un entero sin signo de 32 bits que especifica un valor de la enumeración ColorMatchToTarget (sección 2.1.6).

**Returns:**
int
### setDwFlags(int value) {#setDwFlags-int-}
```
public void setDwFlags(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica un valor de la enumeración ColorMatchToTarget (sección 2.1.6).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCbName() {#getCbName--}
```
public int getCbName()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes en el nombre Unicode UTF16-LE del perfil de color deseado.

**Returns:**
int
### setCbName(int value) {#setCbName-int-}
```
public void setCbName(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el número de bytes en el nombre Unicode UTF16-LE del perfil de color deseado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos sin procesar del perfil de color objetivo, si está contenido en el campo Data.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos sin procesar del perfil de color objetivo, si está contenido en el campo Data.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Obtiene o establece una matriz de tamaño (cbName + cbData) en bytes, que especifica el nombre UTF16-LE y los datos sin procesar del perfil de color deseado.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Obtiene o establece una matriz de tamaño (cbName + cbData) en bytes, que especifica el nombre UTF16-LE y los datos sin procesar del perfil de color deseado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] |  |

### getName() {#getName--}
```
public String getName()
```


Obtiene el nombre

**Returns:**
java.lang.String
### getRawData() {#getRawData--}
```
public byte[] getRawData()
```


Obtiene los datos sin procesar

**Returns:**
byte[]
