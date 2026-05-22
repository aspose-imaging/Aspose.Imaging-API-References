---
title: "Énumération SampleRoundingMode"
type: docs
weight: 80
url: /fr/python-net/aspose.imaging.fileformats.jpeg/sampleroundingmode/
---

Définit une méthode de conversion d’une valeur n bits en une valeur de 8 bits.

**Module:** [aspose.imaging.fileformats.jpeg](/imaging/python-net/aspose.imaging.fileformats.jpeg/)

**Full Name:** aspose.imaging.fileformats.jpeg.SampleRoundingMode

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| EXTRAPOLER | Extrapole une valeur 8 bits pour l'adapter à n bits, où 1 &lt; n &lt; 8.<br/>            Le nombre de toutes les valeurs possibles sur 8 bits est 1 &lt;&lt; 8 = 256, de 0 à 255.<br/>            Le nombre de toutes les valeurs possibles sur n bits est 1 &lt;&lt; n, de 0 à (1 &lt;&lt; n) - 1.<br/>            La valeur n bits la plus raisonnable Vn correspondant à une valeur 8 bits V8 est égale à Vn = V8 &gt;&gt; (8 - n). |
| TRONQUER | Tronque une valeur 8 bits pour l'adapter à n bits, où 1 &lt; n &lt; 8.<br/>            Le nombre de toutes les valeurs possibles sur n bits est 1 &lt;&lt; n, de 0 à (1 &lt;&lt; n) - 1.<br/>            La valeur n bits la plus raisonnable Vn correspondant à une valeur 8 bits V8 est égale à Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |
