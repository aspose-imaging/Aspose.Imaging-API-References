---
title: "Metered"
second_title: "Aspose.Imaging for Java API 参考"
description: "提供用于集成的计量方法"
type: docs
weight: 74
url: /zh/java/com.aspose.imaging/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

提供用于集成的计量方法

在此示例中，将尝试设置计量的公钥和私钥。

`// the component jar file: Metered metered = new Metered(); metered.setMeteredKey(\"PublicKey\", \"PrivateKey\"); `
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Metered()](#Metered--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 获取消耗文件大小 |
| [getConsumptionCredit()](#getConsumptionCredit--) | 获取消耗额度 |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | 设置计量的公钥和私钥。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 Object 是否等于此实例。 |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


获取消耗文件大小

**Returns:**
java.math.BigDecimal - 消耗文件大小
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


获取消耗额度

**Returns:**
java.math.BigDecimal - 消耗数量
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


设置计量的公钥和私钥。

如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这已足够。然而，如果始终无法上传消耗数据且超过 24 小时，许可证将被设置为评估状态。为避免这种情况，您应定期检查许可证状态，如果是评估状态，请再次调用此 API。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| publicKey | java.lang.String | 公钥 |
| privateKey | java.lang.String | 私钥 |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


确定指定的 Object 是否等于此实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 用于与此实例比较的 Object。 |

**Returns:**
boolean - 如果指定的 Object 等于此实例则为 `true`；否则为 `false`。
