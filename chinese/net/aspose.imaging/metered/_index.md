---
title: "类 Metered"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.Metered 类。提供用于集成的计量方法。"
type: docs
weight: 11150
url: /zh/net/aspose.imaging/metered/
---
## Metered class

提供用于集成的计量方法

提供设置计量密钥的方法。

```csharp
public class Metered
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Metered](metered/)() | 初始化此类的新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Equals](../../aspose.imaging/metered/equals/)(object) | 确定指定的 Object 是否等于此实例。 |
| [SetMeteredKey](../../aspose.imaging/metered/setmeteredkey/)(string, string) | 设置计量公钥和私钥。如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这已足够。然而，如果始终无法上传使用数据且超过 24 小时，许可证将被设为评估状态。为避免此情况，您应定期检查许可证状态，如果是评估状态，请再次调用此 API。 |
| static [GetConsumptionCredit](../../aspose.imaging/metered/getconsumptioncredit/)() | 获取消耗额度 |
| static [GetConsumptionQuantity](../../aspose.imaging/metered/getconsumptionquantity/)() | 获取消耗文件大小 |

## 示例

在此示例中，将尝试设置计量公钥和私钥

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### 另请参见

* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


