---
title: WmfLogColorSpace
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Loggetto LogColorSpace specifica uno spazio colore logico per il contesto del dispositivo di riproduzione  che può essere il nome di un profilo colore in caratteri ASCII.
type: docs
weight: 8750
url: /it/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---
## WmfLogColorSpace class

L'oggetto LogColorSpace specifica uno spazio colore logico per il contesto del dispositivo di riproduzione , che può essere il nome di un profilo colore in caratteri ASCII.

```csharp
public class WmfLogColorSpace : MetaObject
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [WmfLogColorSpace](wmflogcolorspace)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ColorSpaceType](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/colorspacetype) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che specifica il tipo spazio colore . DEVE essere definito nell'enumerazione LogicalColorSpace (sezione 2.1.1.14). Se questo valore è LCS_sRGB o LCS_WINDOWS_COLOR_SPACE, DEVE essere utilizzato lo spazio colore sRGB. |
| [Endpoints](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/endpoints) { get; set; } | Ottiene o imposta un oggetto CIEXYZTriple (sezione 2.2.2.7) che definisce le coordinate cromatiche CIE x, yez dei tre colori che corrispondono all'RGBendpoints per lo spazio colore logical associato alla bitmap. Se il [`ColorSpaceType`](./colorspacetype) il campo non specifica LCS_CALIBRATED_RGB, questo campo DEVE essere ignorato. |
| [Filename](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/filename) { get; set; } | Ottiene o imposta una stringa di caratteri ASCII facoltativa che specifica il nome di un file che contiene un profilo colore. Se un nome file è specificato, e il[`ColorSpaceType`](./colorspacetype) il campo è impostato su LCS_CALIBRATED_RGB, gli altri campi di questa struttura DOVREBBE essere ignorati. |
| [GammaBlue](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammablue) { get; set; } | Ottiene o imposta un valore in virgola fissa a 32 bit che definisce la curva di risposta toned per il blu. Se la[`ColorSpaceType`](./colorspacetype) field non specifica LCS_CALIBRATED_RGB, questo campo DEVE essere ignorato. |
| [GammaGreen](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammagreen) { get; set; } | Ottiene o imposta un valore in virgola fissa a 32 bit che definisce la curva di risposta toned per il verde. Se la[`ColorSpaceType`](./colorspacetype) field non specifica LCS_CALIBRATED_RGB, questo campo DEVE essere ignorato. |
| [GammaRed](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/gammared) { get; set; } | Ottiene o imposta un valore in virgola fissa a 32 bit che definisce la curva di risposta toned per il rosso. Se la[`ColorSpaceType`](./colorspacetype) field non specifica LCS_CALIBRATED_RGB, questo campo DEVE essere ignorato. |
| [Intent](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/intent) { get; set; } | Ottiene o imposta un intero con segno a 32 bit che definisce l'intento gamut mapping . DEVE essere definito nell'enumerazione GamutMappingIntent (sezione 2.1.1.11). |
| [Signature](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/signature) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che specifica il signature di oggetti dello spazio colore; DEVE essere impostato su il valore 0x50534F43, che è la codifica ASCII della stringa "PSOC". |
| [Size](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/size) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che definisce il size di questo oggetto, in byte. |
| [Version](../../aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/version) { get; set; } | Ottiene o imposta un intero senza segno a 32 bit che definisce a version numero; DEVE essere 0x00000400. |

### Osservazioni

I campi Endpoints, GammaRed, GammaGreen e GammaBlue vengono utilizzati per specificare uno spazio colore logico. Il campo Endpoints è un oggetto CIEXYZTriple che contiene i valori x, yez dell'endpoint RGB dello spazio colore . La relazione tra i valori tristimolo X,Y,Z e valori di cromaticità x,y,z è espressa come segue. x = X/(X+Y+Z) y = Y/(X+Y+Z) z = Z/(X+Y+Z) I campi GammaRed, GammaGreen e GammaBlue contengono valori in "8.8 punto fisso" format, che è una tecnica per che rappresenta numeri non interi. Ogni valore è costituito da una grandezza zeroextended a 8 bit seguita da una frazione a 8 bit, con i 16 bit combinati spostati a sinistra di 8 bit. Pertanto, in 32 bit, il valore reale NF è 00000000nnnnnnnnffffffff00000000, dove "nnnnnnnn" e "ffffffff" sono rappresentazioni binarie rispettivamente di N e F. Ad esempio, per il numero reale 10.5, nnnnnnn sarebbe 00001010 (binario 10) e ffffffff sarebbero 00000101 (binario 5), e il valore binario completo a 32 bit sarebbe sarà 000000000000101000000101000000, che è il valore hexadecimald_d.

### Guarda anche

* class [MetaObject](../../aspose.imaging.fileformats.emf/metaobject)
* spazio dei nomi [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
