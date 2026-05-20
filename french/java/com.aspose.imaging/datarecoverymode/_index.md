---
title: "DataRecoveryMode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Le mode de récupération des données."
type: docs
weight: 38
url: /fr/java/com.aspose.imaging/datarecoverymode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DataRecoveryMode extends System.Enum
```

Le mode de récupération des données.
## Champs

| Champ | Description |
| --- | --- |
| [None](#None) | Aucune récupération de données n'est implicite. |
| [ConsistentRecover](#ConsistentRecover) | Le mode de récupération cohérent tente de récupérer toutes les données tant que la corruption ne casse pas le format du fichier et permet un traitement ultérieur correct. |
| [MaximalRecover](#MaximalRecover) | Le mode de récupération maximal récupère toutes les données même si le format du fichier possède une structure corrompue et le traitement ultérieur peut entraîner des effets inattendus. |
### None {#None}
```
public static final int None
```


Aucune récupération de données n'est implicite. Chaque fois que le format du fichier contient des données corrompues, l'exception appropriée est levée.

### ConsistentRecover {#ConsistentRecover}
```
public static final int ConsistentRecover
```


Le mode de récupération cohérent tente de récupérer toutes les données tant que la corruption ne casse pas le format du fichier et permet un traitement ultérieur correct.

### MaximalRecover {#MaximalRecover}
```
public static final int MaximalRecover
```


Le mode de récupération maximal récupère toutes les données même si le format du fichier possède une structure corrompue et le traitement ultérieur peut entraîner des effets inattendus.

