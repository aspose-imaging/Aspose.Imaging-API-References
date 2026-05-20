---
title: "EmfPlusStringFormatFlags"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Les indicateurs StringFormat spécifient des options pour la mise en page du texte graphique, y compris le découpage de direction et la gestion des polices."
type: docs
weight: 50
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusStringFormatFlags extends System.Enum
```

Les indicateurs StringFormat spécifient des options pour la mise en page du texte graphique, y compris la direction, le découpage et la gestion des polices. Ces indicateurs peuvent être combinés pour spécifier plusieurs options.
## Champs

| Champ | Description |
| --- | --- |
| [StringFormatDirectionRightToLeft](#StringFormatDirectionRightToLeft) | Si défini, l'ordre de lecture de la chaîne DOIT être de droite à gauche. |
| [StringFormatDirectionVertical](#StringFormatDirectionVertical) | Si défini, les lignes individuelles de texte DOIVENT être dessinées verticalement sur le dispositif d'affichage. |
| [StringFormatNoFitBlackBox](#StringFormatNoFitBlackBox) | Si défini, les parties des caractères DOIVENT être autorisées à dépasser le rectangle de mise en page du texte. |
| [StringFormatDisplayFormatControl](#StringFormatDisplayFormatControl) | Si défini, les caractères de contrôle DOIVENT apparaître dans la sortie sous forme de glyphes Unicode représentatifs. |
| [StringFormatNoFontFallback](#StringFormatNoFontFallback) | Si défini, une police alternative DOIT être utilisée pour les caractères qui ne sont pas pris en charge par la police demandée. |
| [StringFormatMeasureTrailingSpaces](#StringFormatMeasureTrailingSpaces) | Si défini, l'espace à la fin de chaque ligne DOIT être inclus dans les mesures de la longueur de la chaîne. |
| [StringFormatNoWrap](#StringFormatNoWrap) | Si défini, une chaîne qui dépasse la fin du rectangle de mise en page du texte NE DOIT PAS être renvoyée à la ligne suivante. |
| [StringFormatLineLimit](#StringFormatLineLimit) | Si défini, les lignes complètes de texte DOIVENT être émises et NE DOIVENT PAS être coupées par le rectangle de mise en page de la chaîne. |
| [StringFormatNoClip](#StringFormatNoClip) | Si défini, le texte qui dépasse le rectangle de mise en page de la chaîne DOIT être autorisé à s'afficher. |
| [StringFormatBypassGdi](#StringFormatBypassGdi) | Ce drapeau PEUT être utilisé pour spécifier un processus spécifique à l'implémentation pour le rendu du texte. |
### StringFormatDirectionRightToLeft {#StringFormatDirectionRightToLeft}
```
public static final long StringFormatDirectionRightToLeft
```


Si défini, l'ordre de lecture de la chaîne DOIT être de droite à gauche. Pour le texte horizontal, cela signifie que les caractères sont lus de droite à gauche. Pour le texte vertical, cela signifie que les colonnes sont lues de droite à gauche. Si désactivé, le texte horizontal ou vertical DOIT être lu de gauche à droite.

--------------------

La mise en page du texte graphique est spécifiée par les objets [EmfPlusStringFormat](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat).

### StringFormatDirectionVertical {#StringFormatDirectionVertical}
```
public static final long StringFormatDirectionVertical
```


Si défini, les lignes individuelles de texte DOIVENT être dessinées verticalement sur le dispositif d'affichage. Si désactivé, les lignes individuelles de texte DOIVENT être dessinées horizontalement, chaque nouvelle ligne étant placée sous la précédente.

### StringFormatNoFitBlackBox {#StringFormatNoFitBlackBox}
```
public static final long StringFormatNoFitBlackBox
```


Si défini, les parties des caractères DOIVENT être autorisées à dépasser le rectangle de mise en page du texte. Si désactivé, les caractères qui dépassent les limites du rectangle de mise en page du texte DOIVENT être repositionnés pour éviter le débordement. Un italique, \"f\", est un exemple de caractère pouvant avoir des parties qui débordent.

### StringFormatDisplayFormatControl {#StringFormatDisplayFormatControl}
```
public static final long StringFormatDisplayFormatControl
```


Si défini, les caractères de contrôle DOIVENT apparaître dans la sortie sous forme de glyphes Unicode représentatifs.

### StringFormatNoFontFallback {#StringFormatNoFontFallback}
```
public static final long StringFormatNoFontFallback
```


Si défini, une police alternative DOIT être utilisée pour les caractères qui ne sont pas pris en charge par la police demandée. Si désactivé, un caractère manquant dans la police demandée DOIT apparaître comme un caractère \"font missing\", qui PEUT être un carré ouvert.

### StringFormatMeasureTrailingSpaces {#StringFormatMeasureTrailingSpaces}
```
public static final long StringFormatMeasureTrailingSpaces
```


Si défini, l'espace à la fin de chaque ligne DOIT être inclus dans les mesures de la longueur de la chaîne. Si désactivé, l'espace à la fin de chaque ligne DOIT être exclu des mesures de la longueur de la chaîne.

### StringFormatNoWrap {#StringFormatNoWrap}
```
public static final long StringFormatNoWrap
```


Si défini, une chaîne qui dépasse la fin du rectangle de mise en page du texte NE DOIT PAS être renvoyée à la ligne suivante. Si désactivé, une chaîne qui dépasse la fin du rectangle de mise en page du texte DOIT être coupée à la dernière frontière de mot à l'intérieur du rectangle englobant, et le reste de la chaîne DOIT être renvoyé à la ligne suivante.

### StringFormatLineLimit {#StringFormatLineLimit}
```
public static final long StringFormatLineLimit
```


Si défini, les lignes complètes de texte DOIVENT être émises et NE DOIVENT PAS être coupées par le rectangle de mise en page de la chaîne. Si désactivé, la mise en page du texte DOIT se poursuivre jusqu'à ce que toutes les lignes soient émises, ou jusqu'à ce que des lignes supplémentaires ne soient pas visibles à cause du rognage. Ce drapeau peut être utilisé soit pour refuser, soit pour autoriser qu'une ligne de texte soit partiellement masquée par un rectangle de mise en page qui n'est pas un multiple de la hauteur de ligne. Pour que tout le texte soit visible, le rectangle de mise en page doit être au moins aussi haut que la hauteur d'une ligne.

### StringFormatNoClip {#StringFormatNoClip}
```
public static final long StringFormatNoClip
```


Si défini, le texte qui dépasse le rectangle de mise en page de la chaîne DOIT être autorisé à s'afficher. Si désactivé, tout texte qui dépasse le rectangle de mise en page DOIT être coupé.

### StringFormatBypassGdi {#StringFormatBypassGdi}
```
public static final long StringFormatBypassGdi
```


Ce drapeau PEUT être utilisé pour spécifier un processus spécifique à l'implémentation pour le rendu du texte.

