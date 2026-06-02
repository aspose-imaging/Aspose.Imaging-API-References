---
title: "StretchMode"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'Enumerazione specifica la modalità di stretching del bitmap che definisce come il sistema combina righe o colonne di un bitmap con i pixel esistenti."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.fileformats.wmf.consts/stretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StretchMode extends System.Enum
```

L'Enumerazione [StretchMode](../../com.aspose.imaging.fileformats.wmf.consts/stretchmode) specifica la modalità di stretching del bitmap, che definisce come il sistema combina righe o colonne di un bitmap con i pixel esistenti.
## Campi

| Campo | Descrizione |
| --- | --- |
| [BlackOnWhite](#BlackOnWhite) | Esegue un'operazione Boolean AND utilizzando i valori di colore per i pixel eliminati e quelli esistenti. |
| [WhiteOnBlack](#WhiteOnBlack) | Esegue un'operazione Boolean OR utilizzando i valori di colore per i pixel eliminati e quelli esistenti. |
| [ColorOnColor](#ColorOnColor) | Elimina i pixel. |
| [HalfTone](#HalfTone) | Mappa i pixel dal rettangolo di origine in blocchi di pixel nel rettangolo di destinazione. |
### BlackOnWhite {#BlackOnWhite}
```
public static final int BlackOnWhite
```


Esegue un'operazione Boolean AND utilizzando i valori di colore per i pixel eliminati e quelli esistenti. Se il bitmap è monocromatico, questa modalità preserva i pixel neri a scapito di quelli bianchi.

### WhiteOnBlack {#WhiteOnBlack}
```
public static final int WhiteOnBlack
```


Esegue un'operazione Boolean OR utilizzando i valori di colore per i pixel eliminati e quelli esistenti. Se il bitmap è monocromatico, questa modalità preserva i pixel bianchi a scapito di quelli neri.

### ColorOnColor {#ColorOnColor}
```
public static final int ColorOnColor
```


Elimina i pixel. Questa modalità elimina tutte le linee di pixel eliminate senza cercare di preservarne le informazioni.

### HalfTone {#HalfTone}
```
public static final int HalfTone
```


Mappa i pixel dal rettangolo di origine in blocchi di pixel nel rettangolo di destinazione. Il colore medio sul blocco di pixel di destinazione approssima il colore dei pixel di origine.

