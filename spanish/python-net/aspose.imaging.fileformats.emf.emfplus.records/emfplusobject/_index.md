---
title: "Clase EmfPlusObject"
type: docs
weight: 330
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---

**Summary:** The EmfPlusObject record specifies an object for use in graphics operations. The object definition<br/>            can span multiple records, which is indicated by the value of the Flags field.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObject

**Inheritance:** EmfPlusObjectRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusObject(source)](#EmfPlusObject_source_1) | Inicializa una nueva instancia de la clase [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| is_continuable | bool | r/w | Obtiene o establece un valor que indica si esta instancia es continuable.<br/>            Indica que la definición del objeto continúa en el siguiente registro EmfPlusObject<br/>            . Esta bandera nunca se establece en el registro final que define el objeto. |
| object_data | [EmfPlusGraphicsObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/) | r/w | Obtiene o establece una matriz de bytes que contiene datos para el tipo de objeto especificado en<br/>            el campo Flags. El contenido y formato de los datos pueden variar según el tipo de objeto. Consulte<br/>            las definiciones individuales de objetos en la sección 2.2.1 para obtener información adicional. |
| object_id | System.Byte | r/w | Obtiene o establece el identificador del objeto.<br/>            El índice en la tabla de objetos EMF+ para asociarlo con el objeto<br/>            creado por este registro. El valor DEBE ser de 0 a 63, inclusive. |
| object_type | [EmfPlusObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjecttype/) | r/w | Obtiene o establece el tipo del objeto. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| total_object_size | int | r/w | Obtiene o establece el tamaño total del objeto.<br/>            Si el registro es continuable, cuando el bit de continuación está activado, este campo<br/>            estará presente. Los objetos continuados tienen múltiples registros EMF+ que comienzan con<br/>            EmfPlusContineudObjectRecord. Cada EmfPlusContinuedObjectRecord contendrá un<br/>            TotalObjectSize. Una vez que se hayan leído el número de bytes indicado por TotalObjectSize, el siguiente registro EMF+<br/>            no será tratado como parte del objeto continuado. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusObject(source) {#EmfPlusObject_source_1}


```
 EmfPlusObject(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

