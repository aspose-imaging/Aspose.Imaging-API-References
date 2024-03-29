---
title: EmfPlusBrightnessContrastEffect
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Loggetto BrightnessContrastEffect specifica unespansione o una contrazione delle aree più chiare e più scure di unimmagine.
type: docs
weight: 5260
url: /it/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrightnesscontrasteffect/
---
## EmfPlusBrightnessContrastEffect class

L'oggetto BrightnessContrastEffect specifica un'espansione o una contrazione delle aree più chiare e più scure di un'immagine.

```csharp
public sealed class EmfPlusBrightnessContrastEffect : EmfPlusImageEffectsObjectType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusBrightnessContrastEffect](emfplusbrightnesscontrasteffect)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BrightnessLevel](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrightnesscontrasteffect/brightnesslevel) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica il livello di luminosità. Questo valore di DEVE essere compreso tra -255 e 255, con effetti come segue: -255 ≤ valore &lt; 0 Quando il valore diminuisce, la luminosità dell'immagine DEVE diminuire. 0 Un valore di 0 specifica che la luminosità NON DEVE cambiare . 0 &lt; valore ≤ 255 All'aumentare del valore, la luminosità dell'immagine DOVREBBE aumentare. |
| [ContrastLevel](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrightnesscontrasteffect/contrastlevel) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica il livello di contrasto. Questo valore DEVE essere compreso tra -100 e 100, con i seguenti effetti: -100 ≤ valore &lt; 0 Quando il valore diminuisce, il contrasto dell'immagine DEVE diminuire. 0 Un valore di 0 specifica che il contrasto NON DEVE cambiare . 0 &lt; valore ≤ 100 All'aumentare del valore, il contrasto dell'immagine DOVREBBE aumentare. |

### Guarda anche

* class [EmfPlusImageEffectsObjectType](../emfplusimageeffectsobjecttype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
