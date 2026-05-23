---
title: "Classe Metered"
type: docs
weight: 6150
url: /it/python-net/aspose.imaging/metered/
---

**Summary:** Provides metered methods for integration

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Metered

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [Metered()](#Metered__1) | Inizializza una nuova istanza di questa classe. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Ottiene il credito di consumo |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Ottiene la dimensione del file di consumo |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_3) | Imposta la chiave pubblica e privata metered.<br/>            Se acquisti una licenza metered, all'avvio dell'applicazione, questa API dovrebbe essere chiamata; normalmente è sufficiente. <br/>            Tuttavia, se il caricamento dei dati di consumo fallisce continuamente e supera le 24 ore, la licenza verrà impostata allo stato di valutazione, <br/>            per evitare tale caso, dovresti controllare regolarmente lo stato della licenza; se è in stato di valutazione, chiama nuovamente questa API. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Inizializza una nuova istanza di questa classe.

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Ottiene il credito di consumo

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Decimal | quantità di consumo |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Ottiene la dimensione del file di consumo

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Decimal | quantità di consumo |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_3}


```
 set_metered_key(public_key, private_key) 
```

Imposta la chiave pubblica e privata metered.<br/>            Se acquisti una licenza metered, all'avvio dell'applicazione, questa API dovrebbe essere chiamata; normalmente è sufficiente. <br/>            Tuttavia, se il caricamento dei dati di consumo fallisce continuamente e supera le 24 ore, la licenza verrà impostata allo stato di valutazione, <br/>            per evitare tale caso, dovresti controllare regolarmente lo stato della licenza; se è in stato di valutazione, chiama nuovamente questa API.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| public_key | string | chiave pubblica |
| private_key | string | chiave privata |

