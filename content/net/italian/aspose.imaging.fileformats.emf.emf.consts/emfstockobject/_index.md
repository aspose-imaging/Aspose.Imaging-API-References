---
title: EmfStockObject
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Lenumerazione StockObject specifica gli indici degli oggetti grafici logici predefiniti che possono essere utilizzati nelle operazioni grafiche. Le strutture specifiche degli oggetti stock sono dipendenti dallimplementazione tuttavia le proprietà degli oggetti in stock DEVONO essere equivalenti a le proprietà degli oggetti creati in modo esplicito dello stesso tipo. Queste proprietà sono specificate ove possibile per gli oggetti stock definiti in questa enumerazione.
type: docs
weight: 2860
url: /it/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
## EmfStockObject enumeration

L'enumerazione StockObject specifica gli indici degli oggetti grafici logici predefiniti che possono essere utilizzati nelle operazioni grafiche. Le strutture specifiche degli oggetti stock sono dipendenti dall'implementazione; tuttavia, le proprietà degli oggetti in stock DEVONO essere equivalenti a le proprietà degli oggetti creati in modo esplicito dello stesso tipo. Queste proprietà sono specificate ove possibile per gli oggetti stock definiti in questa enumerazione.

```csharp
public enum EmfStockObject
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| WHITE_BRUSH | `-2147483648` | Un pennello bianco a tinta unita equivalente a un pennello logico (oggetto LogBrushEx, sezione 2.2.12) con le seguenti proprietà: BrushStyle: BS_SOLID (enumerazione WMF BrushStyle, [MS-WMF] sezione 2.1.1.4) Colore: 0x00FFFFFF (oggetto WMF ColorRef, [MS-WMF] sezione 2.2.2.8) |
| LTGRAY_BRUSH | `-2147483647` | Un pennello grigio chiaro a tinta unita equivalente a un pennello logico con le seguenti proprietà: BrushStyle: BS_SOLID Color: 0x00C0C0C0 |
| GRAY_BRUSH | `-2147483646` | Un pennello grigio a tinta unita equivalente a un pennello logico con le seguenti proprietà: BrushStyle: BS_SOLID Color: 0x00808080 |
| DKGRAY_BRUSH | `-2147483645` | Un pennello a tinta unita grigio scuro equivalente a un pennello logico con le seguenti proprietà: BrushStyle: BS_SOLID Color: 0x00404040 |
| BLACK_BRUSH | `-2147483644` | Un pennello nero a tinta unita equivalente a un pennello logico con le seguenti proprietà: BrushStyle: BS_SOLID Color: 0x00000000 |
| NULL_BRUSH | `-2147483643` | Un pennello nullo equivalente a un pennello logico con le seguenti proprietà: BrushStyle: BS_NULL |
| WHITE_PEN | `-2147483642` | Una penna bianca a tinta unita equivalente a una penna logica (oggetto LogPen, sezione 2.2.19) con le seguenti proprietà: PenStyle: PS_COSMETIC + PS_SOLID (enumerazione PenStyle, sezione 2.1.25) ColorRef: 0x00FFFFFF ( Oggetto ColorRef WMF). |
| BLACK_PEN | `-2147483641` | Una penna nera a tinta unita equivalente a una penna logica con le seguenti proprietà: PenStyle: PS_COSMETIC + PS_SOLID ColorRef: 0x00000000 |
| NULL_PEN | `-2147483640` | Una penna nulla equivalente a una penna logica con le seguenti proprietà: PenStyle: PS_NULL |
| OEM_FIXED_FONT | `-2147483638` | Un font set di caratteri OEM a larghezza fissa equivalente a un font logico (oggetto LogFont, sezione 2.2.13) con le seguenti proprietà: Charset: OEM_CHARSET (enumerazione WMF CharacterSet, [MS-WMF] sezione 2.1.1.5 ) PitchAndFamily: FF_DONTCARE (enumerazione WMF FamilyFont, [MS-WMF] sezione 2.1.1.8) + FIXED_PITCH (enumerazione WMF PitchFont, [MS-WMF] sezione 2.1.1.24) |
| ANSI_FIXED_FONT | `-2147483637` | Un font a larghezza fissa equivalente a un font logico con le seguenti proprietà: Charset: ANSI_CHARSET PitchAndFamily: FF_DONTCARE + FIXED_PITCH |
| ANSI_VAR_FONT | `-2147483636` | Un font a larghezza variabile equivalente a un font logico con le seguenti proprietà: Charset: ANSI_CHARSET PitchAndFamily: FF_DONTCARE + VARIABLE_PITCH |
| SYSTEM_FONT | `-2147483635` | Un font di cui è garantita la disponibilità nel sistema operativo. Il carattere effettivo specificato da questo valore dipende dall'implementazione |
| DEVICE_DEFAULT_FONT | `-2147483634` | Il carattere predefinito fornito dal driver del dispositivo grafico per il dispositivo di output corrente. Il carattere effettivo specificato da questo valore dipende dall'implementazione |
| DEFAULT_PALETTE | `-2147483633` | La tavolozza predefinita definita per il dispositivo di output corrente. La tavolozza effettiva specificata da questo valore dipende dall'implementazione |
| SYSTEM_FIXED_FONT | `-2147483632` | Un font a larghezza fissa di cui è garantita la disponibilità nel sistema operativo. Il carattere effettivo specificato da questo valore dipende dall'implementazione |
| DEFAULT_GUI_FONT | `-2147483631` | Un font a larghezza fissa di cui è garantita la disponibilità nel sistema operativo. Il carattere effettivo specificato da questo valore dipende dall'implementazione |
| DC_BRUSH | `-2147483630` | Il pennello a tinta unita attualmente selezionato nel contesto del dispositivo di riproduzione |
| DC_PEN | `-2147483629` | La penna a tinta unita attualmente selezionata nel contesto del dispositivo di riproduzione |

### Guarda anche

* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
