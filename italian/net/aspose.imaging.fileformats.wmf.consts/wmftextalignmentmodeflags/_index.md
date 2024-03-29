---
title: WmfTextAlignmentModeFlags
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: TextAlignmentMode I flag specificano la relazione tra un punto di riferimento e un rettangolo di delimitazione  per lallineamento del testo. Questi flag possono essere combinati per specificare più opzioni con la restrizione che può essere scelto un solo flag che altera la posizione del disegno nel contesto del dispositivo di riproduzione . Lallineamento orizzontale del testo viene eseguito quando il font ha una linea di base orizzontale predefinita.
type: docs
weight: 8350
url: /it/net/aspose.imaging.fileformats.wmf.consts/wmftextalignmentmodeflags/
---
## WmfTextAlignmentModeFlags enumeration

TextAlignmentMode I flag specificano la relazione tra un punto di riferimento e un rettangolo di delimitazione , per l'allineamento del testo. Questi flag possono essere combinati per specificare più opzioni, con la restrizione che può essere scelto un solo flag che altera la posizione del disegno nel contesto del dispositivo di riproduzione . L'allineamento orizzontale del testo viene eseguito quando il font ha una linea di base orizzontale predefinita.

```csharp
[Flags]
public enum WmfTextAlignmentModeFlags
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Noupdatecp | `0` | La posizione del disegno nel contesto del dispositivo di riproduzione NON DEVE essere aggiornata dopo ogni chiamata di output di testo. Il punto di riferimento DEVE essere passato alla funzione di output del testo. |
| Left | `0` | Il punto di riferimento DEVE essere sul bordo sinistro del rettangolo di delimitazione. |
| Top | `0` | Il punto di riferimento DEVE trovarsi sul bordo superiore del rettangolo di delimitazione. |
| Updatecp | `1` | La posizione del disegno nel contesto del dispositivo di riproduzione DEVE essere aggiornata dopo ogni chiamata di output text . DEVE essere utilizzato come punto di riferimento. |
| Right | `2` | Il punto di riferimento DEVE essere sul bordo destro del rettangolo di delimitazione. |
| Center | `6` | Il punto di riferimento DEVE essere allineato orizzontalmente con il centro del rettangolo di delimitazione. |
| Bottom | `8` | Il punto di riferimento DEVE trovarsi sul bordo inferiore del rettangolo di delimitazione. |
| Baseline | `18` | Il punto di riferimento DEVE essere sulla linea di base del testo. |
| Rtlreading | `100` | Il testo DEVE essere disposto in ordine di lettura da destra a sinistra, invece dell'ordine predefinito da sinistra a destra. Questo DOVREBBE essere applicato solo quando il carattere definito nel contesto del dispositivo di riproduzione è ebraico o arabo. |
| Horizontal | `6` | Rappresenta set di algin di testo orizzontali (sinistra &#x7C; destra &#x7C; centro) |
| Vertical | `18` | Rappresenta gli insiemi di allineamento del testo verticale (In alto &#x7C; In basso &#x7C; Linea di base) |

### Osservazioni

I flag TextAlignmentMode specificano tre diversi componenti dell'allineamento del testo: - La posizione orizzontale del punto di riferimento è determinata da TA_RIGHT e TA_CENTER; se quei bit sono liberi, l'allineamento DEVE essere TA_LEFT. - La posizione verticale del punto di riferimento è determinata da TA_BOTTOM e TA_BASELINE; se quei bit sono liberi, l'allineamento DEVE essere TA_TOP. - Se aggiornare la posizione di output nel contesto del dispositivo di riproduzione dopo che l'output del testo è determinato da TA_UPDATECP; se quel bit è libero, la posizione NON DEVE essere aggiornata. Questo è il motivo per definire tre diversi valori zero nell'enumerazione; rappresentano gli stati predefiniti delle tre componenti dell'allineamento del testo.

### Guarda anche

* spazio dei nomi [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
