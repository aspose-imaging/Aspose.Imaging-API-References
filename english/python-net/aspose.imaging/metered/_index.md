---
title: Metered Class
type: docs
weight: 6090
url: /python-net/aspose.imaging/metered/
---

**Summary:** Provides metered methods for integration

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Metered

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Metered()](#Metered__1) | Initializes a new instance of this class. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Gets consumption credit |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Gets consumption file size |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_3) | Sets metered public and private key.<br/>            If you purchase metered license, when start application, this API should be called, normally, this is enough. <br/>            However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, <br/>            to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Initializes a new instance of this class.

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Gets consumption credit

**Returns**

| Type | Description |
| :- | :- |
| System.Decimal | consumption quantity |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Gets consumption file size

**Returns**

| Type | Description |
| :- | :- |
| System.Decimal | consumption quantity |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_3}


```
 set_metered_key(public_key, private_key) 
```

Sets metered public and private key.<br/>            If you purchase metered license, when start application, this API should be called, normally, this is enough. <br/>            However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, <br/>            to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| public_key | string | public key |
| private_key | string | private key |

