---
title: "A consumo"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Fornisce metodi misurati per l'integrazione"
type: docs
weight: 74
url: /it/java/com.aspose.imaging/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Fornisce metodi misurati per l'integrazione

In questo esempio, verrà tentato di impostare la chiave pubblica e privata a consumo

`// the component jar file: Metered metered = new Metered(); metered.setMeteredKey("PublicKey", "PrivateKey"); `
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Metered()](#Metered--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Ottiene la dimensione del file di consumo |
| [getConsumptionCredit()](#getConsumptionCredit--) | Ottiene il credito di consumo |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Imposta la chiave pubblica e privata a consumo. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'Object specificato è uguale a questa istanza. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Ottiene la dimensione del file di consumo

**Returns:**
java.math.BigDecimal - dimensione del file di consumo
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Ottiene il credito di consumo

**Returns:**
java.math.BigDecimal - quantità di consumo
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Imposta la chiave pubblica e privata a consumo.

Se acquisti una licenza a consumo, all'avvio dell'applicazione questa API dovrebbe essere chiamata; normalmente è sufficiente. Tuttavia, se il caricamento dei dati di consumo fallisce continuamente e supera le 24 ore, la licenza verrà impostata in stato di valutazione; per evitare ciò, dovresti controllare regolarmente lo stato della licenza e, se è in stato di valutazione, chiamare nuovamente questa API.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| publicKey | java.lang.String | chiave pubblica |
| privateKey | java.lang.String | chiave privata |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se l'Object specificato è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'Object da confrontare con questa istanza. |

**Returns:**
boolean - `true` se l'Object specificato è uguale a questa istanza; altrimenti, `false`.
