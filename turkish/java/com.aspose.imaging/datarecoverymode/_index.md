---
title: "DataRecoveryMode"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Veri kurtarma modu."
type: docs
weight: 38
url: /tr/java/com.aspose.imaging/datarecoverymode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DataRecoveryMode extends System.Enum
```

Veri kurtarma modu.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [None](#None) | Veri kurtarma uygulanmaz. |
| [ConsistentRecover](#ConsistentRecover) | Tutarlı kurtarma modu, bozulmanın dosya formatını bozmadığı sürece tüm verileri kurtarmaya çalışır ve doğru sonraki işleme izin verir. |
| [MaximalRecover](#MaximalRecover) | Maksimum kurtarma modu, dosya formatının bozuk bir yapısı olsa bile tüm verileri kurtarır ve sonraki işleme beklenmeyen etkiler doğurabilir. |
### None {#None}
```
public static final int None
```


Veri kurtarma uygulanmaz. Dosya formatında bozuk veri olduğunda uygun istisna fırlatılır.

### ConsistentRecover {#ConsistentRecover}
```
public static final int ConsistentRecover
```


Tutarlı kurtarma modu, bozulmanın dosya formatını bozmadığı sürece tüm verileri kurtarmaya çalışır ve doğru sonraki işleme izin verir.

### MaximalRecover {#MaximalRecover}
```
public static final int MaximalRecover
```


Maksimum kurtarma modu, dosya formatının bozuk bir yapısı olsa bile tüm verileri kurtarır ve sonraki işleme beklenmeyen etkiler doğurabilir.

