---
title: "Clase EmfDesignVector"
type: docs
weight: 40
url: /es/python-net/aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/
---

**Summary:** The DesignVector (section 2.2.3) object defines the design vector, which specifies values for the font axes of a multiple master font.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfDesignVector

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [EmfDesignVector()](#EmfDesignVector__1) | Inicializa una nueva instancia de la clase EmfDesignVector |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| num_axes | int | r/w | Obtiene o establece un entero sin signo de 32 bits que especifica el número de elementos en <br/>            la matriz Values. DEBE estar en el rango de 0 a 16, inclusive |
| signature | int | r/w | Obtiene o establece un entero sin signo de 32 bits que DEBE establecerse al valor 0x08007664. |
| values | int[] | r/w | Obtiene o establece una matriz opcional de enteros con signo de 32 bits que especifican los valores <br/>            de los ejes de fuente de una fuente OpenType de maestro múltiple. El número máximo de valores en la matriz es 16. |


### Constructor: EmfDesignVector() {#EmfDesignVector__1}


```
 EmfDesignVector() 
```

Inicializa una nueva instancia de la clase EmfDesignVector

