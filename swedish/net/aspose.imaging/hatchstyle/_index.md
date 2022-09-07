---
title: HatchStyle
second_title: Aspose.Imaging för .NET API-referens
description: Anger de olika mönster som är tillgängliga förHatchBrush../aspose.imaging.brushes/hatchbrush objekt.
type: docs
weight: 9390
url: /sv/net/aspose.imaging/hatchstyle/
---
## HatchStyle enumeration

Anger de olika mönster som är tillgängliga för[`HatchBrush`](../../aspose.imaging.brushes/hatchbrush) objekt.

```csharp
public enum HatchStyle
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Horizontal | `0` | Ett mönster av horisontella linjer. |
| Min | `0` | Anger kläckningsstil Horisontell. |
| Vertical | `1` | Ett mönster av vertikala linjer. |
| ForwardDiagonal | `2` | Ett mönster av linjer på en diagonal från övre vänster till nedre höger. |
| BackwardDiagonal | `3` | Ett mönster av linjer på en diagonal från övre högra till nedre vänstra. |
| Cross | `4` | Anger horisontella och vertikala linjer som korsar. |
| LargeGrid | `4` | Anger kläckningsstilen Cross. |
| Max | `4` | Anger kläckningsstil SolidDiamond. |
| DiagonalCross | `5` | Ett mönster av kors och tvärs diagonala linjer. |
| Percent05 | `6` | Anger en 5-procentig lucka. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 5:95. |
| Percent10 | `7` | Anger en 10-procentig lucka. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 10:90. |
| Percent20 | `8` | Anger en 20-procentig lucka. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 20:80. |
| Percent25 | `9` | Anger en 25-procentig lucka. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 25:75. |
| Percent30 | `10` | Anger en 30-procentig lucka. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 30:70. |
| Percent40 | `11` | Anger en 40-procentig lucka. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 40:60. |
| Percent50 | `12` | Anger en 50-procentig lucka. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 50:50. |
| Percent60 | `13` | Anger en 60-procentig lucka. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 60:40. |
| Percent70 | `14` | Anger en 70-procentig lucka. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 70:30. |
| Percent75 | `15` | Anger en 75-procentig lucka. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 75:25. |
| Percent80 | `16` | Anger en 80-procentig lucka. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 80:100. |
| Percent90 | `17` | Anger en 90-procentig lucka. Förhållandet mellan förgrundsfärg och bakgrundsfärg är 90:10. |
| LightDownwardDiagonal | `18` | Anger diagonala linjer som lutar åt höger från topppunkter till bottenpunkter och är placerade 50 procent närmare varandra än ForwardDiagonal, men är inte kantutjämnade. |
| LightUpwardDiagonal | `19` | Anger diagonala linjer som lutar åt vänster från topppunkter till bottenpunkter och är placerade 50 procent närmare varandra än BackwardDiagonal, men de är inte kantutjämnade. |
| DarkDownwardDiagonal | `20` | Anger diagonala linjer som lutar åt höger från topppunkter till bottenpunkter, är placerade 50 procent närmare varandra än och är dubbelt så breda som ForwardDiagonal. Det här kläckningsmönstret har inte kantutjämning. |
| DarkUpwardDiagonal | `21` | Anger diagonala linjer som lutar åt vänster från topppunkter till bottenpunkter, är placerade 50 procent närmare varandra än BackwardDiagonal och är två gånger dess bredd, men linjerna är inte kantutjämnade. |
| WideDownwardDiagonal | `22` | Anger diagonala linjer som lutar åt höger från topppunkter till bottenpunkter, har samma avstånd som lucka stil ForwardDiagonal och är tredubbla dess bredd, men är inte kantutjämnade. |
| WideUpwardDiagonal | `23` | Anger diagonala linjer som lutar åt vänster från topppunkter till bottenpunkter, har samma avstånd som lucka stil BakåtDiagonal och är tredubbla dess bredd, men är inte kantutjämnade. |
| LightVertical | `24` | Anger vertikala linjer som är placerade 50 procent närmare varandra än Vertical. |
| LightHorizontal | `25` | Anger horisontella linjer som är placerade 50 procent närmare varandra än horisontella. |
| NarrowVertical | `26` | Anger vertikala linjer som är placerade 75 procent närmare varandra än Vertical (eller 25 procent närmare varandra än LightVertical). |
| NarrowHorizontal | `27` | Anger horisontella linjer som är placerade 75 procent närmare varandra än horisontellt (eller 25 procent närmare varandra än LightHorizontal). |
| DarkVertical | `28` | Anger vertikala linjer som är placerade 50 procent närmare varandra än vertikala och är dubbelt så breda. |
| DarkHorizontal | `29` | Anger horisontella linjer som är placerade 50 procent närmare varandra än horisontella och är dubbelt så breda som horisontella. |
| DashedDownwardDiagonal | `30` | Anger streckade diagonala linjer, som lutar åt höger från topppunkter till bottenpunkter. |
| DashedUpwardDiagonal | `31` | Anger streckade diagonala linjer, som lutar åt vänster från topppunkter till bottenpunkter. |
| DashedHorizontal | `32` | Anger streckade horisontella linjer. |
| DashedVertical | `33` | Anger streckade vertikala linjer. |
| SmallConfetti | `34` | Anger en lucka som ser ut som konfetti. |
| LargeConfetti | `35` | Anger en lucka som ser ut som konfetti och är sammansatt av större bitar än SmallConfetti. |
| ZigZag | `36` | Anger horisontella linjer som är sammansatta av sicksack. |
| Wave | `37` | Anger horisontella linjer som är sammansatta av tildes. |
| DiagonalBrick | `38` | Anger en lucka som ser ut som skiktade tegelstenar som lutar åt vänster från topppunkter till bottenpunkter. |
| HorizontalBrick | `39` | Anger en lucka som ser ut som horisontellt skiktade tegelstenar. |
| Weave | `40` | Anger en lucka som ser ut som ett vävt material. |
| Plaid | `41` | Anger en lucka som ser ut som ett rutigt material. |
| Divot | `42` | Anger en lucka som ser ut som divot. |
| DottedGrid | `43` | Anger horisontella och vertikala linjer, som var och en består av punkter, som korsar. |
| DottedDiamond | `44` | Anger diagonala framåt och bakåt diagonala linjer, som var och en består av punkter, som korsar. |
| Shingle | `45` | Anger en lucka som ser ut som diagonalt skiktade bältros som lutar åt höger från topppunkter till bottenpunkter. |
| Trellis | `46` | Anger en lucka som ser ut som en spaljé. |
| Sphere | `47` | Anger en lucka som ser ut som sfärer som ligger intill varandra. |
| SmallGrid | `48` | Anger horisontella och vertikala linjer som korsar och är placerade 50 procent närmare varandra än kors med skräckstil. |
| SmallCheckerBoard | `49` | Anger en lucka som ser ut som en schackbräde. |
| LargeCheckerBoard | `50` | Anger en lucka som ser ut som en schackbräde med rutor som är dubbelt så stora som SmallCheckerBoard. |
| OutlinedDiamond | `51` | Anger diagonala framåt och bakåt diagonala linjer som korsar men inte är kantutjämnade. |
| SolidDiamond | `52` | Anger en lucka som ser ut som en schackbräde placerad diagonalt. |

### Se även

* namnutrymme [Aspose.Imaging](../../aspose.imaging)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
