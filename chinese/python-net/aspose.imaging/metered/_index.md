---
title: "计量类"
type: docs
weight: 6150
url: /zh/python-net/aspose.imaging/metered/
---

**Summary:** Provides metered methods for integration

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Metered

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Metered()](#Metered__1) | 初始化此类的新实例。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | 获取消耗积分 |
| [get_consumption_quantity()](#get_consumption_quantity__2) | 获取消耗文件大小 |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_3) | 设置计量的公钥和私钥。<br/>            如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这已足够。<br/>            但是，如果始终无法上传消耗数据且超过 24 小时，许可证将被设置为评估状态，<br/>            为避免这种情况，您应定期检查许可证状态，如果是评估状态，请再次调用此 API。 |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

初始化此类的新实例。

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

获取消耗积分

**Returns**

| Type | Description |
| :- | :- |
| System.Decimal | 消耗数量 |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

获取消耗文件大小

**Returns**

| Type | Description |
| :- | :- |
| System.Decimal | 消耗数量 |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_3}


```
 set_metered_key(public_key, private_key) 
```

设置计量的公钥和私钥。<br/>            如果您购买了计量许可证，在启动应用程序时应调用此 API，通常这已足够。<br/>            但是，如果始终无法上传消耗数据且超过 24 小时，许可证将被设置为评估状态，<br/>            为避免这种情况，您应定期检查许可证状态，如果是评估状态，请再次调用此 API。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| public_key | string | 公钥 |
| private_key | string | 私钥 |

