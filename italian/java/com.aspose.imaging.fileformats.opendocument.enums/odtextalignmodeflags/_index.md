---
title: "OdTextAlignModeFlags"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Le flag della modalità di allineamento del testo del documento aperto"
type: docs
weight: 14
url: /it/java/com.aspose.imaging.fileformats.opendocument.enums/odtextalignmodeflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class OdTextAlignModeFlags extends System.Enum
```

Le flag della modalità di allineamento del testo del documento aperto
## Campi

| Campo | Descrizione |
| --- | --- |
| [Noupdatecp](#Noupdatecp) | La posizione di disegno nel contesto del dispositivo di riproduzione NON DEVE essere aggiornata dopo ogni chiamata di output del testo. |
| [Left](#Left) | Il punto di riferimento DEVE trovarsi sul bordo sinistro del rettangolo di delimitazione. |
| [Top](#Top) | Il punto di riferimento DEVE trovarsi sul bordo superiore del rettangolo di delimitazione. |
| [Updatecp](#Updatecp) | La posizione di disegno nel contesto del dispositivo di riproduzione DEVE essere aggiornata dopo ogni chiamata di output del testo. |
| [Right](#Right) | Il punto di riferimento DEVE trovarsi sul bordo destro del rettangolo di delimitazione. |
| [Center](#Center) | Il punto di riferimento DEVE essere allineato orizzontalmente con il centro del rettangolo di delimitazione. |
| [Justify](#Justify) | Il testo deve essere allineato in modo che ogni riga di testo di un paragrafo abbia la stessa lunghezza. |
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

### Justify {#Justify}
```
public static final int Justify
```


Il testo deve essere allineato in modo che ogni riga di testo di un paragrafo abbia la stessa lunghezza.

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

