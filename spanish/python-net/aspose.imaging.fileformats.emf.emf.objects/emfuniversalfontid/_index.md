---
title: "Clase EmfUniversalFontId"
type: docs
weight: 280
url: /es/python-net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---

**Summary:** The UniversalFontId object defines a mechanism for identifying fonts in EMF metafiles.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfUniversalFontId()](#EmfUniversalFontId__1) | Inicializa una nueva instancia de la clase EmfUniversalFontId |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| checksum | int | r/w | Obtiene o establece un entero sin signo de 32 bits que es la suma de verificación de la fuente.<br/>            El valor de la suma de verificación tiene los siguientes significados.<br/>            0x00000000  El objeto es una fuente de dispositivo. <br/>            0x00000001  El objeto es una fuente Type 1 que ha sido instalada en la máquina cliente y está <br/>            enumerada por el controlador de impresora PostScript como una fuente de dispositivo. <br/>            0x00000002  El objeto no es una fuente sino un rasterizador Type 1. <br/>            3 ≤ valor   El objeto es una fuente bitmap, vectorial o TrueType, o una fuente rasterizada Type 1 que <br/>            fue creada por un rasterizador Type 1. |
| index | int | r/w | Obtiene o establece un entero sin signo de 32 bits que es un índice asociado al objeto de fuente. El <br/>            significado de este campo está determinado por el tipo de fuente. |


### Constructor: EmfUniversalFontId() {#EmfUniversalFontId__1}


```
 EmfUniversalFontId() 
```

Inicializa una nueva instancia de la clase EmfUniversalFontId

