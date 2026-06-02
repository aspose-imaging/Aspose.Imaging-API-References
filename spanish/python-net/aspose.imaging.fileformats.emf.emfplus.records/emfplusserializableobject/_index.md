---
title: "Clase EmfPlusSerializableObject"
type: docs
weight: 440
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/
---

**Summary:** The EmfPlusSerializableObject record defines an image effects parameter block that has been<br/>            serialized into a data buffer.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusSerializableObject

**Inheritance:** EmfPlusObjectRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusSerializableObject(source)](#EmfPlusSerializableObject_source_1) | Inicializa una nueva instancia de la clase [EmfPlusSerializableObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| búfer | System.Byte | r/w | Obtiene o establece una matriz de bytes de BufferSize que contiene el bloque de parámetros de efectos de imagen serializados<br/>            que corresponde al GUID en el campo ObjectGUID. Esto DEBE ser uno de<br/>            los objetos Image Effects (sección 2.2.3). |
| buffer_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño en bytes del campo Buffer alineado a 32 bits. |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que no se utiliza. Este campo DEBERÍA establecerse a cero<br/>            y DEBE ser ignorado al recibirlo. |
| image_effect | [EmfPlusImageEffectsObjectType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype/) | r/w | Obtiene o establece el efecto de imagen. |
| object_guid | [GuidPacketRepresentation](/imaging/python-net/aspose.imaging.fileformats.emf.dtyp.commondatastructures/guidpacketrepresentation/) | r/w | Obtiene o establece el valor de representación del paquete GUID ([MS-DTYP] sección 2.3.4.2)<br/>            para el efecto de imagen. Esto DEBE corresponder a uno de los identificadores ImageEffects (sección 2.1.3.1). |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |


### Constructor: EmfPlusSerializableObject(source) {#EmfPlusSerializableObject_source_1}


```
 EmfPlusSerializableObject(source) 
```

Inicializa una nueva instancia de la clase [EmfPlusSerializableObject](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

