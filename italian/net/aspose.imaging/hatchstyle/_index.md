---
title: HatchStyle
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Specifica i diversi modelli disponibili perHatchBrush../aspose.imaging.brushes/hatchbrush oggetti.
type: docs
weight: 9390
url: /it/net/aspose.imaging/hatchstyle/
---
## HatchStyle enumeration

Specifica i diversi modelli disponibili per[`HatchBrush`](../../aspose.imaging.brushes/hatchbrush) oggetti.

```csharp
public enum HatchStyle
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Horizontal | `0` | Uno schema di linee orizzontali. |
| Min | `0` | Specifica lo stile di tratteggio Orizzontale. |
| Vertical | `1` | Uno schema di linee verticali. |
| ForwardDiagonal | `2` | Un motivo di linee su una diagonale da in alto a sinistra a in basso a destra. |
| BackwardDiagonal | `3` | Un motivo di linee su una diagonale da in alto a destra a in basso a sinistra. |
| Cross | `4` | Specifica le linee orizzontali e verticali che si incrociano. |
| LargeGrid | `4` | Specifica lo stile di tratteggio Cross. |
| Max | `4` | Specifica lo stile di tratteggio SolidDiamond. |
| DiagonalCross | `5` | Uno schema di linee diagonali incrociate. |
| Percent05 | `6` | Specifica un tratteggio del 5 percento. Il rapporto tra il colore di primo piano e il colore di sfondo è 5:95. |
| Percent10 | `7` | Specifica un tratteggio del 10 percento. Il rapporto tra il colore di primo piano e il colore di sfondo è 10:90. |
| Percent20 | `8` | Specifica un tratteggio del 20 percento. Il rapporto tra il colore di primo piano e il colore di sfondo è 20:80. |
| Percent25 | `9` | Specifica un tratteggio del 25 percento. Il rapporto tra il colore di primo piano e il colore di sfondo è 25:75. |
| Percent30 | `10` | Specifica un tratteggio del 30 percento. Il rapporto tra il colore di primo piano e il colore di sfondo è 30:70. |
| Percent40 | `11` | Specifica un tratteggio del 40 percento. Il rapporto tra il colore di primo piano e il colore di sfondo è 40:60. |
| Percent50 | `12` | Specifica un tratteggio del 50 percento. Il rapporto tra il colore di primo piano e il colore di sfondo è 50:50. |
| Percent60 | `13` | Specifica un tratteggio del 60 percento. Il rapporto tra il colore di primo piano e il colore di sfondo è 60:40. |
| Percent70 | `14` | Specifica un tratteggio del 70 percento. Il rapporto tra il colore di primo piano e il colore di sfondo è 70:30. |
| Percent75 | `15` | Specifica un tratteggio del 75 percento. Il rapporto tra il colore di primo piano e il colore di sfondo è 75:25. |
| Percent80 | `16` | Specifica un tratteggio dell'80 percento. Il rapporto tra il colore di primo piano e il colore di sfondo è 80:100. |
| Percent90 | `17` | Specifica un tratteggio del 90 percento. Il rapporto tra il colore di primo piano e il colore di sfondo è 90:10. |
| LightDownwardDiagonal | `18` | Specifica le linee diagonali che si inclinano a destra dai punti in alto ai punti in basso e sono distanziate del 50 percento più vicine tra loro rispetto a ForwardDiagonal, ma non hanno l'antialias. |
| LightUpwardDiagonal | `19` | Specifica le linee diagonali che si inclinano a sinistra dai punti in alto ai punti in basso e sono distanziate del 50 percento più vicine tra loro rispetto a BackwardDiagonal, ma non hanno l'antialias. |
| DarkDownwardDiagonal | `20` | Specifica le linee diagonali che si inclinano a destra dai punti in alto ai punti in basso, sono distanziate del 50 percento più vicine tra loro e sono larghe il doppio di ForwardDiagonal. Questo modello di tratteggio non è antialias. |
| DarkUpwardDiagonal | `21` | Specifica le linee diagonali che si inclinano a sinistra dai punti in alto ai punti in basso, sono distanziate del 50 percento più vicine tra loro rispetto a BackwardDiagonal e sono larghe il doppio, ma le linee non hanno l'antialias. |
| WideDownwardDiagonal | `22` | Specifica le linee diagonali che si inclinano a destra dai punti in alto ai punti in basso, hanno la stessa spaziatura dello stile di tratteggio Diagonale in avanti e sono larghe il triplo, ma non hanno antialias. |
| WideUpwardDiagonal | `23` | Specifica le linee diagonali che si inclinano a sinistra dai punti in alto ai punti in basso, hanno la stessa spaziatura dello stile di tratteggio Diagonale indietro e sono larghe il triplo, ma non hanno l'antialias. |
| LightVertical | `24` | Specifica le linee verticali che sono distanziate del 50 percento più vicine tra loro rispetto a Vertical. |
| LightHorizontal | `25` | Specifica le linee orizzontali che sono distanziate del 50 percento più vicine tra loro rispetto a Orizzontale. |
| NarrowVertical | `26` | Specifica le linee verticali che sono distanziate del 75% più vicine tra loro rispetto allo stile di tratteggio Verticale (o del 25% più vicine tra loro rispetto a LightVertical). |
| NarrowHorizontal | `27` | Specifica le linee orizzontali che sono distanziate del 75% più vicine tra loro rispetto allo stile di tratteggio Orizzontale (o del 25% più vicine tra loro rispetto a LightHorizontal). |
| DarkVertical | `28` | Specifica le linee verticali che sono distanziate del 50 percento più vicine tra loro rispetto a Verticale e sono larghe il doppio della sua larghezza. |
| DarkHorizontal | `29` | Specifica le linee orizzontali che sono distanziate del 50 percento più vicine tra loro rispetto a Orizzontale e sono larghe il doppio di Orizzontale. |
| DashedDownwardDiagonal | `30` | Specifica le linee diagonali tratteggiate, che si inclinano a destra dai punti superiori a quelli inferiori. |
| DashedUpwardDiagonal | `31` | Specifica le linee diagonali tratteggiate, che si inclinano a sinistra dai punti superiori a quelli inferiori. |
| DashedHorizontal | `32` | Specifica le linee orizzontali tratteggiate. |
| DashedVertical | `33` | Specifica le linee verticali tratteggiate. |
| SmallConfetti | `34` | Specifica un tratteggio che ha l'aspetto di coriandoli. |
| LargeConfetti | `35` | Specifica un tratteggio che ha l'aspetto di coriandoli ed è composto da pezzi più grandi di SmallConfetti. |
| ZigZag | `36` | Specifica le linee orizzontali composte da zigzag. |
| Wave | `37` | Specifica le linee orizzontali composte da tilde. |
| DiagonalBrick | `38` | Specifica un tratteggio che ha l'aspetto di mattoni a strati inclinati a sinistra dai punti superiori a quelli inferiori. |
| HorizontalBrick | `39` | Specifica un tratteggio che ha l'aspetto di mattoni a strati orizzontalmente. |
| Weave | `40` | Specifica un tratteggio che ha l'aspetto di un materiale intrecciato. |
| Plaid | `41` | Specifica un tratteggio che ha l'aspetto di un materiale plaid. |
| Divot | `42` | Specifica un tratteggio che ha l'aspetto di divots. |
| DottedGrid | `43` | Specifica le linee orizzontali e verticali, ognuna delle quali è composta da punti, che si incrociano. |
| DottedDiamond | `44` | Specifica le linee diagonali avanti e indietro, ciascuna delle quali è composta da punti, che si incrociano. |
| Shingle | `45` | Specifica un tratteggio che ha l'aspetto di tegole a strati diagonalmente inclinate a destra dai punti superiori ai punti inferiori. |
| Trellis | `46` | Specifica un tratteggio che ha l'aspetto di un traliccio. |
| Sphere | `47` | Specifica un tratteggio che ha l'aspetto di sfere adiacenti l'una all'altra. |
| SmallGrid | `48` | Specifica le linee orizzontali e verticali che si incrociano e sono distanziate del 50 percento più vicine tra loro rispetto allo stile di tratteggio Cross. |
| SmallCheckerBoard | `49` | Specifica un tratteggio che ha l'aspetto di una scacchiera. |
| LargeCheckerBoard | `50` | Specifica un tratteggio che ha l'aspetto di una scacchiera con quadrati grandi il doppio di SmallCheckerBoard. |
| OutlinedDiamond | `51` | Specifica le linee diagonali avanti e indietro che si incrociano ma non hanno antialias. |
| SolidDiamond | `52` | Specifica un tratteggio che ha l'aspetto di una scacchiera posizionata in diagonale. |

### Guarda anche

* spazio dei nomi [Aspose.Imaging](../../aspose.imaging)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
