---
title: EmfPenStyle
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Lenumerazione PenStyle definisce gli attributi delle penne che possono essere utilizzati nelle operazioni grafiche. Uno stile penna è una combinazione di tipo penna stile linea fine linea e unione di linea.
type: docs
weight: 2780
url: /it/net/aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/
---
## EmfPenStyle enumeration

L'enumerazione PenStyle definisce gli attributi delle penne che possono essere utilizzati nelle operazioni grafiche. Uno stile penna è una combinazione di tipo penna, stile linea, fine linea e unione di linea.

```csharp
[Flags]
public enum EmfPenStyle
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| PS_COSMETIC | `0` | Un tipo di penna che specifica una linea con una larghezza di un'unità logica e uno stile che è un colore solido |
| PS_ENDCAP_ROUND | `0` | Un limite di riga che specifica le estremità arrotondate. |
| PS_JOIN_ROUND | `0` | Un join di linea che specifica i join rotondi |
| PS_SOLID | `0` | Uno stile di linea a tinta unita |
| PS_DASH | `1` | Uno stile di linea tratteggiato |
| PS_DOT | `2` | Uno stile di linea punteggiato. |
| PS_DASHDOT | `3` | Uno stile di linea composto da trattini e punti alternati |
| PS_DASHDOTDOT | `4` | Uno stile di linea composto da trattini e punti doppi. |
| PS_NULL | `5` | Uno stile di linea invisibile. |
| PS_INSIDEFRAME | `6` | Uno stile di linea a tinta unita. Quando questo stile viene specificato in un record di disegno che accetta un rettangolo di delimitazione, le dimensioni della figura vengono ridotte in modo che rientri interamente nel rettangolo di delimitazione, tenendo conto della larghezza della penna. |
| PS_USERSTYLE | `7` | Uno stile di linea definito da un array di stili, che specifica la lunghezza dei trattini e degli spazi vuoti nella linea |
| PS_ALTERNATE | `8` | Uno stile di linea in cui è impostato ogni altro pixel. Questo stile è applicabile solo a un tipo di penna PS_COSMETIC |
| PS_ENDCAP_SQUARE | `100` | Un limite di linea che specifica le estremità quadrate. |
| PS_ENDCAP_FLAT | `200` | Un limite di linea che specifica le estremità piatte. |
| PS_JOIN_BEVEL | `1000` | Un'unione di linea che specifica unioni smussate. |
| PS_JOIN_MITER | `2000` | Un join di linea che specifica i join smussati quando le lunghezze dei join rientrano nel limite di lunghezza dell'angolo corrente impostato nel contesto del dispositivo di riproduzione. Se le lunghezze dei giunti superano il limite di taglio obliquo, vengono specificati i giunti smussati |
| PS_GEOMETRIC | `10000` | Un tipo di penna che specifica una linea con una larghezza misurata in unità logiche e uno stile che può contenere qualsiasi attributo di un pennello. |
| StyleMask | `F` | La maschera di stile |
| EndCapMask | `F00` | La maschera del cappuccio terminale |
| JoinMask | `F000` | La maschera di unione |
| TypeMask | `F0000` | Il tipo mask |

### Guarda anche

* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
