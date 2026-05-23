---
title: "Clase EmfPlusHeader"
type: docs
weight: 310
url: /es/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/
---

**Summary:** The EmfPlusHeader record specifies the start of EMF+ data in the metafile.<br/>            The EmfPlusHeader record MUST be embedded in an EMF EMR_COMMENT_EMFPLUS record,<br/>             which MUST be the record immediately following the EMF header in the metafile. <br/>            The EMR_COMMENT_EMFPLUS record is specified in [MS-EMF] section 2.3.3.2.

**Module:** [aspose.imaging.fileformats.emf.emfplus.records](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.records.EmfPlusHeader

**Inheritance:** EmfPlusControlRecordType

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfPlusHeader(source)](#EmfPlusHeader_source_1) | Inicializa una nueva instancia de la [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/) clase. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| data_size | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE definir el número alineado a 32 bits de<br/>            bytes de datos en el campo RecordData que sigue. Este número no incluye el encabezado de registro de 12 bytes. |
| dual_mode | bool | r/w | Obtiene o establece un valor que indica si [dual mode].<br/>            Si está establecido, esta bandera indica que este metafichero es \"dual-mode\", lo que significa<br/>            que contiene dos conjuntos de registros, cada uno de los cuales especifica completamente <br/>            el contenido gráfico. Si está desactivado, el contenido gráfico se especifica mediante registros EMF+ <br/>            y, posiblemente, registros EMF que son precedidos por un registro EmfPlusGetDC. <br/>            Si esta bandera está establecida, los registros EMF por sí solos DEBERÍAN ser suficientes para definir el <br/>            contenido gráfico. Tenga en cuenta que, ya sea que la bandera \"dual-mode\" esté establecida o no, algunos <br/>            registros EMF están siempre presentes, a saber, los registros de control EMF y los registros EMF <br/>            que contienen registros EMF+. Los registros de control EMF se especifican en [MS-EMF] <br/>            sección 2.3.4. |
| emf_plus_flags | int | r/w | Obtiene o establece las banderas EMF plus.<br/>            Un entero sin signo de 32 bits que contiene información sobre cómo se grabó este metafichero.<br/>            si el bit 31 del campo está establecido, esta bandera indica que el metafichero se grabó con <br/>            un contexto de dispositivo de referencia para una pantalla de video. Si está desactivado, el metafichero se grabó con<br/>            un contexto de dispositivo de referencia para una impresora. |
| banderas | int | r/w | Obtiene o establece un entero sin signo de 16 bits que contiene información para algunos registros sobre cómo<br/>            se debe realizar la operación y sobre la estructura del registro. |
| is_valid | bool | r | Obtiene un valor que indica si esta instancia es válida. |
| logical_dpi_x | int | r/w | Obtiene o establece el dpi lógico x.<br/>            Un entero sin signo de 32 bits que especifica la resolución horizontal para la cual se grabó el metafichero <br/>            en unidades de píxeles por pulgada. |
| logical_dpi_y | int | r/w | Obtiene o establece el dpi lógico y.<br/>            Un entero sin signo de 32 bits que especifica la resolución vertical para la cual se grabó el metafichero <br/>            en unidades de líneas por pulgada. |
| tamaño | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número alineado a 32 bits de bytes<br/>            en todo el registro, incluyendo el encabezado de registro de 12 bytes y los datos específicos del registro. |
| type | [EmfPlusRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/) | r | Obtiene un entero sin signo de 16 bits que identifica el tipo de registro. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Obtiene o establece la versión.<br/>            Un objeto EmfPlusGraphicsVersion (sección 2.2.2.19) que especifica la versión de los gráficos del sistema operativo que se utilizó para crear este metafichero. |
| video_display | bool | r/w | Obtiene o establece un valor que indica si pantalla de video.<br/>            si está establecido, esta bandera indica que el metafichero se grabó con un contexto de dispositivo de referencia para una pantalla de video. Si está desactivado, el metafichero se grabó con un contexto de dispositivo de referencia para una impresora. |


### Constructor: EmfPlusHeader(source) {#EmfPlusHeader_source_1}


```
 EmfPlusHeader(source) 
```

Inicializa una nueva instancia de la [EmfPlusHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusheader/) clase.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| source | [EmfPlusRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/) | La fuente. |

