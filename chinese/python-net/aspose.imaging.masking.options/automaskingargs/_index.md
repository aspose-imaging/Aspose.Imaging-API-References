---
title: "AutoMaskingArgs 类"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.masking.options/automaskingargs/
---

**Summary:** Represents the arguments that are specified for automated masking methods

**Module:** [aspose.imaging.masking.options](/imaging/python-net/aspose.imaging.masking.options/)

**Full Name:** aspose.imaging.masking.options.AutoMaskingArgs

**Inheritance:** IMaskingArgs

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [AutoMaskingArgs()](#AutoMaskingArgs__1) | 初始化 AutoMaskingArgs 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| max_iteration_number | int | r/w | 获取或设置最大迭代次数。 |
| number_of_objects | int | r/w | 获取或设置对象的数量<br/>            将初始图像分割为（可选），默认值为 2（对象和背景）。 |
| objects_points | [Point[][]](/imaging/python-net/aspose.imaging/point[]/) | r/w | 获取或设置属于分离对象的点（可选）<br/>            NumberOfObjects 坐标，属于初始图像的 NumberOfObjects 个对象。<br/>            此参数用于提高分割方法的精度。 |
| objects_rectangles | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | r/w | 获取或设置属于分离对象的对象矩形（可选）。<br/>            此参数用于提高分割方法的精度。 |
| orphaned_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | 获取或设置不再属于任何对象的点（可选）。<br/>            此参数仅在重新分割的情况下使用。 |
| precision | float | r/w | 获取或设置分割方法的精度（可选）。 |


### Constructor: AutoMaskingArgs() {#AutoMaskingArgs__1}


```
 AutoMaskingArgs() 
```

初始化 AutoMaskingArgs 类的新实例

