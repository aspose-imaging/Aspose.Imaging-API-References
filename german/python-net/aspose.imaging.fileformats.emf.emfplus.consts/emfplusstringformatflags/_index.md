---
title: "EmfPlusStringFormatFlags Aufzählung"
type: docs
weight: 410
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---

Die StringFormat-Flags geben Optionen für die grafische Textlayout‑Anordnung an, einschließlich Richtung, Beschneidung und Schriftartenverwaltung. Diese Flags können kombiniert werden, um mehrere Optionen festzulegen.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusStringFormatFlags

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| STRING_FORMAT_BYPASS_GDI | Dieses Flag **DÜRFT** verwendet werden, um einen implementierungsspezifischen Prozess zum Rendern von Text anzugeben. |
| STRING_FORMAT_DIRECTION_RIGHT_TO_LEFT | Wenn gesetzt, **SOLL** die Lesereihenfolge der Zeichenkette von rechts nach links sein. Für horizontalen Text bedeutet das, dass Zeichen von rechts nach links gelesen werden. Für vertikalen Text bedeutet das, dass Spalten von rechts nach links gelesen werden.<br/>            Wenn nicht gesetzt, **SOLL** horizontaler oder vertikaler Text von links nach rechts gelesen werden. |
| STRING_FORMAT_DIRECTION_VERTICAL | Wenn gesetzt, **SOLL** jede einzelne Textzeile vertikal auf dem Anzeigegerät gezeichnet werden.<br/>            Wenn nicht gesetzt, **SOLL** jede einzelne Textzeile horizontal gezeichnet werden, wobei jede neue Zeile unter der vorherigen liegt. |
| STRING_FORMAT_DISPLAY_FORMAT_CONTROL | Wenn gesetzt, **SOLL** Steuerzeichen in der Ausgabe als repräsentative Unicode‑Glyphen erscheinen. |
| STRING_FORMAT_LINE_LIMIT | Wenn gesetzt, **SOLL** der gesamte Text in Zeilen ausgegeben werden und **SOLL** NICHT vom Layout‑Rechteck der Zeichenkette abgeschnitten werden.<br/>            Wenn nicht gesetzt, **SOLL** das Textlayout fortgesetzt werden, bis alle Zeilen ausgegeben sind, oder bis weitere Zeilen aufgrund von Abschneiden nicht mehr sichtbar wären.<br/>            Dieses Flag kann verwendet werden, um entweder zu verhindern oder zu erlauben, dass eine Textzeile teilweise von einem Layout‑Rechteck verdeckt wird, das kein Vielfaches der Zeilenhöhe ist. Damit aller Text sichtbar ist, muss das Layout‑Rechteck mindestens so hoch sein wie die Höhe einer Zeile. |
| STRING_FORMAT_MEASURE_TRAILING_SPACES | Wenn gesetzt, muss das Leerzeichen am Ende jeder Zeile in die Messungen der Zeichenkettenlänge einbezogen werden.<br/>            Wenn nicht gesetzt, muss das Leerzeichen am Ende jeder Zeile von den Messungen der Zeichenkettenlänge ausgeschlossen werden. |
| STRING_FORMAT_NO_CLIP | Wenn gesetzt, sollte Text, der außerhalb des Zeichenlayout-Rechtecks liegt, angezeigt werden dürfen.<br/>            Wenn nicht gesetzt, sollte jeglicher Text, der außerhalb des Layout-Rechtecks liegt, abgeschnitten werden. |
| STRING_FORMAT_NO_FIT_BLACK_BOX | Wenn gesetzt, müssen Teile von Zeichen über das Textlayout‑Rechteck hinausragen dürfen.<br/>            Wenn nicht gesetzt, müssen Zeichen, die über die Grenzen des Textlayout‑Rechtecks hinausragen, neu positioniert werden, um das Überragen zu vermeiden.<br/>            Ein kursives "f" ist ein Beispiel für ein Zeichen, das überragende Teile haben kann. |
| STRING_FORMAT_NO_FONT_FALLBACK | Wenn gesetzt, sollte für Zeichen, die in der angeforderten Schriftart nicht unterstützt werden, eine alternative Schriftart verwendet werden.<br/>            Wenn nicht gesetzt, sollte ein in der angeforderten Schriftart fehlendes Zeichen als ein "Schrift fehlt"‑Zeichen angezeigt werden, das ein offenes Quadrat sein kann. |
| STRING_FORMAT_NO_WRAP | Wenn gesetzt, darf eine Zeichenkette, die über das Ende des Textlayout‑Rechtecks hinausgeht, nicht in die nächste Zeile umgebrochen werden.<br/>            Wenn nicht gesetzt, muss eine Zeichenkette, die über das Ende des Textlayout‑Rechtecks hinausgeht, an der letzten Wortgrenze innerhalb des Begrenzungsrechtecks getrennt werden, und der Rest der Zeichenkette muss in die nächste Zeile umgebrochen werden. |
