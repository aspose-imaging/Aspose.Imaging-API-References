---
title: Metered
second_title: Aspose.Imaging for Java API Reference
description: Provides metered methods for integration
type: docs
weight: 75
url: /java/com.aspose.imaging/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Provides metered methods for integration

In this example, an attempt will be made to set metered public and private key

`// the component jar file: Metered metered = new Metered(); metered.setMeteredKey("PublicKey", "PrivateKey"); `
## Constructors

| Constructor | Description |
| --- | --- |
| [Metered()](#Metered--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Gets consumption file size |
| [getConsumptionCredit()](#getConsumptionCredit--) | Gets consumption credit |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Sets metered public and private key. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object, is equal to this instance. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Gets consumption file size

**Returns:**
java.math.BigDecimal - consumption file size
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Gets consumption credit

**Returns:**
java.math.BigDecimal - consumption quantity
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Sets metered public and private key.

If you purchase metered license, when start application, this API should be called, normally, this is enough. However, if always fail to upload consumption data and exceed 24 hours, the license will be set to evaluation status, to avoid such case, you should regularly check the license status, if it is evaluation status, call this API again.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| publicKey | java.lang.String | public key |
| privateKey | java.lang.String | private key |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified Object, is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The Object to compare with this instance. |

**Returns:**
boolean - `true` if the specified Object is equal to this instance; otherwise, `false`.
