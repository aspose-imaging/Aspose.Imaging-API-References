---
title: "EmfPlusCompositingQuality"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione CompositingQuality definisce i livelli di qualità per la creazione di immagini composite"
type: docs
weight: 15
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCompositingQuality extends System.Enum
```

L'enumerazione CompositingQuality definisce i livelli di qualità per la creazione di immagini composite
## Campi

| Campo | Descrizione |
| --- | --- |
| [CompositingQualityDefault](#CompositingQualityDefault) | Non viene eseguita alcuna correzione gamma. |
| [CompositingQualityHighSpeed](#CompositingQualityHighSpeed) | Non viene eseguita alcuna correzione gamma. |
| [CompositingQualityHighQuality](#CompositingQualityHighQuality) | Viene eseguita la correzione gamma. |
| [CompositingQualityGammaCorrected](#CompositingQualityGammaCorrected) | Abilita la correzione gamma per un compositing di qualità superiore a velocità ridotta. |
| [CompositingQualityAssumeLinear](#CompositingQualityAssumeLinear) | Non viene eseguita alcuna correzione gamma; tuttavia, l'uso di valori lineari produce una qualità migliore rispetto al valore predefinito a una velocità leggermente inferiore. |
### CompositingQualityDefault {#CompositingQualityDefault}
```
public static final byte CompositingQualityDefault
```


Non viene eseguita alcuna correzione gamma. La correzione gamma controlla la luminosità e il contrasto complessivi di un'immagine. Senza correzione gamma, le immagini composte possono apparire troppo chiare o troppo scure.

### CompositingQualityHighSpeed {#CompositingQualityHighSpeed}
```
public static final byte CompositingQualityHighSpeed
```


Non viene eseguita alcuna correzione gamma. La velocità di compositing è privilegiata a scapito della qualità. Per quanto riguarda il risultato, non vi è alcuna differenza tra questo valore e CompositingQualityDefault.

### CompositingQualityHighQuality {#CompositingQualityHighQuality}
```
public static final byte CompositingQualityHighQuality
```


Viene eseguita la correzione gamma. La qualità del compositing è privilegiata a scapito della velocità.

### CompositingQualityGammaCorrected {#CompositingQualityGammaCorrected}
```
public static final byte CompositingQualityGammaCorrected
```


Abilita la correzione gamma per un compositing di qualità superiore a velocità ridotta. Per quanto riguarda il risultato, non vi è alcuna differenza tra questo valore e CompositingQualityHighQuality.

### CompositingQualityAssumeLinear {#CompositingQualityAssumeLinear}
```
public static final byte CompositingQualityAssumeLinear
```


Non viene eseguita alcuna correzione gamma; tuttavia, l'uso di valori lineari produce una qualità migliore rispetto al valore predefinito a una velocità leggermente inferiore.

