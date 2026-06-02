---
title: "EmfPlusObject"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro EmfPlusObject especifica un objeto para su uso en operaciones gráficas."
type: docs
weight: 42
url: /es/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusObject extends EmfPlusObjectRecordType
```

El registro EmfPlusObject especifica un objeto para su uso en operaciones gráficas. La definición del objeto puede abarcar varios registros, lo que se indica con el valor del campo Flags.

El registro EmfPlusObject es genérico; se utiliza para todo tipo de objetos. Los valores que son específicos de tipos de objetos particulares se encuentran en el campo ObjectData. Un modelo conceptual para gestionar objetos gráficos se describe en Managing Graphics Objects (sección 3.1.2).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmfPlusObject(EmfPlusRecord source)](#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Inicializa una nueva instancia de la clase `EmfPlusObject`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [isContinuable()](#isContinuable--) | Obtiene o establece un valor que indica si esta instancia es continuable. |
| [setContinuable(boolean value)](#setContinuable-boolean-) | Obtiene o establece un valor que indica si esta instancia es continuable. |
| [getObjectType()](#getObjectType--) | Obtiene o establece el tipo del objeto. |
| [setObjectType(byte value)](#setObjectType-byte-) | Obtiene o establece el tipo del objeto. |
| [getObjectId()](#getObjectId--) | Obtiene o establece el identificador del objeto. |
| [setObjectId(byte value)](#setObjectId-byte-) | Obtiene o establece el identificador del objeto. |
| [getTotalObjectSize()](#getTotalObjectSize--) | Obtiene o establece el tamaño total del objeto. |
| [setTotalObjectSize(int value)](#setTotalObjectSize-int-) | Obtiene o establece el tamaño total del objeto. |
| [getObjectData()](#getObjectData--) | Obtiene o establece una matriz de bytes que contiene datos para el tipo de objeto especificado en el campo Flags. |
| [setObjectData(EmfPlusGraphicsObjectType value)](#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-) | Obtiene o establece una matriz de bytes que contiene datos para el tipo de objeto especificado en el campo Flags. |
### EmfPlusObject(EmfPlusRecord source) {#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusObject(EmfPlusRecord source)
```


Inicializa una nueva instancia de la clase `EmfPlusObject`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | El origen. |

### isContinuable() {#isContinuable--}
```
public boolean isContinuable()
```


Obtiene o establece un valor que indica si esta instancia es continuable. Indica que la definición del objeto continúa en el siguiente registro EmfPlusObject. Esta bandera nunca se establece en el registro final que define el objeto.

Valor: `true` si esta instancia está comprimida; de lo contrario, `false`.

**Returns:**
boolean
### setContinuable(boolean value) {#setContinuable-boolean-}
```
public void setContinuable(boolean value)
```


Obtiene o establece un valor que indica si esta instancia es continuable. Indica que la definición del objeto continúa en el siguiente registro EmfPlusObject. Esta bandera nunca se establece en el registro final que define el objeto.

Valor: `true` si esta instancia está comprimida; de lo contrario, `false`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getObjectType() {#getObjectType--}
```
public byte getObjectType()
```


Obtiene o establece el tipo del objeto.

Valor: El tipo del objeto.

**Returns:**
byte
### setObjectType(byte value) {#setObjectType-byte-}
```
public void setObjectType(byte value)
```


Obtiene o establece el tipo del objeto.

Valor: El tipo del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Obtiene o establece el identificador del objeto. El índice en la tabla de objetos EMF+ para asociarlo con el objeto creado por este registro. El valor DEBE estar entre 0 y 63, inclusive.

Valor: El identificador del objeto.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Obtiene o establece el identificador del objeto. El índice en la tabla de objetos EMF+ para asociarlo con el objeto creado por este registro. El valor DEBE estar entre 0 y 63, inclusive.

Valor: El identificador del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte |  |

### getTotalObjectSize() {#getTotalObjectSize--}
```
public int getTotalObjectSize()
```


Obtiene o establece el tamaño total del objeto. Si el registro es continuable, cuando el bit de continuación está activado, este campo estará presente. Los objetos continuados tienen varios registros EMF+ que comienzan con EmfPlusContineudObjectRecord. Cada EmfPlusContinuedObjectRecord contendrá un TotalObjectSize. Una vez que se hayan leído el número de bytes indicado por TotalObjectSize, el siguiente registro EMF+ no se considerará parte del objeto continuado.

Valor: El tamaño total del objeto.

**Returns:**
int
### setTotalObjectSize(int value) {#setTotalObjectSize-int-}
```
public void setTotalObjectSize(int value)
```


Obtiene o establece el tamaño total del objeto. Si el registro es continuable, cuando el bit de continuación está activado, este campo estará presente. Los objetos continuados tienen varios registros EMF+ que comienzan con EmfPlusContineudObjectRecord. Cada EmfPlusContinuedObjectRecord contendrá un TotalObjectSize. Una vez que se hayan leído el número de bytes indicado por TotalObjectSize, el siguiente registro EMF+ no se considerará parte del objeto continuado.

Valor: El tamaño total del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getObjectData() {#getObjectData--}
```
public EmfPlusGraphicsObjectType getObjectData()
```


Obtiene o establece una matriz de bytes que contiene datos para el tipo de objeto especificado en el campo Flags. El contenido y formato de los datos pueden variar según cada tipo de objeto. Consulte las definiciones individuales de objetos en la sección 2.2.1 para obtener información adicional.

Valor: Los datos del objeto.

**Returns:**
[EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
### setObjectData(EmfPlusGraphicsObjectType value) {#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-}
```
public void setObjectData(EmfPlusGraphicsObjectType value)
```


Obtiene o establece una matriz de bytes que contiene datos para el tipo de objeto especificado en el campo Flags. El contenido y formato de los datos pueden variar según cada tipo de objeto. Consulte las definiciones individuales de objetos en la sección 2.2.1 para obtener información adicional.

Valor: Los datos del objeto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype) |  |

