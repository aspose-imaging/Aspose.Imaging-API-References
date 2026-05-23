---
title: "Clase EmfHeaderExtension2"
type: docs
weight: 100
url: /es/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/
---

**Summary:** The HeaderExtension2 object defines the second extension to the EMF metafile header. It adds the<br/>            ability to measure device surfaces in micrometers, which enhances the resolution and scalability of EMF metafiles.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension2

**Inheritance:** EmfHeaderObject

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfHeaderExtension2()](#EmfHeaderExtension2__1) | Inicializa una nueva instancia de la clase EmfHeaderExtension2 |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL ([MS-WMF] sección 2.2.2.19) que especifica los límites rectangulares inclusivo‑inclusivo <br/>            en unidades de dispositivo del rectángulo más pequeño que puede dibujarse alrededor de la imagen almacenada en <br/>            el metafile |
| bytes | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño del metafile, en bytes. |
| device | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Obtiene o establece un objeto WMF SizeL ([MS-WMF] sección 2.2.2.22) que especifica el tamaño del dispositivo de referencia, en píxeles |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Obtiene o establece un objeto WMF RectL que especifica las dimensiones rectangulares inclusivo‑inclusivo, en unidades de 0,01 milímetros <br/>            , de un rectángulo que rodea la imagen almacenada en el metafile |
| manejadores | int | r/w | Obtiene o establece un entero sin signo de 16 bits que especifica el número de objetos gráficos que se utilizarán durante el procesamiento del metafile |
| micrometers_x | int | r/w | Obtiene o establece el tamaño horizontal de 32 bits del dispositivo de pantalla para el cual se generó la imagen del metafile, en micrómetros |
| micrometers_y | int | r/w | Obtiene o establece el tamaño vertical de 32 bits del dispositivo de pantalla para el cual se generó la imagen del metafile, en micrómetros. |
| millimeters | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Obtiene o establece un objeto WMF SizeL que especifica el tamaño del dispositivo de referencia, en milímetros |
| n_desription | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número de caracteres en la matriz <br/>            que contiene la descripción del contenido del metafile. Es cero si no hay cadena de descripción. |
| n_pal_entries | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número de entradas en la paleta del metafile <br/>            . La paleta se encuentra en el registro EMR_EOF |
| off_description | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el desplazamiento desde el comienzo de este <br/>            registro hasta la matriz que contiene la descripción del contenido del metafile |
| record_signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica la firma del registro. Esto DEBE ser ENHMETA_SIGNATURE, <br/>            de la enumeración FormatSignature (sección 2.1.14). |
| registros | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número de registros en el metafile |
| reservado | int | r/w | Obtiene o establece un entero sin signo de 16 bits que DEBE ser 0x0000 y DEBE ser ignorado |
| valid | bool | r | Obtiene un valor que indica si este [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) es válido. |
| versión | int | r/w | Obtiene o establece Version (4 bytes): Un entero sin signo de 32 bits que especifica la interoperabilidad del metafichero EMF. Esto DEBERÍA ser 0x00010000 |


### Constructor: EmfHeaderExtension2() {#EmfHeaderExtension2__1}


```
 EmfHeaderExtension2() 
```

Inicializa una nueva instancia de la clase EmfHeaderExtension2

