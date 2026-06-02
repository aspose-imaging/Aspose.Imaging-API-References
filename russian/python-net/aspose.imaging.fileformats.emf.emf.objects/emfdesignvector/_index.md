---
title: "Класс EmfDesignVector"
type: docs
weight: 40
url: /ru/python-net/aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/
---

**Summary:** The DesignVector (section 2.2.3) object defines the design vector, which specifies values for the font axes of a multiple master font.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfDesignVector

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfDesignVector()](#EmfDesignVector__1) | Инициализирует новый экземпляр класса EmfDesignVector |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| num_axes | int | r/w | Получает или задает 32-битное беззнаковое целое, которое указывает количество элементов в <br/>            массиве Values. Оно ДОЛЖНО находиться в диапазоне от 0 до 16 включительно. |
| signature | int | r/w | Получает или задает 32-битное беззнаковое целое, которое ДОЛЖНО быть установлено в значение 0x08007664. |
| values | int[] | r/w | Получает или задает необязательный массив 32-битных знаковых целых, который указывает значения <br/>            осей шрифта многомастера OpenType. Максимальное количество значений в массиве — 16. |


### Constructor: EmfDesignVector() {#EmfDesignVector__1}


```
 EmfDesignVector() 
```

Инициализирует новый экземпляр класса EmfDesignVector

