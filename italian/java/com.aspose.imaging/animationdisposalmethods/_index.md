---
title: "AnimationDisposalMethods"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Indica il modo in cui la grafica deve essere trattata dopo essere stata visualizzata."
type: docs
weight: 11
url: /it/java/com.aspose.imaging/animationdisposalmethods/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class AnimationDisposalMethods extends System.Enum
```

Indica il modo in cui la grafica deve essere trattata dopo essere stata visualizzata.
## Campi

| Campo | Descrizione |
| --- | --- |
| [PRESERVE](#PRESERVE) | Non eliminare. |
| [BACKGROUND](#BACKGROUND) | Ripristina al colore di sfondo. |
| [PREVIOUS](#PREVIOUS) | Ripristina al precedente. |
### PRESERVE {#PRESERVE}
```
public static final int PRESERVE
```


Non eliminare. Il grafico deve rimanere al suo posto.

### BACKGROUND {#BACKGROUND}
```
public static final int BACKGROUND
```


Ripristina al colore di sfondo. L'area utilizzata dal grafico deve essere ripristinata al colore di sfondo.

### PREVIOUS {#PREVIOUS}
```
public static final int PREVIOUS
```


Ripristina al precedente. Il decoder deve ripristinare l'area sovrascritta dal grafico con ciò che era presente prima del rendering del grafico.

