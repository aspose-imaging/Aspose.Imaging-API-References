---
title: "Måttbaserad"
second_title: "Aspose.Imaging för Java API-referens"
description: "Tillhandahåller mätade metoder för integration"
type: docs
weight: 74
url: /sv/java/com.aspose.imaging/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Tillhandahåller mätade metoder för integration

I det här exemplet kommer ett försök att sätta den meterade offentliga och privata nyckeln att göras.

`// the component jar file: Metered metered = new Metered(); metered.setMeteredKey("PublicKey", "PrivateKey"); `
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Metered()](#Metered--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Hämtar förbrukningsfilens storlek |
| [getConsumptionCredit()](#getConsumptionCredit--) | Hämtar förbrukningskredit |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Ställer in meterad offentlig och privat nyckel. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det angivna Object är lika med den här instansen. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Hämtar förbrukningsfilens storlek

**Returns:**
java.math.BigDecimal - förbrukningsfilens storlek
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Hämtar förbrukningskredit

**Returns:**
java.math.BigDecimal - förbrukningsmängd
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Ställer in meterad offentlig och privat nyckel.

Om du köper en meterad licens, bör detta API anropas när applikationen startas; normalt räcker det. Men om uppladdning av förbrukningsdata alltid misslyckas och överstiger 24 timmar, kommer licensen att sättas till utvärderingsstatus. För att undvika detta bör du regelbundet kontrollera licensstatusen och, om den är i utvärderingsstatus, anropa detta API igen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicKey | java.lang.String | offentlig nyckel |
| privateKey | java.lang.String | privat nyckel |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om det angivna Object är lika med den här instansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Objectet att jämföra med den här instansen. |

**Returns:**
boolean - `true` om det angivna Object är lika med den här instansen; annars `false`.
