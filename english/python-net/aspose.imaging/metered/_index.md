---
title: Metered Class
type: docs
weight: 5940
url: /python-net/aspose.imaging/metered/
---

Provides methods to set metered key.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Metered

**Aspose.Imaging Version:** 23.6

The Metered type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [Metered()](#Metered__0) | Initializes a new instance of this class and injects dependency on metered |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_1) | Sets metered public and private key<br/>            If you purchase metered license, when start application, this API should be called, normally, this is enough. <br/>            However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status,<br/>            to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again. |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Gets consumption file size |
| [get_consumption_credit()](#get_consumption_credit__3) | Gets consumption credit |

### Metered() {#Metered__0}


```
 Metered() 
```

Initializes a new instance of this class and injects dependency on metered

### set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_1}


```
 set_metered_key(public_key, private_key) 
```

Sets metered public and private key<br/>            If you purchase metered license, when start application, this API should be called, normally, this is enough. <br/>            However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status,<br/>            to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| public_key | string | public key |
| private_key | string | private key |

### get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Gets consumption file size

**Returns**

| Type | Description |
| :- | :- |
| decimal | consumption quantity |


### get_consumption_credit()  [static] {#get_consumption_credit__3}


```
 get_consumption_credit() 
```

Gets consumption credit

**Returns**

| Type | Description |
| :- | :- |
| decimal | consumption quantity |


