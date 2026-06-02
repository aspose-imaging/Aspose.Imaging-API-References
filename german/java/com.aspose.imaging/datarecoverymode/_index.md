---
title: "DataRecoveryMode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der Datenwiederherstellungsmodus."
type: docs
weight: 38
url: /de/java/com.aspose.imaging/datarecoverymode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DataRecoveryMode extends System.Enum
```

Der Datenwiederherstellungsmodus.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [None](#None) | Keine Datenwiederherstellung ist impliziert. |
| [ConsistentRecover](#ConsistentRecover) | Der konsistente Wiederherstellungsmodus versucht, alle Daten wiederherzustellen, solange die Beschädigung das Dateiformat nicht bricht und eine korrekte Weiterverarbeitung ermöglicht. |
| [MaximalRecover](#MaximalRecover) | Der maximale Wiederherstellungsmodus stellt alle Daten wieder her, selbst wenn das Dateiformat eine beschädigte Struktur aufweist, und die Weiterverarbeitung kann unbeabsichtigte Effekte erzeugen. |
### None {#None}
```
public static final int None
```


Keine Datenwiederherstellung ist impliziert. Immer wenn das Dateiformat beschädigte Daten enthält, wird die entsprechende Ausnahme ausgelöst.

### ConsistentRecover {#ConsistentRecover}
```
public static final int ConsistentRecover
```


Der konsistente Wiederherstellungsmodus versucht, alle Daten wiederherzustellen, solange die Beschädigung das Dateiformat nicht bricht und eine korrekte Weiterverarbeitung ermöglicht.

### MaximalRecover {#MaximalRecover}
```
public static final int MaximalRecover
```


Der maximale Wiederherstellungsmodus stellt alle Daten wieder her, selbst wenn das Dateiformat eine beschädigte Struktur aufweist, und die Weiterverarbeitung kann unbeabsichtigte Effekte erzeugen.

