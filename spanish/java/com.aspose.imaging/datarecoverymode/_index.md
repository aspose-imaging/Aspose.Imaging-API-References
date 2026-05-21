---
title: "DataRecoveryMode"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El modo de recuperación de datos."
type: docs
weight: 38
url: /es/java/com.aspose.imaging/datarecoverymode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DataRecoveryMode extends System.Enum
```

El modo de recuperación de datos.
## Campos

| Campo | Descripción |
| --- | --- |
| [None](#None) | No se implica recuperación de datos. |
| [ConsistentRecover](#ConsistentRecover) | El modo de recuperación consistente intenta recuperar todos los datos siempre que la corrupción no rompa el formato del archivo y permite un procesamiento posterior correcto. |
| [MaximalRecover](#MaximalRecover) | El modo de recuperación máximo recupera todos los datos incluso si el formato del archivo tiene una estructura corrupta y el procesamiento posterior puede producir efectos no deseados. |
### None {#None}
```
public static final int None
```


No se implica recuperación de datos. Siempre que el formato del archivo tenga datos corruptos, se lanza la excepción apropiada.

### ConsistentRecover {#ConsistentRecover}
```
public static final int ConsistentRecover
```


El modo de recuperación consistente intenta recuperar todos los datos siempre que la corrupción no rompa el formato del archivo y permite un procesamiento posterior correcto.

### MaximalRecover {#MaximalRecover}
```
public static final int MaximalRecover
```


El modo de recuperación máximo recupera todos los datos incluso si el formato del archivo tiene una estructura corrupta y el procesamiento posterior puede producir efectos no deseados.

