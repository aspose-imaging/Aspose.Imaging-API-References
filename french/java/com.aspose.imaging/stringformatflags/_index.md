---
title: "StringFormatFlags"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Spécifie les informations d'affichage et de mise en page pour les chaînes de texte."
type: docs
weight: 113
url: /fr/java/com.aspose.imaging/stringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StringFormatFlags extends System.Enum
```

Spécifie les informations d'affichage et de mise en page pour les chaînes de texte.
## Champs

| Champ | Description |
| --- | --- |
| [DirectionRightToLeft](#DirectionRightToLeft) | Le texte est affiché de droite à gauche. |
| [DirectionVertical](#DirectionVertical) | Le texte est aligné verticalement. |
| [FitBlackBox](#FitBlackBox) | Les parties des caractères sont autorisées à dépasser le rectangle de mise en page de la chaîne. |
| [DisplayFormatControl](#DisplayFormatControl) | Les caractères de contrôle tels que la marque de gauche à droite sont affichés dans la sortie avec un glyphe représentatif. |
| [NoFontFallback](#NoFontFallback) | Le recours à des polices alternatives pour les caractères non pris en charge dans la police demandée est désactivé. |
| [MeasureTrailingSpaces](#MeasureTrailingSpaces) | Inclut l'espace de fin à la fin de chaque ligne. |
| [NoWrap](#NoWrap) | Le retour à la ligne entre les lignes lors du formatage dans un rectangle est désactivé. |
| [LineLimit](#LineLimit) | Seules les lignes complètes sont disposées dans le rectangle de formatage. |
| [NoClip](#NoClip) | Les parties dépassant des glyphes, et le texte non enveloppé qui dépasse le rectangle de formatage sont autorisés à s'afficher. |
| [ExactAlignment](#ExactAlignment) | L'alignement exact, le remplissage correct GDI+ |
### DirectionRightToLeft {#DirectionRightToLeft}
```
public static final int DirectionRightToLeft
```


Le texte est affiché de droite à gauche.

### DirectionVertical {#DirectionVertical}
```
public static final int DirectionVertical
```


Le texte est aligné verticalement.

### FitBlackBox {#FitBlackBox}
```
public static final int FitBlackBox
```


Les parties des caractères sont autorisées à dépasser le rectangle de mise en page de la chaîne. Par défaut, les caractères sont repositionnés pour éviter tout dépassement.

### DisplayFormatControl {#DisplayFormatControl}
```
public static final int DisplayFormatControl
```


Les caractères de contrôle tels que la marque de gauche à droite sont affichés dans la sortie avec un glyphe représentatif.

### NoFontFallback {#NoFontFallback}
```
public static final int NoFontFallback
```


Le recours à des polices alternatives pour les caractères non pris en charge dans la police demandée est désactivé. Tout caractère manquant est affiché avec le glyphe manquant de la police, généralement un carré ouvert.

### MeasureTrailingSpaces {#MeasureTrailingSpaces}
```
public static final int MeasureTrailingSpaces
```


Inclut l'espace de fin à la fin de chaque ligne. Par défaut, le rectangle de délimitation retourné par la méthode MeasureString exclut l'espace à la fin de chaque ligne. Définissez ce drapeau pour inclure cet espace dans la mesure.

### NoWrap {#NoWrap}
```
public static final int NoWrap
```


Le retour à la ligne entre les lignes lors du formatage dans un rectangle est désactivé. Ce drapeau est implicite lorsqu'un point est passé au lieu d'un rectangle, ou lorsque le rectangle spécifié a une longueur de ligne nulle.

### LineLimit {#LineLimit}
```
public static final int LineLimit
```


Seules les lignes complètes sont disposées dans le rectangle de formatage. Par défaut, la disposition continue jusqu'à la fin du texte, ou jusqu'à ce qu'aucune ligne supplémentaire ne soit visible à cause du rognage, selon ce qui survient en premier. Notez que les paramètres par défaut permettent à la dernière ligne d'être partiellement masquée par un rectangle de formatage qui n'est pas un multiple entier de la hauteur de ligne. Pour garantir que seules les lignes entières soient visibles, spécifiez cette valeur et veillez à fournir un rectangle de formatage d'au moins la hauteur d'une ligne.

### NoClip {#NoClip}
```
public static final int NoClip
```


Les parties dépassant des glyphes, et le texte non enveloppé qui dépasse le rectangle de formatage sont autorisés à s'afficher. Par défaut, tout texte et toute partie de glyphe dépassant le rectangle de formatage sont rognés.

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


L'alignement exact, le remplissage correct GDI+

