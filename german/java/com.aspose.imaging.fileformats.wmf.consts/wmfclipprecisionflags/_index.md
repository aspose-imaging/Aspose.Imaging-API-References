---
title: "WmfClipPrecisionFlags"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "ClipPrecision-Flags geben die Clipping-Genauigkeit an, die definiert, wie Zeichen, die teilweise außerhalb einer Clipping-Region liegen, abgeschnitten werden."
type: docs
weight: 14
url: /de/java/com.aspose.imaging.fileformats.wmf.consts/wmfclipprecisionflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfClipPrecisionFlags extends System.Enum
```

ClipPrecision-Flags geben die Clipping-Genauigkeit an, die definiert, wie Zeichen, die teilweise außerhalb einer Clipping-Region liegen, abgeschnitten werden. Diese Flags können kombiniert werden, um mehrere Optionen anzugeben.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Default](#Default) | Gibt an, dass das Standard-Clipping verwendet werden MUSS. |
| [Character](#Character) | Dieser Wert SOLLTE NICHT verwendet werden. |
| [Stroke](#Stroke) | Dieser Wert KANN zurückgegeben werden, wenn rasterisierte, TrueType- und Vektor-Schriften aufgelistet werden. |
| [LhAngles](#LhAngles) | Dieser Wert wird verwendet, um die Schriftrotation zu steuern, wie folgt: - Wenn gesetzt, SOLLTE die Rotation für alle Schriften durch die Ausrichtung des Koordinatensystems bestimmt werden; das heißt, ob die Ausrichtung linkshändig oder rechtshändig ist. |
| [TtAlways](#TtAlways) | Dieser Wert SOLLTE NICHT [34] verwendet werden. |
| [DfaDisable](#DfaDisable) | Dieser Wert gibt an, dass die Schriftzuordnung [35] ausgeschaltet werden SOLLTE. |
| [Embedded](#Embedded) | Dieser Wert gibt an, dass das Einbetten von Schriften verwendet werden MUSS, um Dokumentinhalte darzustellen; eingebettete Schriften sind schreibgeschützt. |
### Default {#Default}
```
public static final byte Default
```


Gibt an, dass das Standard-Clipping verwendet werden MUSS.

### Character {#Character}
```
public static final byte Character
```


Dieser Wert SOLLTE NICHT verwendet werden.

### Stroke {#Stroke}
```
public static final byte Stroke
```


Dieser Wert KANN zurückgegeben werden, wenn rasterisierte, TrueType- und Vektor-Schriften aufgelistet werden. [33] (Windows NT 3.1, Windows NT 3.5, Windows NT 3.51, Windows NT 4.0, Windows 2000 und Windows XP: Dieser Wert wird immer zurückgegeben, wenn Schriften aufgelistet werden.)

### LhAngles {#LhAngles}
```
public static final byte LhAngles
```


Dieser Wert wird verwendet, um die Schriftrotation zu steuern, wie folgt: - Wenn gesetzt, SOLLTE die Rotation für alle Schriften durch die Ausrichtung des Koordinatensystems bestimmt werden; das heißt, ob die Ausrichtung linkshändig oder rechtshändig ist. - Wenn nicht gesetzt, SOLLTEN Geräteschriften gegen den Uhrzeigersinn rotieren, aber die Rotation anderer Schriften SOLLTE durch die Ausrichtung des Koordinatensystems bestimmt werden.

### TtAlways {#TtAlways}
```
public static final byte TtAlways
```


Dieser Wert SOLLTE NICHT [34] verwendet werden. [34] Dieser Wert wird in den folgenden Windows-Versionen ignoriert: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### DfaDisable {#DfaDisable}
```
public static final byte DfaDisable
```


Dieser Wert gibt an, dass die Schriftzuordnung [35] ausgeschaltet werden SOLLTE. [35] Dieser Wert wird in Windows 95, Windows 98 und Windows Millennium Edition nicht unterstützt. Die Schriftzuordnung ist in Windows 2000, Windows XP und Windows Server 2003 ausgeschaltet. Dieser Wert wird in diesen Windows-Versionen ignoriert: - Windows Vista - Windows Server 2008 - Windows 7 - Windows Server 2008 R2 - Windows 8 - Windows Server 2012 - Windows 8.1 - Windows Server 2012 R2

### Embedded {#Embedded}
```
public static final byte Embedded
```


Dieser Wert gibt an, dass das Einbetten von Schriften verwendet werden MUSS, um Dokumentinhalte darzustellen; eingebettete Schriften sind schreibgeschützt.

