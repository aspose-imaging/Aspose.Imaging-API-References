---
title: "Clase EmfFormat"
type: docs
weight: 60
url: /es/python-net/aspose.imaging.fileformats.emf.emf.objects/emfformat/
---

**Summary:** The EmrFormat object contains information that identifies the format of image data in an<br/>            EMR_COMMENT_MULTIFORMATS record(section 2.3.3.4.3).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfFormat

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfFormat()](#EmfFormat__1) | Inicializa una nueva instancia de la clase EmfFormat |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| off_data | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el desplazamiento de los datos desde el <br/> inicio del campo de identificador en un registro EMR_COMMENT_PUBLIC (sección 2.3.3.4). <br/> El desplazamiento DEBE estar alineado a 32 bits. |
| signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el formato de los datos de imagen. <br/> Este valor DEBE estar en la enumeración FormatSignature (sección 2.1.14). |
| size_data | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño de los datos en bytes |
| versión | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número de versión del formato. <br/> Si el campo Signature especifica PostScript encapsulado (EPS), <br/> este valor DEBE ser 0x00000001; de lo contrario, este valor DEBE ser ignorado. |


### Constructor: EmfFormat() {#EmfFormat__1}


```
 EmfFormat() 
```

Inicializa una nueva instancia de la clase EmfFormat

