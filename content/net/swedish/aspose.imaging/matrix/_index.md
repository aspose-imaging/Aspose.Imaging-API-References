---
title: Matrix
second_title: Aspose.Imaging för .NET API-referens
description: Ersätter GDI-matrisen.
type: docs
weight: 10550
url: /sv/aspose.imaging/matrix/
---
## Matrix class

Ersätter GDI+-matrisen.

```csharp
public class Matrix
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Matrix](matrix#constructor)() | Initierar en ny instans av Matrix-klassen som identitetsmatris. |
| [Matrix](matrix#constructor_1)(Matrix) | Gör en kopia av[`Matrix`](../matrix) class. |
| [Matrix](matrix#constructor_2)(Rectangle, Point[]) | Initierar en ny instans av[`Matrix`](../matrix) klass till den geometriska transformationen som definieras av den specificerade rektangeln och matrisen av punkter. |
| [Matrix](matrix#constructor_3)(RectangleF, PointF[]) | Initierar en ny instans av[`Matrix`](../matrix) klass till den geometriska transformationen som definieras av den specificerade rektangeln och matrisen av punkter. |
| [Matrix](matrix#constructor_4)(float, float, float, float, float, float) | Initierar en ny instans av[`Matrix`](../matrix) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Elements](../../aspose.imaging/matrix/elements) { get; } | Får en matris med flyttalsvärden som representerar elementen i detta[`Matrix`](../matrix) . |
| [M11](../../aspose.imaging/matrix/m11) { get; } | Hämtar matriselementet vid första radens första kolumn. Representerar skala längs X-axeln. |
| [M12](../../aspose.imaging/matrix/m12) { get; } | Hämtar matriselementet vid första radens andra kolumn. Representerar skjuvning längs Y-axeln. |
| [M21](../../aspose.imaging/matrix/m21) { get; } | Hämtar matriselementet vid andra radens första kolumn. Representerar skjuvning längs X-axeln. |
| [M22](../../aspose.imaging/matrix/m22) { get; } | Hämtar matriselementet vid andra radens andra kolumn. Representerar skala längs Y-axeln. |
| [M31](../../aspose.imaging/matrix/m31) { get; } | Hämtar matriselementet vid tredje radens första kolumn. Representerar översättning längs X-axeln. |
| [M32](../../aspose.imaging/matrix/m32) { get; } | Hämtar matriselementet vid tredje radens första kolumn. Representerar översättning längs Y-axeln. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.imaging/matrix/equals)(object) | Bestämmer om den angivnaObject är lika med denna instans. |
| [GetElements](../../aspose.imaging/matrix/getelements)() | Hämtar kopian av matriselement. |
| override [GetHashCode](../../aspose.imaging/matrix/gethashcode)() | Returnerar en hash-kod för denna instans. |
| [Multiply](../../aspose.imaging/matrix/multiply#multiply)(Matrix) | Multiplicerar denna matris med matrisen som anges i matrisparametern med hjälp av (standard) Prepend order. |
| [Multiply](../../aspose.imaging/matrix/multiply#multiply_1)(Matrix, MatrixOrder) | Multiplicerar denna matris med matrisen som anges i matrisparametern och i den ordning som anges i orderparametern. |
| [Reset](../../aspose.imaging/matrix/reset)() | Återställer denna matris för att ha elementen i identitetsmatrisen. |
| [Rotate](../../aspose.imaging/matrix/rotate#rotate)(float) | Tillämpar en medurs rotation av en mängd som anges i vinkelparametern, runt origo (noll x- och y-koordinater) för denna matris i standardordningen (Prepend). |
| [Rotate](../../aspose.imaging/matrix/rotate#rotate_1)(float, MatrixOrder) | Tillämpar en medurs rotation av en mängd som anges i vinkelparametern, runt origo (noll x- och y-koordinater) för denna matris i angiven ordning. |
| [RotateAt](../../aspose.imaging/matrix/rotateat#rotateat)(float, PointF) | Tillämpar en medurs rotation kring den angivna punkten på denna matris i standardordningen (Prepend). |
| [RotateAt](../../aspose.imaging/matrix/rotateat#rotateat_1)(float, PointF, MatrixOrder) | Tillämpar en medurs rotation kring den angivna punkten på denna matris i angiven ordning. |
| [Scale](../../aspose.imaging/matrix/scale#scale)(float, float) | Tillämpar den angivna skalvektorn (scaleX och scaleY) på denna matris med hjälp av (standard) Prepend order. |
| [Scale](../../aspose.imaging/matrix/scale#scale_1)(float, float, MatrixOrder) | Tillämpar den angivna skalvektorn (scaleX och scaleY) på detta[`Matrix`](../matrix) med den angivna ordningen. |
| override [ToString](../../aspose.imaging/matrix/tostring)() | Returnerar enString som representerar denna instans. |
| [TransformPoints](../../aspose.imaging/matrix/transformpoints)(PointF[]) | Tillämpar den geometriska transformationen som representeras av detta[`Matrix`](../matrix)till en specificerad uppsättning punkter. |
| [Translate](../../aspose.imaging/matrix/translate#translate)(float, float) | Tillämpar den angivna översättningsvektorn på detta[`Matrix`](../matrix) använder (standard) Prepend order. |
| [Translate](../../aspose.imaging/matrix/translate#translate_1)(float, float, MatrixOrder) | Tillämpar den angivna översättningsvektorn på denna matris i angiven ordning. |
| static [Equals](../../aspose.imaging/matrix/equals)(Matrix, Matrix) | Bestämmer om två matriser är lika. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [TypeFlip](../../aspose.imaging/matrix/typeflip) | Denna flaggbit indikerar att omvandlingen som definieras av detta objekt utför en spegelvändning kring någon axel som ändrar normalt högerhänt koordinatsystem till ett vänsterhänt förutom omvandlingarna som indikeras av andra flaggbitar. Ett högerhänt koordinatsystem är en där den positiva X -axeln roterar moturs för att överlägga den positiva Y-axeln liknande riktningen som fingrarna på din högra hand kröker sig när du stirrar på tummen. Ett vänsterhänt koordinatsystem är ett där det positiva X_x000 roterar medurs för att överlägga den positiva Y-axeln similar i den riktning som fingrarna på din vänstra hand kröker sig. Det finns inget matematiskt sätt att bestämma vinkeln för den ursprungliga vändningen eller spegelvändningen eftersom alla vinklar av vändningen är identiska med en lämplig justeringsrotation. OBS: TypeFlip lades till efter GENERAL_TRANSFORM var i public cirkulation och flaggbitarna kunde inte längre bekvämt omnumreras utan att införa binär inkompatibilitet i outside kod. |
| const [TypeGeneralRotation](../../aspose.imaging/matrix/typegeneralrotation) | Denna flaggbit indikerar att transformationen som definieras av detta objekt utför en rotation med en godtycklig vinkel utöver de omvandlingarna som indikeras av andra flaggbitar. En rotation ändrar vinklarna på vektorerna med samma mängd i vektorns riktning oavsett den ursprungliga riktningen och utan att ändra längden på vektorn. Denna flaggbit är ömsesidigt uteslutande med the |
| const [TypeGeneralScale](../../aspose.imaging/matrix/typegeneralscale) | En allmän skala multiplicerar längden på vektorer med olika mängder i x- och y-riktningarna utan att ändra vinkeln mellan vinkelräta vektorer. Denna flaggbit är ömsesidigt uteslutande med flaggan TypeUniformScale. |
| const [TypeGeneralTransform](../../aspose.imaging/matrix/typegeneraltransform) | Denna konstant indikerar att transformationen som definieras av detta object utför en godtycklig omvandling av ingångskoordinaterna. Om denna transform kan klassificeras av någon av ovanstående konstanter, kommer typen antingen att vara konstant TypeIdentity eller a kombination av lämplig flagga bitar för de olika koordinat -omvandlingarna som denna transformation utför. |
| const [TypeIdentity](../../aspose.imaging/matrix/typeidentity) | En identitetstransform är en där utgångskoordinaterna är alltid desamma som ingångskoordinaterna. Om denna transformation är något annat än identitetstransformen, kommer typen antingen att vara den konstanta GENERAL_TRANSFORM eller a kombinationen av lämpliga flaggbitar för de olika koordinat omvandlingarna som denna transformation utför. |
| const [TypeMaskRotation](../../aspose.imaging/matrix/typemaskrotation) | Denna konstant är en bitmask för någon av rotationsflaggans bitar. |
| const [TypeMaskScale](../../aspose.imaging/matrix/typemaskscale) | Denna konstant är en bitmask för vilken som helst av skalflaggbitarna. |
| const [TypeQuadrantRotation](../../aspose.imaging/matrix/typequadrantrotation) | Denna flaggbit indikerar att transformationen som definieras av detta objekt utför en kvadrantrotation med någon multipel av 90 grader in tillägg till de omvandlingar som indikeras av andra flaggbitar. En rotation ändrar vinklarna för vektorer med samma mängd oavsett den ursprungliga riktningen. av vektorn och utan att ändra längden på vektorn. Denna flaggbit är ömsesidigt uteslutande med flaggan TypeGeneralRotation. |
| const [TypeTranslation](../../aspose.imaging/matrix/typetranslation) | En översättning flyttar koordinaterna med en konstant mängd i x och y utan att ändra längden eller vinkeln på vektorerna. |
| const [TypeUniformScale](../../aspose.imaging/matrix/typeuniformscale) | En enhetlig skala multiplicerar längden på vektorer med samma mängd i både x- och y-riktningarna utan att ändra vinkeln mellan vektorer. Denna flaggbit är ömsesidigt uteslutande med flaggan TypeGeneralScale. |

### Anmärkningar

De flesta algoritmer hämtade från Suns AffineTransform.java. Javas namn för matriselement som används internt. Karta över java-namn till .net ettor till beskrivning: m00 M11 Skala X mx2 Scale She m10 M10 M10 M10 M10 M10 M10 M10 M10 M10 M2 M10 M10 M10 M10 M2 Översätt X m12 M32 Översätt Y

### Se även

* namnutrymme [Aspose.Imaging](../../aspose.imaging)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
