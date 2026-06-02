---
title: "EmfEpsData 类"
type: docs
weight: 50
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---

**Summary:** The EpsData object is a container for EPS data

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfEpsData

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfEpsData()](#EmfEpsData__1) | 初始化 EmfEpsData 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| points | [EmfPoint28To4[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4/) | r/w | 获取或设置一个包含三个 Point28_4 对象（第 2.2.23 节）的数组，该数组使用 28.4 位 FIX 表示法定义输出平行四边形的 <br/>            坐标。 |
| post_script_data | System.Byte | r/w | 获取或设置 PostScript 数据的字节数组。此数组的长度可以 <br/>            从 SizeData 字段计算得到。此数据可能用于渲染图像。 |
| size_data | int | r/w | 获取或设置一个 32 位无符号整数，指定此对象的总大小（字节） |
| 版本 | int | r/w | 获取或设置一个 32 位无符号整数，指定 PostScript 语言级别。此 <br/>            值必须为 0x00000001 |


### Constructor: EmfEpsData() {#EmfEpsData__1}


```
 EmfEpsData() 
```

初始化 EmfEpsData 类的新实例

