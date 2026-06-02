---
title: "Abgerechnet"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt messbare Methoden für die Integration bereit"
type: docs
weight: 74
url: /de/java/com.aspose.imaging/metered/
---
**Inheritance:**
java.lang.Object
```
public class Metered
```

Stellt messbare Methoden für die Integration bereit

In diesem Beispiel wird versucht, den abgerechneten öffentlichen und privaten Schlüssel festzulegen.

`// the component jar file: Metered metered = new Metered(); metered.setMeteredKey("PublicKey", "PrivateKey"); `
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Metered()](#Metered--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Ermittelt die Dateigröße des Verbrauchs. |
| [getConsumptionCredit()](#getConsumptionCredit--) | Ermittelt das Verbrauchsguthaben. |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Setzt den abgerechneten öffentlichen und privaten Schlüssel. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene Objekt dieser Instanz gleich ist. |
### Metered() {#Metered--}
```
public Metered()
```


### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static BigDecimal getConsumptionQuantity()
```


Ermittelt die Dateigröße des Verbrauchs.

**Returns:**
java.math.BigDecimal - Verbrauchsdateigröße
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static BigDecimal getConsumptionCredit()
```


Ermittelt das Verbrauchsguthaben.

**Returns:**
java.math.BigDecimal - Verbrauchsmenge
### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Setzt den abgerechneten öffentlichen und privaten Schlüssel.

Wenn Sie eine abgerechnete Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. Wenn jedoch immer wieder das Hochladen der Verbrauchsdaten fehlschlägt und 24 Stunden überschritten werden, wird die Lizenz auf den Evaluierungsstatus gesetzt. Um einen solchen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen und bei Evaluierungsstatus diese API erneut aufrufen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| publicKey | java.lang.String | öffentlicher Schlüssel |
| privateKey | java.lang.String | privater Schlüssel |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob das angegebene Objekt dieser Instanz gleich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Das Objekt, das mit dieser Instanz verglichen wird. |

**Returns:**
boolean - `true`, wenn das angegebene Objekt dieser Instanz gleich ist; andernfalls `false`.
