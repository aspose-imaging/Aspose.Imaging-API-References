---
title: "Metered Klasse"
type: docs
weight: 6150
url: /de/python-net/aspose.imaging/metered/
---

**Summary:** Provides metered methods for integration

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Metered

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Metered()](#Metered__1) | Initialisiert eine neue Instanz dieser Klasse. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_consumption_credit()](#get_consumption_credit__1) | Ermittelt Verbrauchsguthaben |
| [get_consumption_quantity()](#get_consumption_quantity__2) | Ermittelt Verbrauchsdateigröße |
| [set_metered_key(public_key, private_key)](#set_metered_key_public_key_private_key_3) | Setzt den gemessenen öffentlichen und privaten Schlüssel.<br/>            Wenn Sie eine gemessene Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden, normalerweise reicht das aus. <br/>            Wenn jedoch das Hochladen der Verbrauchsdaten ständig fehlschlägt und 24 Stunden überschreitet, wird die Lizenz auf den Evaluierungsstatus gesetzt, <br/>            um einen solchen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf. |


### Constructor: Metered() {#Metered__1}


```
 Metered() 
```

Initialisiert eine neue Instanz dieser Klasse.

### Method: get_consumption_credit()  [static] {#get_consumption_credit__1}


```
 get_consumption_credit() 
```

Ermittelt Verbrauchsguthaben

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Decimal | Verbrauchsmenge |


### Method: get_consumption_quantity()  [static] {#get_consumption_quantity__2}


```
 get_consumption_quantity() 
```

Ermittelt Verbrauchsdateigröße

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Decimal | Verbrauchsmenge |


### Method: set_metered_key(public_key, private_key) {#set_metered_key_public_key_private_key_3}


```
 set_metered_key(public_key, private_key) 
```

Setzt den gemessenen öffentlichen und privaten Schlüssel.<br/>            Wenn Sie eine gemessene Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden, normalerweise reicht das aus. <br/>            Wenn jedoch das Hochladen der Verbrauchsdaten ständig fehlschlägt und 24 Stunden überschreitet, wird die Lizenz auf den Evaluierungsstatus gesetzt, <br/>            um einen solchen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| public_key | string | öffentlicher Schlüssel |
| private_key | string | privater Schlüssel |

