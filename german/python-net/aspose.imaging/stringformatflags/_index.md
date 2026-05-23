---
title: "Aufzählung StringFormatFlags"
type: docs
weight: 11220
url: /de/python-net/aspose.imaging/stringformatflags/
---

Gibt die Anzeige‑ und Layoutinformationen für Textzeichenfolgen an.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StringFormatFlags

## **Members**
| **Member name** | **Beschreibung** |
| :- | :- |
| DIRECTION_RIGHT_TO_LEFT | Text wird von rechts nach links angezeigt. |
| DIRECTION_VERTICAL | Text ist vertikal ausgerichtet. |
| DISPLAY_FORMAT_CONTROL | Steuerzeichen wie das Links‑nach‑Rechts‑Markierung werden in der Ausgabe mit einem repräsentativen Glyphen angezeigt. |
| EXACT_ALIGNMENT | Die exakte Ausrichtung, korrektes Padding GDI+ |
| FIT_BLACK_BOX | Teile von Zeichen dürfen über den Layout‑Rechteck des Strings hinausragen. Standardmäßig werden Zeichen neu positioniert, um ein Überragen zu vermeiden. |
| LINE_LIMIT | Nur ganze Zeilen werden im Formatierungsrechteck angeordnet. Standardmäßig wird das Layout bis zum Ende des Textes fortgesetzt oder bis keine Zeilen mehr sichtbar sind aufgrund von Clipping, je nachdem, was zuerst eintritt.<br/>            Beachten Sie, dass die Standardeinstellungen zulassen, dass die letzte Zeile teilweise von einem Formatierungsrechteck verdeckt wird, das kein ganzes Vielfaches der Zeilenhöhe ist. Um sicherzustellen, dass nur ganze Zeilen sichtbar sind,<br/>            geben Sie diesen Wert an und achten Sie darauf, ein Formatierungsrechteck bereitzustellen, das mindestens so hoch ist wie die Höhe einer Zeile. |
| MEASURE_TRAILING_SPACES | Schließt das nachfolgende Leerzeichen am Ende jeder Zeile ein. Standardmäßig schließt das von der MeasureString‑Methode zurückgegebene Begrenzungsrechteck das Leerzeichen am Ende jeder Zeile aus. Setzen Sie dieses Flag, um dieses Leerzeichen in die Messung einzubeziehen. |
| NO_CLIP | Überstehende Teile von Glyphen und nicht umbrochener Text, die außerhalb des Formatierungsrechtecks reichen, dürfen angezeigt werden. Standardmäßig werden alle Texte und Glyphen‑Teile, die außerhalb des Formatierungsrechtecks reichen, abgeschnitten. |
| NO_FONT_FALLBACK | Das Zurückgreifen auf alternative Schriftarten für Zeichen, die in der angeforderten Schriftart nicht unterstützt werden, ist deaktiviert. Fehlende Zeichen werden mit dem fehlenden Glyphen der Schriftart angezeigt, üblicherweise ein offenes Quadrat. |
| NO_WRAP | Der Textumbruch zwischen Zeilen beim Formatieren innerhalb eines Rechtecks ist deaktiviert. Dieses Flag wird impliziert, wenn ein Punkt anstelle eines Rechtecks übergeben wird oder wenn das angegebene Rechteck eine Zeilenlänge von Null hat. |
