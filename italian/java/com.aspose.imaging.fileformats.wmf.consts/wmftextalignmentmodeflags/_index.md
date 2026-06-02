---
title: "WmfTextAlignmentModeFlags"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "I flag TextAlignmentMode specificano la relazione tra un punto di riferimento e un rettangolo di delimitazione per l'allineamento del testo."
type: docs
weight: 36
url: /it/java/com.aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfTextAlignmentModeFlags extends System.Enum
```

I flag TextAlignmentMode specificano la relazione tra un punto di riferimento e un rettangolo di delimitazione, per l'allineamento del testo. Questi flag possono essere combinati per specificare più opzioni, con la restrizione che può essere scelto solo un flag che modifica la posizione di disegno nel contesto del dispositivo di riproduzione. L'allineamento orizzontale del testo viene eseguito quando il carattere ha una linea di base predefinita orizzontale.

--------------------

I flag TextAlignmentMode specificano tre diversi componenti dell'allineamento del testo: - La posizione orizzontale del punto di riferimento è determinata da TA\_RIGHT e TA\_CENTER; se questi bit sono cancellati, l'allineamento DEVE essere TA\_LEFT. - La posizione verticale del punto di riferimento è determinata da TA\_BOTTOM e TA\_BASELINE; se questi bit sono cancellati, l'allineamento DEVE essere TA\_TOP. - L'aggiornamento della posizione di output nel contesto del dispositivo di riproduzione dopo l'output del testo è determinato da TA\_UPDATECP; se quel bit è cancellato, la posizione NON DEVE essere aggiornata. Questo è il motivo per cui nell'enumerazione sono definiti tre valori zero diversi; rappresentano gli stati predefiniti dei tre componenti dell'allineamento del testo.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Noupdatecp](#Noupdatecp) | La posizione di disegno nel contesto del dispositivo di riproduzione NON DEVE essere aggiornata dopo ogni chiamata di output del testo. |
| [Left](#Left) | Il punto di riferimento DEVE trovarsi sul bordo sinistro del rettangolo di delimitazione. |
| [Top](#Top) | Il punto di riferimento DEVE trovarsi sul bordo superiore del rettangolo di delimitazione. |
| [Updatecp](#Updatecp) | La posizione di disegno nel contesto del dispositivo di riproduzione DEVE essere aggiornata dopo ogni chiamata di output del testo. |
| [Right](#Right) | Il punto di riferimento DEVE trovarsi sul bordo destro del rettangolo di delimitazione. |
| [Center](#Center) | Il punto di riferimento DEVE essere allineato orizzontalmente con il centro del rettangolo di delimitazione. |
| [Bottom](#Bottom) | Il punto di riferimento DEVE trovarsi sul bordo inferiore del rettangolo di delimitazione. |
| [Baseline](#Baseline) | Il punto di riferimento DEVE trovarsi sulla linea di base del testo. |
| [Rtlreading](#Rtlreading) | Il testo DEVE essere disposto in ordine di lettura da destra a sinistra, invece dell'ordine predefinito da sinistra a destra. |
| [Horizontal](#Horizontal) | Represents Horizontal text align sets (Left | Right | Centro) |
| [Vertical](#Vertical) | Represents Vertical text align sets (Top | Bottom | Linea di base) |
### Noupdatecp {#Noupdatecp}
```
public static final int Noupdatecp
```


La posizione di disegno nel contesto del dispositivo di riproduzione NON DEVE essere aggiornata dopo ogni chiamata di output del testo. Il punto di riferimento DEVE essere passato alla funzione di output del testo.

### Left {#Left}
```
public static final int Left
```


Il punto di riferimento DEVE trovarsi sul bordo sinistro del rettangolo di delimitazione.

### Top {#Top}
```
public static final int Top
```


Il punto di riferimento DEVE trovarsi sul bordo superiore del rettangolo di delimitazione.

### Updatecp {#Updatecp}
```
public static final int Updatecp
```


La posizione di disegno nel contesto del dispositivo di riproduzione DEVE essere aggiornata dopo ogni chiamata di output del testo. Essa DEVE essere usata come punto di riferimento.

### Right {#Right}
```
public static final int Right
```


Il punto di riferimento DEVE trovarsi sul bordo destro del rettangolo di delimitazione.

### Center {#Center}
```
public static final int Center
```


Il punto di riferimento DEVE essere allineato orizzontalmente con il centro del rettangolo di delimitazione.

### Bottom {#Bottom}
```
public static final int Bottom
```


Il punto di riferimento DEVE trovarsi sul bordo inferiore del rettangolo di delimitazione.

### Baseline {#Baseline}
```
public static final int Baseline
```


Il punto di riferimento DEVE trovarsi sulla linea di base del testo.

### Rtlreading {#Rtlreading}
```
public static final int Rtlreading
```


Il testo DEVE essere disposto in ordine di lettura da destra a sinistra, invece dell'ordine predefinito da sinistra a destra. Questo DEVE essere applicato solo quando il carattere definito nel contesto del dispositivo di riproduzione è ebraico o arabo.

### Horizontal {#Horizontal}
```
public static final int Horizontal
```


Rappresenta i set di allineamento orizzontale del testo (Left | Right | Center)

### Vertical {#Vertical}
```
public static final int Vertical
```


Rappresenta i set di allineamento verticale del testo (Top | Bottom | Baseline)

