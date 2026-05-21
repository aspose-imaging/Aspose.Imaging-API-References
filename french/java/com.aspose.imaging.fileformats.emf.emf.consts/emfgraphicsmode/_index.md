---
title: "EmfGraphicsMode"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération GraphicsMode est utilisée pour spécifier comment interpréter les données de forme telles que les coordonnées de rectangle."
type: docs
weight: 24
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfGraphicsMode extends System.Enum
```

L'énumération GraphicsMode est utilisée pour spécifier comment interpréter les données de forme telles que les coordonnées de rectangle.
## Champs

| Champ | Description |
| --- | --- |
| [GM_COMPATIBLE](#GM-COMPATIBLE) | Le texte TrueType DOIT être écrit de gauche à droite et à l'endroit, même si le reste des graphiques est pivoté autour de l'axe x ou de l'axe y en raison de la transformation monde-vers-appareil actuelle dans le contexte du dispositif de lecture. |
| [GM_ADVANCED](#GM-ADVANCED) | La sortie de texte TrueType DOIT se conformer pleinement à la transformation monde-vers-appareil actuelle dans le contexte du dispositif de lecture. |
### GM_COMPATIBLE {#GM-COMPATIBLE}
```
public static final int GM_COMPATIBLE
```


Le texte TrueType DOIT être écrit de gauche à droite et à l'endroit, même si le reste des graphiques est pivoté autour de l'axe x ou de l'axe y en raison de la transformation monde-vers-appareil actuelle dans le contexte du dispositif de lecture. Seule la hauteur du texte DOIT être mise à l'échelle. Les arcs DOIVENT être dessinés en utilisant la direction d'arc actuelle dans le contexte du dispositif de lecture, mais ils NE DOIVENT PAS respecter la transformation monde-vers-appareil actuelle, ce qui pourrait nécessiter une rotation le long de l'axe x ou y. La transformation monde-vers-appareil DOIT uniquement être modifiée en changeant les étendues et origines de la fenêtre et du viewport, en utilisant les enregistrements EMR\_SETWINDOWEXTEX (section 2.3.11.30) et EMR\_SETVIEWPORTEXTEX (section 2.3.11.28), ainsi que les enregistrements EMR\_SETWINDOWORGEX (section 2.3.11.31) et EMR\_SETVIEWPORTORGEX (section 2.3.11.30), respectivement. bChanging la transformation directement en utilisant les enregistrements EMR\_MODIFYWORLDTRANSFORM (section 2.3.12.1) ou EMR\_SETWORLDTRANSFORM (section 2.3.12.2) PEUT NE PAS être pris en charge. En mode graphique GM\_COMPATIBLE, les bords inférieurs et les bords les plus à droite DOIVENT être exclus lorsque les rectangles sont dessinés

### GM_ADVANCED {#GM-ADVANCED}
```
public static final int GM_ADVANCED
```


La sortie de texte TrueType DOIT se conformer pleinement à la transformation monde-vers-appareil actuelle dans le contexte du dispositif de lecture. Les arcs DOIVENT être dessinés dans le sens antihoraire dans l'espace monde ; cependant, les points de contrôle des arcs ainsi que les arcs eux‑mêmes DOIVENT pleinement respecter la transformation monde-vers-appareil actuelle dans le contexte du dispositif de lecture. La transformation monde-vers-appareil PEUT être modifiée directement en utilisant les enregistrements EMR\_MODIFYWORLDTRANSFORM ou EMR\_SETWORLDTRANSFORM, ou indirectement en changeant les étendues et origines de la fenêtre et du viewport, en utilisant les enregistrements EMR\_SETWINDOWEXTEX (section 2.3.11.30) et EMR\_SETVIEWPORTEXTEX (section 2.3.11.28), ainsi que les enregistrements EMR\_SETWINDOWORGEX (section 2.3.11.31) et EMR\_SETVIEWPORTORGEX (section 2.3.11.30), respectivement. En mode graphique GM\_ADVANCED, les bords inférieurs et les bords les plus à droite DOIVENT être inclus lorsque les rectangles sont dessinés.

