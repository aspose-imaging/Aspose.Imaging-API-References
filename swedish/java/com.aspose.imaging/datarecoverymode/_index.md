---
title: "DataRecoveryMode"
second_title: "Aspose.Imaging för Java API-referens"
description: "Återställningsläget för data."
type: docs
weight: 38
url: /sv/java/com.aspose.imaging/datarecoverymode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DataRecoveryMode extends System.Enum
```

Återställningsläget för data.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [None](#None) | Ingen dataåterställning förutsätts. |
| [ConsistentRecover](#ConsistentRecover) | Det konsekventa återställningsläget försöker återställa all data så länge korruptionen inte bryter filformatet och möjliggör korrekt vidare bearbetning. |
| [MaximalRecover](#MaximalRecover) | Det maximala återställningsläget återställer all data även om filformatet har en korrupt struktur och vidare bearbetning kan ge oönskade effekter. |
### None {#None}
```
public static final int None
```


Ingen dataåterställning förutsätts. När filformatet har korrupt data kastas lämpligt undantag.

### ConsistentRecover {#ConsistentRecover}
```
public static final int ConsistentRecover
```


Det konsekventa återställningsläget försöker återställa all data så länge korruptionen inte bryter filformatet och möjliggör korrekt vidare bearbetning.

### MaximalRecover {#MaximalRecover}
```
public static final int MaximalRecover
```


Det maximala återställningsläget återställer all data även om filformatet har en korrupt struktur och vidare bearbetning kan ge oönskade effekter.

