---
title: EmfPlusObject
second_title: Aspose.Imaging para la referencia de la API de .NET
description: El registro EmfPlusObject especifica un objeto para usar en operaciones gráficas. La definición del objeto puede abarcar varios registros lo que se indica mediante el valor del campo Indicadores.
type: docs
weight: 6160
url: /es/net/aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---
## EmfPlusObject class

El registro EmfPlusObject especifica un objeto para usar en operaciones gráficas. La definición del objeto puede abarcar varios registros, lo que se indica mediante el valor del campo Indicadores.

```csharp
public sealed class EmfPlusObject : EmfPlusObjectRecordType
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EmfPlusObject](emfplusobject)(EmfPlusRecord) | Inicializa una nueva instancia del[`EmfPlusObject`](../emfplusobject) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado de 32 bits de bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado del registro de 12 bytes. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo se realizará la operación y sobre la estructura del registro. |
| [IsContinuable](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/iscontinuable) { get; set; } | Obtiene o establece un valor que indica si esta instancia es continuable. Indica que la definición del objeto continúa en el siguiente registro EmfPlusObject . Esta bandera nunca se establece en el registro final que define el objeto. |
| [ObjectData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/objectdata) { get; set; } | Obtiene o establece una matriz de bytes que contiene datos para el tipo de objeto especificado en el campo Indicadores. El contenido y el formato de los datos pueden ser diferentes para cada tipo de objeto. Consulte las definiciones de objetos individuales en la sección 2.2.1 para obtener información adicional. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/objectid) { get; set; } | Obtiene o establece el identificador de objeto. El índice en la tabla de objetos EMF+ para asociar con el objeto creado por este registro. El valor DEBE ser cero a 63, inclusive. |
| [ObjectType](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/objecttype) { get; set; } | Obtiene o establece el tipo del objeto. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado de 32 bits de bytes en todo el registro, incluido el encabezado del registro de 12 bytes y los datos específicos del registro. |
| [TotalObjectSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/totalobjectsize) { get; set; } | Obtiene o establece el tamaño total del objeto. Si el registro es continuable, cuando se establece el bit de continuación, este campo estará presente. Los objetos continuos tienen varios registros EMF+ que comienzan con EmfPlusContineudObjectRecord. Cada EmfPlusContinuedObjectRecord contendrá a TotalObjectSize. Una vez que se ha leído el número de bytes de TotalObjectSize, el siguiente registro EMF+ no se tratará como parte del objeto continuo. |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Obtiene un entero de 16 bits sin signo que identifica el tipo de registro. |

### Observaciones

El registro EmfPlusObject es genérico; se utiliza para todo tipo de objetos. Los valores que son específicos de tipos de objetos particulares están contenidos en el campo ObjectData. Un modelo conceptual para gestionar objetos gráficos se describe en Gestión de objetos gráficos (sección 3.1.2).

### Ver también

* class [EmfPlusObjectRecordType](../emfplusobjectrecordtype)
* espacio de nombres [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
