---
title: "EmfPlusColorBalanceEffect"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das ColorBalanceEffect‑Objekt gibt Anpassungen der relativen Anteile von Rot, Grün und Blau in einem Bild an."
type: docs
weight: 26
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorbalanceeffect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageEffectsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageeffectsobjecttype)
```
public final class EmfPlusColorBalanceEffect extends EmfPlusImageEffectsObjectType
```

Das ColorBalanceEffect-Objekt gibt Anpassungen der relativen Anteile von Rot, Grün und Blau in einem Bild an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusColorBalanceEffect()](#EmfPlusColorBalanceEffect--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCyanRed()](#getCyanRed--) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die eine Änderung des Rotanteils im Bild angibt. |
| [setCyanRed(int value)](#setCyanRed-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die eine Änderung des Rotanteils im Bild angibt. |
| [getMagentaGreen()](#getMagentaGreen--) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die eine Änderung des Grünanteils im Bild angibt. |
| [setMagentaGreen(int value)](#setMagentaGreen-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die eine Änderung des Grünanteils im Bild angibt. |
| [getYellowBlue()](#getYellowBlue--) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die eine Änderung des Blauanteils im Bild angibt. |
| [setYellowBlue(int value)](#setYellowBlue-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die eine Änderung des Blauanteils im Bild angibt. |
### EmfPlusColorBalanceEffect() {#EmfPlusColorBalanceEffect--}
```
public EmfPlusColorBalanceEffect()
```


### getCyanRed() {#getCyanRed--}
```
public int getCyanRed()
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die eine Änderung des Rotanteils im Bild angibt. Dieser Wert MUST im Bereich -100 bis 100 liegen, mit folgenden Effekten: -100 \\u2264 Wert < 0: Wenn der Wert sinkt, sollte der Rotanteil im Bild abnehmen und der Cyananteil zunehmen. 0: Ein Wert von 0 gibt an, dass die Anteile von Rot und Cyan sich NICHT ändern dürfen. 0 < Wert \\u2264 100: Wenn der Wert steigt, sollte der Rotanteil im Bild zunehmen und der Cyananteil abnehmen.

**Returns:**
int
### setCyanRed(int value) {#setCyanRed-int-}
```
public void setCyanRed(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die eine Änderung des Rotanteils im Bild angibt. Dieser Wert MUST im Bereich -100 bis 100 liegen, mit folgenden Effekten: -100 \\u2264 Wert < 0: Wenn der Wert sinkt, sollte der Rotanteil im Bild abnehmen und der Cyananteil zunehmen. 0: Ein Wert von 0 gibt an, dass die Anteile von Rot und Cyan sich NICHT ändern dürfen. 0 < Wert \\u2264 100: Wenn der Wert steigt, sollte der Rotanteil im Bild zunehmen und der Cyananteil abnehmen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getMagentaGreen() {#getMagentaGreen--}
```
public int getMagentaGreen()
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die eine Änderung des Grünanteils im Bild angibt. Dieser Wert MUST im Bereich -100 bis 100 liegen, mit folgenden Effekten: -100 \\u2264 Wert < 0: Wenn der Wert sinkt, sollte der Grünanteil im Bild abnehmen und der Magentaanteil zunehmen. 0: Ein Wert von 0 gibt an, dass die Anteile von Grün und Magenta sich NICHT ändern dürfen. 0 < Wert \\u2264 100: Wenn der Wert steigt, sollte der Grünanteil im Bild zunehmen und der Magentaanteil abnehmen.

**Returns:**
int
### setMagentaGreen(int value) {#setMagentaGreen-int-}
```
public void setMagentaGreen(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die eine Änderung des Grünanteils im Bild angibt. Dieser Wert MUST im Bereich -100 bis 100 liegen, mit folgenden Effekten: -100 \\u2264 Wert < 0: Wenn der Wert sinkt, sollte der Grünanteil im Bild abnehmen und der Magentaanteil zunehmen. 0: Ein Wert von 0 gibt an, dass die Anteile von Grün und Magenta sich NICHT ändern dürfen. 0 < Wert \\u2264 100: Wenn der Wert steigt, sollte der Grünanteil im Bild zunehmen und der Magentaanteil abnehmen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getYellowBlue() {#getYellowBlue--}
```
public int getYellowBlue()
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die eine Änderung des Blauanteils im Bild angibt. Dieser Wert MUST im Bereich -100 bis 100 liegen, mit folgenden Effekten: -100 \\u2264 Wert < 0: Wenn der Wert sinkt, sollte der Blauanteil im Bild abnehmen und der Gelbanteil zunehmen. 0: Ein Wert von 0 gibt an, dass die Anteile von Blau und Gelb sich NICHT ändern dürfen. 0 < Wert \\u2264 100: Wenn der Wert steigt, sollte der Blauanteil im Bild zunehmen und der Gelbanteil abnehmen.

**Returns:**
int
### setYellowBlue(int value) {#setYellowBlue-int-}
```
public void setYellowBlue(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenbehaftete Ganzzahl, die eine Änderung des Blauanteils im Bild angibt. Dieser Wert MUST im Bereich -100 bis 100 liegen, mit folgenden Effekten: -100 \\u2264 Wert < 0: Wenn der Wert sinkt, sollte der Blauanteil im Bild abnehmen und der Gelbanteil zunehmen. 0: Ein Wert von 0 gibt an, dass die Anteile von Blau und Gelb sich NICHT ändern dürfen. 0 < Wert \\u2264 100: Wenn der Wert steigt, sollte der Blauanteil im Bild zunehmen und der Gelbanteil abnehmen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

