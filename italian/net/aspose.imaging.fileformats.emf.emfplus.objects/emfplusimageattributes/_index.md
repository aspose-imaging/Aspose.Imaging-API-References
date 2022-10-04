---
title: EmfPlusImageAttributes
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Loggetto EmfPlusImageAttributes specifica come vengono manipolati i colori dellimmagine bitmap durante il rendering.
type: docs
weight: 5510
url: /it/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---
## EmfPlusImageAttributes class

L'oggetto EmfPlusImageAttributes specifica come vengono manipolati i colori dell'immagine bitmap durante il rendering.

```csharp
public sealed class EmfPlusImageAttributes : EmfPlusGraphicsObjectType
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfPlusImageAttributes](emfplusimageattributes)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ClampArgb32Color](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/clampargb32color) { get; set; } | Ottiene o imposta l'oggetto EmfPlusARGB (sezione 2.2.2.1) che specifica il colore del bordo da utilizzare quando il valore WrapMode è WrapModeClamp. Questo colore è visibile quando il rettangolo di origine elaborato da un record EmfPlusDrawImage (sezione 2.3.4.8) è più grande dell'immagine stessa. |
| [ObjectClamp](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/objectclamp) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica il comportamento di bloccaggio dell'oggetto. Non viene utilizzato finché questo oggetto non viene applicato a un'immagine disegnata. Questo valore DEVE essere uno dei valori definiti nella tabella seguente. |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version) { get; set; } | Ottiene o imposta la versione. |
| [WrapMode](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/wrapmode) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica come gestire le condizioni dei bordi con un valore dall'enumerazione WrapMode (sezione 2.1.1.34). |

### Guarda anche

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype)
* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->