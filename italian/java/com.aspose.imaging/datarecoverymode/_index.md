---
title: "DataRecoveryMode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "La modalità di recupero dati."
type: docs
weight: 38
url: /it/java/com.aspose.imaging/datarecoverymode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DataRecoveryMode extends System.Enum
```

La modalità di recupero dati.
## Campi

| Campo | Descrizione |
| --- | --- |
| [None](#None) | Nessun recupero dati è implicito. |
| [ConsistentRecover](#ConsistentRecover) | La modalità di recupero coerente tenta di recuperare tutti i dati finché la corruzione non rompe il formato del file e consente una corretta elaborazione successiva. |
| [MaximalRecover](#MaximalRecover) | La modalità di recupero massimale recupera tutti i dati anche se il formato del file ha una struttura corrotta e l'elaborazione successiva può produrre effetti inattesi. |
### None {#None}
```
public static final int None
```


Nessun recupero dati è implicito. Ogni volta che il formato del file contiene dati corrotti viene sollevata l'eccezione appropriata.

### ConsistentRecover {#ConsistentRecover}
```
public static final int ConsistentRecover
```


La modalità di recupero coerente tenta di recuperare tutti i dati finché la corruzione non rompe il formato del file e consente una corretta elaborazione successiva.

### MaximalRecover {#MaximalRecover}
```
public static final int MaximalRecover
```


La modalità di recupero massimale recupera tutti i dati anche se il formato del file ha una struttura corrotta e l'elaborazione successiva può produrre effetti inattesi.

