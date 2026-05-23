---
title: "Mätad klass"
type: docs
weight: 6150
url: /sv/python-net/aspose.imaging/metered/
---

**Summary:** Provides metered methods for integration

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Metered

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Metered()](#Metered__1) | Initierar en ny instans av denna klass. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Hämtar förbrukningskredit |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Hämtar förbrukningsfilens storlek |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_3) | Sätter mätad offentlig och privat nyckel.<br/>            Om du köper en mätad licens, när du startar applikationen bör detta API anropas, normalt är detta tillräckligt. <br/>            Men om uppladdning av förbrukningsdata alltid misslyckas och överstiger 24 timmar, kommer licensen att sättas till utvärderingsstatus, <br/>            för att undvika detta bör du regelbundet kontrollera licensstatusen, och om den är i utvärderingsstatus, anropa detta API igen. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Initierar en ny instans av denna klass.

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Hämtar förbrukningskredit

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Decimal | förbrukningskvantitet |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Hämtar förbrukningsfilens storlek

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Decimal | förbrukningskvantitet |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_3}


```
 set_metered_key(public_key, private_key) 
```

Sätter mätad offentlig och privat nyckel.<br/>            Om du köper en mätad licens, när du startar applikationen bör detta API anropas, normalt är detta tillräckligt. <br/>            Men om uppladdning av förbrukningsdata alltid misslyckas och överstiger 24 timmar, kommer licensen att sättas till utvärderingsstatus, <br/>            för att undvika detta bör du regelbundet kontrollera licensstatusen, och om den är i utvärderingsstatus, anropa detta API igen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| public_key | string | offentlig nyckel |
| private_key | string | privat nyckel |

