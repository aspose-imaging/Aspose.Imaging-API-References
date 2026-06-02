---
title: "EmfPlusStringFormatFlags"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die StringFormat-Flags geben Optionen für die Grafik-Textanordnung an, einschließlich Richtung, Beschneidung und Schriftartenhandhabung."
type: docs
weight: 50
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusStringFormatFlags extends System.Enum
```

Die StringFormat-Flags geben Optionen für die Grafik-Textanordnung an, einschließlich Richtung, Beschneidung und Schriftartenhandhabung. Diese Flags können kombiniert werden, um mehrere Optionen anzugeben.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [StringFormatDirectionRightToLeft](#StringFormatDirectionRightToLeft) | Wenn gesetzt, sollte die Lesereihenfolge der Zeichenkette von rechts nach links sein. |
| [StringFormatDirectionVertical](#StringFormatDirectionVertical) | Wenn gesetzt, sollten einzelne Textzeilen vertikal auf dem Anzeigegerät gezeichnet werden. |
| [StringFormatNoFitBlackBox](#StringFormatNoFitBlackBox) | Wenn gesetzt, dürfen Teile von Zeichen über das Textanordnungsrechteck hinausragen. |
| [StringFormatDisplayFormatControl](#StringFormatDisplayFormatControl) | Wenn gesetzt, sollten Steuerzeichen in der Ausgabe als repräsentative Unicode-Glyphen erscheinen. |
| [StringFormatNoFontFallback](#StringFormatNoFontFallback) | Wenn gesetzt, sollte eine alternative Schriftart für Zeichen verwendet werden, die in der angeforderten Schriftart nicht unterstützt werden. |
| [StringFormatMeasureTrailingSpaces](#StringFormatMeasureTrailingSpaces) | Wenn gesetzt, muss das Leerzeichen am Ende jeder Zeile in die Messung der Zeichenkettenlänge einbezogen werden. |
| [StringFormatNoWrap](#StringFormatNoWrap) | Wenn gesetzt, darf eine Zeichenkette, die über das Ende des Textanordnungsrechtecks hinausgeht, nicht in die nächste Zeile umgebrochen werden. |
| [StringFormatLineLimit](#StringFormatLineLimit) | Wenn gesetzt, sollten ganze Textzeilen ausgegeben werden und sollten nicht vom Layoutrechteck der Zeichenkette abgeschnitten werden. |
| [StringFormatNoClip](#StringFormatNoClip) | Wenn gesetzt, sollte Text, der außerhalb des Layoutrechtecks der Zeichenkette liegt, angezeigt werden dürfen. |
| [StringFormatBypassGdi](#StringFormatBypassGdi) | Dieses Flag kann verwendet werden, um einen implementierungsspezifischen Prozess zum Rendern von Text anzugeben. |
### StringFormatDirectionRightToLeft {#StringFormatDirectionRightToLeft}
```
public static final long StringFormatDirectionRightToLeft
```


Wenn gesetzt, sollte die Lesereihenfolge der Zeichenkette von rechts nach links sein. Für horizontalen Text bedeutet dies, dass Zeichen von rechts nach links gelesen werden. Für vertikalen Text bedeutet dies, dass Spalten von rechts nach links gelesen werden. Wenn nicht gesetzt, sollten horizontale oder vertikale Texte von links nach rechts gelesen werden.

--------------------

Die Grafik-Textanordnung wird durch [EmfPlusStringFormat](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat)-Objekte festgelegt.

### StringFormatDirectionVertical {#StringFormatDirectionVertical}
```
public static final long StringFormatDirectionVertical
```


Wenn gesetzt, sollten einzelne Textzeilen vertikal auf dem Anzeigegerät gezeichnet werden. Wenn nicht gesetzt, sollten einzelne Textzeilen horizontal gezeichnet werden, wobei jede neue Zeile unter der vorherigen liegt.

### StringFormatNoFitBlackBox {#StringFormatNoFitBlackBox}
```
public static final long StringFormatNoFitBlackBox
```


Wenn gesetzt, dürfen Teile von Zeichen über das Textanordnungsrechteck hinausragen. Wenn nicht gesetzt, müssen Zeichen, die die Grenzen des Textanordnungsrechtecks überschreiten, neu positioniert werden, um ein Überragen zu vermeiden. Ein kursives "f" ist ein Beispiel für ein Zeichen, das überragende Teile haben kann.

### StringFormatDisplayFormatControl {#StringFormatDisplayFormatControl}
```
public static final long StringFormatDisplayFormatControl
```


Wenn gesetzt, sollten Steuerzeichen in der Ausgabe als repräsentative Unicode-Glyphen erscheinen.

### StringFormatNoFontFallback {#StringFormatNoFontFallback}
```
public static final long StringFormatNoFontFallback
```


Wenn gesetzt, sollte eine alternative Schriftart für Zeichen verwendet werden, die in der angeforderten Schriftart nicht unterstützt werden. Wenn nicht gesetzt, sollte ein fehlendes Zeichen in der angeforderten Schriftart als ein "Schrift fehlt"-Zeichen erscheinen, das ein offenes Quadrat sein kann.

### StringFormatMeasureTrailingSpaces {#StringFormatMeasureTrailingSpaces}
```
public static final long StringFormatMeasureTrailingSpaces
```


Wenn gesetzt, muss das Leerzeichen am Ende jeder Zeile in die Messung der Zeichenkettenlänge einbezogen werden. Wenn nicht gesetzt, muss das Leerzeichen am Ende jeder Zeile von der Messung der Zeichenkettenlänge ausgeschlossen werden.

### StringFormatNoWrap {#StringFormatNoWrap}
```
public static final long StringFormatNoWrap
```


Wenn gesetzt, darf eine Zeichenkette, die über das Ende des Textanordnungsrechtecks hinausgeht, nicht in die nächste Zeile umgebrochen werden. Wenn nicht gesetzt, muss eine Zeichenkette, die über das Ende des Textanordnungsrechtecks hinausgeht, an der letzten Wortgrenze innerhalb des Begrenzungsrechtecks getrennt werden, und der Rest der Zeichenkette muss in die nächste Zeile umgebrochen werden.

### StringFormatLineLimit {#StringFormatLineLimit}
```
public static final long StringFormatLineLimit
```


Wenn gesetzt, sollten ganze Textzeilen ausgegeben werden und sollten nicht vom Layoutrechteck der Zeichenkette abgeschnitten werden. Wenn nicht gesetzt, sollte die Textanordnung fortgesetzt werden, bis alle Zeilen ausgegeben sind, oder bis zusätzliche Zeilen aufgrund von Abschneiden nicht mehr sichtbar wären. Dieses Flag kann verwendet werden, um entweder zu verhindern oder zu erlauben, dass eine Textzeile teilweise von einem Layoutrechteck, das kein Vielfaches der Zeilenhöhe ist, verdeckt wird. Damit der gesamte Text sichtbar ist, muss das Layoutrechteck mindestens so hoch sein wie die Höhe einer Zeile.

### StringFormatNoClip {#StringFormatNoClip}
```
public static final long StringFormatNoClip
```


Wenn gesetzt, sollte Text, der außerhalb des Layoutrechtecks der Zeichenkette liegt, angezeigt werden dürfen. Wenn nicht gesetzt, sollte aller Text, der außerhalb des Layoutrechtecks liegt, abgeschnitten werden.

### StringFormatBypassGdi {#StringFormatBypassGdi}
```
public static final long StringFormatBypassGdi
```


Dieses Flag kann verwendet werden, um einen implementierungsspezifischen Prozess zum Rendern von Text anzugeben.

