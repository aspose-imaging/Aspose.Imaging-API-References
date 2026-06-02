---
title: "EmfPlusCurveAdjustments"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione CurveAdjustments definisce le regolazioni che possono essere applicate alla curva colore di un'immagine."
type: docs
weight: 16
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCurveAdjustments extends System.Enum
```

L'enumerazione CurveAdjustments definisce le regolazioni che possono essere applicate alla curva colore di un'immagine.
## Campi

| Campo | Descrizione |
| --- | --- |
| [AdjustExposure](#AdjustExposure) | Specifica la simulazione dell'aumento o della diminuzione dell'esposizione di un'immagine. |
| [AdjustDensity](#AdjustDensity) | Specifica la simulazione dell'aumento o della diminuzione della densità di un'immagine. |
| [AdjustContrast](#AdjustContrast) | Specifica un aumento o una diminuzione del contrasto di un'immagine. |
| [AdjustHighlight](#AdjustHighlight) | Specifica un aumento o una diminuzione del valore di un canale colore di un'immagine, se quel canale ha già un valore superiore a metà dell'intensità. |
| [AdjustShadow](#AdjustShadow) | Specifica un aumento o una diminuzione del valore di un canale colore di un'immagine, se quel canale ha già un valore inferiore a metà dell'intensità. |
| [AdjustMidtone](#AdjustMidtone) | Specifica una regolazione che schiarisce o scurisce un'immagine. |
| [AdjustWhiteSaturation](#AdjustWhiteSaturation) | Specifica una regolazione della saturazione bianca di un'immagine, definita come il valore massimo nell'intervallo di intensità per un dato canale di colore, il cui intervallo è tipicamente da 0 a 255. |
| [AdjustBlackSaturation](#AdjustBlackSaturation) | Specifica una regolazione della saturazione nera di un'immagine, che è il valore minimo nell'intervallo di intensità per un dato canale di colore, tipicamente da 0 a 255. |
### AdjustExposure {#AdjustExposure}
```
public static final int AdjustExposure
```


Specifica la simulazione dell'aumento o della diminuzione dell'esposizione di un'immagine.

### AdjustDensity {#AdjustDensity}
```
public static final int AdjustDensity
```


Specifica la simulazione dell'aumento o della diminuzione della densità di un'immagine.

### AdjustContrast {#AdjustContrast}
```
public static final int AdjustContrast
```


Specifica un aumento o una diminuzione del contrasto di un'immagine.

### AdjustHighlight {#AdjustHighlight}
```
public static final int AdjustHighlight
```


Specifica un aumento o una diminuzione del valore di un canale di colore di un'immagine, se quel canale ha già un valore superiore alla metà dell'intensità. Questa regolazione può essere usata per aumentare la definizione nelle aree chiare di un'immagine senza influenzare le aree scure.

### AdjustShadow {#AdjustShadow}
```
public static final int AdjustShadow
```


Specifica un aumento o una diminuzione del valore di un canale di colore di un'immagine, se quel canale ha già un valore inferiore alla metà dell'intensità. Questa regolazione può essere usata per aumentare la definizione nelle aree scure di un'immagine senza influenzare le aree chiare.

### AdjustMidtone {#AdjustMidtone}
```
public static final int AdjustMidtone
```


Specifica una regolazione che schiarisce o scurisce un'immagine. I valori dei canali di colore nel mezzo dell'intervallo di intensità vengono modificati più di quelli vicino agli estremi minimo o massimo dell'intensità. Questa regolazione può essere usata per schiarire o scurire un'immagine senza perdere il contrasto tra le parti più scure e più chiare dell'immagine.

### AdjustWhiteSaturation {#AdjustWhiteSaturation}
```
public static final int AdjustWhiteSaturation
```


Specifica una regolazione della saturazione bianca di un'immagine, definita come il valore massimo nell'intervallo di intensità per un dato canale di colore, il cui intervallo è tipicamente da 0 a 255.

--------------------

Ad esempio, un valore di regolazione della saturazione bianca di 240 specifica che i valori dei canali di colore nell'intervallo da 0 a 240 vengono regolati in modo da distribuirsi sull'intervallo da 0 a 255, con i valori dei canali di colore superiori a 240 impostati a 255.

### AdjustBlackSaturation {#AdjustBlackSaturation}
```
public static final int AdjustBlackSaturation
```


Specifica una regolazione della saturazione nera di un'immagine, che è il valore minimo nell'intervallo di intensità per un dato canale di colore, tipicamente da 0 a 255.

--------------------

Ad esempio, un valore di regolazione della saturazione nera di 15 specifica che i valori dei canali di colore nell'intervallo da 15 a 255 vengono regolati in modo da distribuirsi sull'intervallo da 0 a 255, con i valori dei canali di colore inferiori a 15 impostati a 0.

