---
title: "WmfFontQuality"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die FontQuality‑Aufzählung gibt an, wie genau die Attribute der logischen Schrift mit denen der physischen Schrift beim Rendern von Text übereinstimmen sollen."
type: docs
weight: 19
url: /de/java/com.aspose.imaging.fileformats.wmf.consts/wmffontquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfFontQuality extends System.Enum
```

Die FontQuality‑Aufzählung gibt an, wie genau die Attribute der logischen Schrift mit denen der physischen Schrift beim Rendern von Text übereinstimmen sollen.
## Felder

| Feld | Beschreibung |
| --- | --- |
| [Default](#Default) | Gibt an, dass die Zeichenqualität der Schriftart keine Rolle spielt, sodass DRAFT verwendet werden kann. |
| [Draft](#Draft) | Gibt an, dass die Zeichenqualität der Schriftart weniger wichtig ist als die Übereinstimmung der logischen Attribute. |
| [Proof](#Proof) | Gibt an, dass die Zeichenqualität der Schriftart wichtiger ist als die Übereinstimmung der logischen Attribute. |
| [Nonantialiased](#Nonantialiased) | Gibt an, dass Anti-Aliasing NICHT verwendet werden SOLLTE, wenn Text gerendert wird |
| [Antialiased](#Antialiased) | Gibt an, dass Anti-Aliasing verwendet werden SOLLTE, wenn Text gerendert wird, falls die Schriftart dies unterstützt. |
| [Cleartype](#Cleartype) | Gibt an, dass ClearType-Anti-Aliasing verwendet werden SOLLTE, wenn Text gerendert wird, falls die Schriftart dies unterstützt. |
### Default {#Default}
```
public static final byte Default
```


Gibt an, dass die Zeichenqualität der Schriftart keine Rolle spielt, sodass DRAFT verwendet werden kann.

### Draft {#Draft}
```
public static final byte Draft
```


Gibt an, dass die Zeichenqualität der Schriftart weniger wichtig ist als die Übereinstimmung der logischen Attribute. Für gerasterte Schriften SOLLTE das Skalieren aktiviert sein, was bedeutet, dass mehr Schriftgrößen verfügbar sind.

### Proof {#Proof}
```
public static final byte Proof
```


Gibt an, dass die Zeichenqualität der Schriftart wichtiger ist als die Übereinstimmung der logischen Attribute. Für gerasterte Schriften SOLLTE das Skalieren deaktiviert sein, und die Schrift, die der Größe am nächsten kommt, SOLLTE ausgewählt werden.

### Nonantialiased {#Nonantialiased}
```
public static final byte Nonantialiased
```


Gibt an, dass Anti-Aliasing NICHT verwendet werden SOLLTE, wenn Text gerendert wird

### Antialiased {#Antialiased}
```
public static final byte Antialiased
```


Gibt an, dass Anti-Aliasing verwendet werden SOLLTE, wenn Text gerendert wird, falls die Schriftart dies unterstützt.

### Cleartype {#Cleartype}
```
public static final byte Cleartype
```


Gibt an, dass ClearType-Anti-Aliasing verwendet werden SOLLTE, wenn Text gerendert wird, falls die Schriftart dies unterstützt.

