---
title: "Clase EmfEpsData"
type: docs
weight: 50
url: /es/python-net/aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---

**Summary:** The EpsData object is a container for EPS data

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfEpsData

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfEpsData()](#EmfEpsData__1) | Inicializa una nueva instancia de la clase EmfEpsData |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| points | [EmfPoint28To4[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4/) | r/w | Obtiene o establece una matriz de tres objetos Point28_4 (sección 2.2.23) que define las <br/>            coordenadas del paralelogramo de salida usando notación FIX de 28.4 bits |
| post_script_data | System.Byte | r/w | Obtiene o establece una matriz de bytes de datos PostScript. La longitud de esta matriz puede <br/>            ser calculada a partir del campo SizeData. Estos datos PUEDE ser usados para renderizar una imagen. |
| size_data | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el tamaño total de este objeto, en bytes |
| versión | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el nivel del lenguaje PostScript. Este <br/>            valor DEBE ser 0x00000001 |


### Constructor: EmfEpsData() {#EmfEpsData__1}


```
 EmfEpsData() 
```

Inicializa una nueva instancia de la clase EmfEpsData

