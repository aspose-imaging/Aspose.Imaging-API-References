---
title: "EmfPlusLineCapType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'enumerazione LineCapType definisce i tipi di capolinea da utilizzare alle estremità delle linee disegnate con penne grafiche."
type: docs
weight: 31
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusLineCapType extends System.Enum
```

L'enumerazione LineCapType definisce i tipi di capolinea da utilizzare alle estremità delle linee disegnate con penne grafiche.

--------------------

I cap di linea della grafica sono specificati dagli oggetti [EmfPlusPen](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen) (sezione 2.2.1.7).
## Campi

| Campo | Descrizione |
| --- | --- |
| [LineCapTypeFlat](#LineCapTypeFlat) | Specifica un cap di linea quadrato. |
| [LineCapTypeSquare](#LineCapTypeSquare) | Specifica un cappuccio di linea quadrato. |
| [LineCapTypeRound](#LineCapTypeRound) | Specifica un cap di linea circolare. |
| [LineCapTypeTriangle](#LineCapTypeTriangle) | Specifica un cappuccio di linea triangolare. |
| [LineCapTypeNoAnchor](#LineCapTypeNoAnchor) | Specifica che l'estremità della linea non è ancorata. |
| [LineCapTypeSquareAnchor](#LineCapTypeSquareAnchor) | Specifica che l'estremità della linea è ancorata con un cap di linea quadrato. |
| [LineCapTypeRoundAnchor](#LineCapTypeRoundAnchor) | Specifica che l'estremità della linea è ancorata con un cap di linea circolare. |
| [LineCapTypeDiamondAnchor](#LineCapTypeDiamondAnchor) | Specifica che l'estremità della linea è ancorata con un cap di linea a forma di diamante, che è un quadrato ruotato di 45 gradi. |
| [LineCapTypeArrowAnchor](#LineCapTypeArrowAnchor) | Specifica che l'estremità della linea è ancorata con una forma a punta di freccia. |
| [LineCapTypeAnchorMask](#LineCapTypeAnchorMask) | Maschera usata per verificare se un cap di linea è un cap di ancoraggio. |
| [LineCapTypeCustom](#LineCapTypeCustom) | Specifica un cappuccio di linea personalizzato. |
### LineCapTypeFlat {#LineCapTypeFlat}
```
public static final int LineCapTypeFlat
```


Specifica un cap di linea quadrato. L'estremità della linea DEVE essere l'ultimo punto della linea.

### LineCapTypeSquare {#LineCapTypeSquare}
```
public static final int LineCapTypeSquare
```


Specifica un cap di linea quadrato. Il centro del quadrato DEVE trovarsi all'ultimo punto della linea. La larghezza del quadrato è la larghezza della linea.

### LineCapTypeRound {#LineCapTypeRound}
```
public static final int LineCapTypeRound
```


Specifica un cap di linea circolare. Il centro del cerchio DEVE trovarsi all'ultimo punto della linea. Il diametro del cerchio è la larghezza della linea.

### LineCapTypeTriangle {#LineCapTypeTriangle}
```
public static final int LineCapTypeTriangle
```


Specifica un cap di linea triangolare. La base del triangolo DEVE trovarsi all'ultimo punto della linea. La base del triangolo è la larghezza della linea.

### LineCapTypeNoAnchor {#LineCapTypeNoAnchor}
```
public static final int LineCapTypeNoAnchor
```


Specifica che l'estremità della linea non è ancorata.

### LineCapTypeSquareAnchor {#LineCapTypeSquareAnchor}
```
public static final int LineCapTypeSquareAnchor
```


Specifica che l'estremità della linea è ancorata con un cap di linea quadrato. Il centro del quadrato DEVE trovarsi all'ultimo punto della linea. L'altezza e la larghezza del quadrato sono la larghezza della linea.

### LineCapTypeRoundAnchor {#LineCapTypeRoundAnchor}
```
public static final int LineCapTypeRoundAnchor
```


Specifica che l'estremità della linea è ancorata con un cap di linea circolare. Il centro del cerchio DEVE trovarsi all'ultimo punto della linea. Il cerchio DEVE essere più largo della linea.

### LineCapTypeDiamondAnchor {#LineCapTypeDiamondAnchor}
```
public static final int LineCapTypeDiamondAnchor
```


Specifica che l'estremità della linea è ancorata con un cap di linea a forma di diamante, che è un quadrato ruotato di 45 gradi. Il centro del diamante DEVE trovarsi all'ultimo punto della linea. Il diamante DEVE essere più largo della linea.

### LineCapTypeArrowAnchor {#LineCapTypeArrowAnchor}
```
public static final int LineCapTypeArrowAnchor
```


Specifica che l'estremità della linea è ancorata con una forma a punta di freccia. Il punto della punta di freccia DEVE trovarsi all'ultimo punto della linea. La punta di freccia DEVE essere più larga della linea.

### LineCapTypeAnchorMask {#LineCapTypeAnchorMask}
```
public static final int LineCapTypeAnchorMask
```


Maschera usata per verificare se un cap di linea è un cap di ancoraggio.

### LineCapTypeCustom {#LineCapTypeCustom}
```
public static final int LineCapTypeCustom
```


Specifica un cappuccio di linea personalizzato.

