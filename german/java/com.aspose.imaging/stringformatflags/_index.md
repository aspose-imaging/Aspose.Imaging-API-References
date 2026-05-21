---
title: "StringFormatFlags"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Gibt die Anzeige- und Layout-Informationen für Textzeichenfolgen an."
type: docs
weight: 113
url: /de/java/com.aspose.imaging/stringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StringFormatFlags extends System.Enum
```

Gibt die Anzeige- und Layout-Informationen für Textzeichenfolgen an.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [DirectionRightToLeft](#DirectionRightToLeft) | Text wird von rechts nach links angezeigt. |
| [DirectionVertical](#DirectionVertical) | Text ist vertikal ausgerichtet. |
| [FitBlackBox](#FitBlackBox) | Teile von Zeichen dürfen über das Layoutrechteck der Zeichenkette hinausragen. |
| [DisplayFormatControl](#DisplayFormatControl) | Steuerzeichen wie das left-to-right mark werden in der Ausgabe mit einem repräsentativen Glyphen angezeigt. |
| [NoFontFallback](#NoFontFallback) | Das Ausweichen auf alternative Schriftarten für Zeichen, die in der angeforderten Schriftart nicht unterstützt werden, ist deaktiviert. |
| [MeasureTrailingSpaces](#MeasureTrailingSpaces) | Enthält das nachfolgende Leerzeichen am Ende jeder Zeile. |
| [NoWrap](#NoWrap) | Der Zeilenumbruch zwischen Zeilen beim Formatieren innerhalb eines Rechtecks ist deaktiviert. |
| [LineLimit](#LineLimit) | Nur ganze Zeilen werden im Formatierungsrechteck angeordnet. |
| [NoClip](#NoClip) | Überstehende Teile von Glyphen und nicht umgebrochener Text, die außerhalb des Formatierungsrechtecks liegen, dürfen angezeigt werden. |
| [ExactAlignment](#ExactAlignment) | Die genaue Ausrichtung, korrekte Polsterung GDI+ |
### DirectionRightToLeft {#DirectionRightToLeft}
```
public static final int DirectionRightToLeft
```


Text wird von rechts nach links angezeigt.

### DirectionVertical {#DirectionVertical}
```
public static final int DirectionVertical
```


Text ist vertikal ausgerichtet.

### FitBlackBox {#FitBlackBox}
```
public static final int FitBlackBox
```


Teile von Zeichen dürfen über das Layoutrechteck der Zeichenkette hinausragen. Standardmäßig werden Zeichen neu positioniert, um ein Überstehen zu vermeiden.

### DisplayFormatControl {#DisplayFormatControl}
```
public static final int DisplayFormatControl
```


Steuerzeichen wie das left-to-right mark werden in der Ausgabe mit einem repräsentativen Glyphen angezeigt.

### NoFontFallback {#NoFontFallback}
```
public static final int NoFontFallback
```


Das Ausweichen auf alternative Schriftarten für Zeichen, die in der angeforderten Schriftart nicht unterstützt werden, ist deaktiviert. Fehlende Zeichen werden mit dem fehlenden Glyphen der Schriftart angezeigt, üblicherweise ein offenes Quadrat.

### MeasureTrailingSpaces {#MeasureTrailingSpaces}
```
public static final int MeasureTrailingSpaces
```


Enthält das nachfolgende Leerzeichen am Ende jeder Zeile. Standardmäßig schließt das von der MeasureString‑Methode zurückgegebene Begrenzungsrechteck das Leerzeichen am Ende jeder Zeile aus. Setzen Sie dieses Flag, um dieses Leerzeichen in die Messung einzubeziehen.

### NoWrap {#NoWrap}
```
public static final int NoWrap
```


Der Zeilenumbruch zwischen Zeilen beim Formatieren innerhalb eines Rechtecks ist deaktiviert. Dieses Flag wird impliziert, wenn anstelle eines Rechtecks ein Punkt übergeben wird oder wenn das angegebene Rechteck eine Zeilenlänge von Null hat.

### LineLimit {#LineLimit}
```
public static final int LineLimit
```


Nur ganze Zeilen werden im Formatierungsrechteck angeordnet. Standardmäßig wird das Layout bis zum Ende des Textes fortgesetzt oder bis keine weiteren Zeilen mehr sichtbar sind aufgrund von Clipping, je nachdem, was zuerst eintritt. Beachten Sie, dass die Standardeinstellungen zulassen, dass die letzte Zeile teilweise von einem Formatierungsrechteck verdeckt wird, das kein ganzzahliges Vielfaches der Zeilenhöhe ist. Um sicherzustellen, dass nur ganze Zeilen angezeigt werden, geben Sie diesen Wert an und achten Sie darauf, ein Formatierungsrechteck bereitzustellen, das mindestens so hoch ist wie die Höhe einer Zeile.

### NoClip {#NoClip}
```
public static final int NoClip
```


Überstehende Teile von Glyphen und nicht umgebrochener Text, die außerhalb des Formatierungsrechtecks liegen, dürfen angezeigt werden. Standardmäßig werden alle Texte und Glyphenteile, die außerhalb des Formatierungsrechtecks liegen, abgeschnitten.

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


Die genaue Ausrichtung, korrekte Polsterung GDI+

