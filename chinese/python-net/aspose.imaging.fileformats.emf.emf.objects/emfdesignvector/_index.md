---
title: "EmfDesignVector 类"
type: docs
weight: 40
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/
---

**Summary:** The DesignVector (section 2.2.3) object defines the design vector, which specifies values for the font axes of a multiple master font.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfDesignVector

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfDesignVector()](#EmfDesignVector__1) | 初始化 EmfDesignVector 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| num_axes | int | r/w | 获取或设置一个 32 位无符号整数，指定在 <br/>            Values 数组中的元素数量。它必须在 0 到 16（含）范围内。 |
| signature | int | r/w | 获取或设置一个 32 位无符号整数，必须设置为值 0x08007664。 |
| values | int[] | r/w | 获取或设置一个可选的 32 位有符号整数数组，指定 <br/>            多主 OpenType 字体的字体轴值。数组中的最大值个数为 16。 |


### Constructor: EmfDesignVector() {#EmfDesignVector__1}


```
 EmfDesignVector() 
```

初始化 EmfDesignVector 类的新实例

