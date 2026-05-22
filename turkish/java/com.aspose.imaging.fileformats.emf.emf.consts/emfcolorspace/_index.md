---
title: "EmfColorSpace"
second_title: "Aspose.Imaging for Java API Referansı"
description: "ColorSpace sayımı, renk doğrulamasını ne zaman açıp kapatacağınızı ve dönüşümleri ne zaman sileceğinizi belirtmek için kullanılır."
type: docs
weight: 15
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfcolorspace/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfColorSpace extends System.Enum
```

ColorSpace sayımı, renk doğrulamasının ne zaman açılıp kapatılacağını ve dönüşümlerin ne zaman silineceğini belirtmek için kullanılır.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CS_ENABLE](#CS-ENABLE) | Renkleri hedef cihazın renk gamına eşler. |
| [CS_DISABLE](#CS-DISABLE) | Renk doğrulamasını devre dışı bırakır. |
| [CS_DELETE_TRANSFORM](#CS-DELETE-TRANSFORM) | Hedef profil için renk yönetimi etkinleştirilmişse, bunu devre dışı bırakır ve birleştirilmiş dönüşümü siler. |
### CS_ENABLE {#CS-ENABLE}
```
public static final int CS_ENABLE
```


Renkleri hedef cihazın renk gamına eşler. Bu, renk doğrulamasını etkinleştirir. Oynatma cihaz bağlamına gönderilen sonraki tüm çizim komutları, renkleri hedef cihazda görünecek şekilde işler.

### CS_DISABLE {#CS-DISABLE}
```
public static final int CS_DISABLE
```


Renk doğrulamasını devre dışı bırakır.

### CS_DELETE_TRANSFORM {#CS-DELETE-TRANSFORM}
```
public static final int CS_DELETE_TRANSFORM
```


Hedef profil için renk yönetimi etkinleştirilmişse, bunu devre dışı bırakır ve birleştirilmiş dönüşümü siler.

