---
title: "Blend 类"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Blend 类。定义混合模式。此类不能被继承"
type: docs
weight: 120
url: /zh/net/aspose.imaging/blend/
---
## Blend class

定义混合模式。此类不可被继承。

```csharp
public sealed class Blend
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Blend](blend/#constructor)() | 初始化 `Blend` 类的新实例。factor 和 blend 数组中的元素数量将为 1。 |
| [Blend](blend/#constructor_1)(int) | 使用指定数量的因子和位置初始化 `Blend` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Factors](../../aspose.imaging/blend/factors/) { get; set; } | 获取或设置渐变的 blend 因子数组。 |
| [Positions](../../aspose.imaging/blend/positions/) { get; set; } | 获取或设置渐变的 blend 位置数组。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.imaging/blend/equals/)(object) | 测试指定的对象是否为 `Blend` 类且等价于此 `Blend` 类。 |
| override [GetHashCode](../../aspose.imaging/blend/gethashcode/)() | 返回此实例的哈希码。 |

## 备注

典型的 blend 类用法是为画笔定义混合模式。因此应仔细初始化 blend 属性。不允许空数组。如果 blend 因子或位置数组为空或长度不一致，画笔将抛出相应的异常。如果位置数组中有两个或更多元素，则第一个元素应为 0，最后一个应为 1。

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


