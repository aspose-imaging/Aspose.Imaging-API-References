---
title: "Énumération EmfGraphicsMode"
type: docs
weight: 150
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---

L'énumération GraphicsMode est utilisée pour spécifier comment interpréter les données de forme telles que les coordonnées de rectangle.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfGraphicsMode

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| GM_ADVANCED | La sortie de texte TrueType DOIT être entièrement conforme à la transformation monde-vers-appareil actuelle dans le contexte du dispositif de lecture.<br/> Les arcs DOIVENT être tracés dans le sens antihoraire dans l'espace monde ; cependant, les points de contrôle des arcs <br/> ainsi que les arcs eux‑mêmes DOIVENT pleinement respecter la transformation monde‑vers‑appareil actuelle dans le contexte du dispositif de lecture.<br/> La transformation monde‑vers‑appareil PEUT être modifiée directement en utilisant les enregistrements EMR_MODIFYWORLDTRANSFORM ou <br/> EMR_SETWORLDTRANSFORM, ou indirectement en modifiant les étendues et origines de la fenêtre et du viewport, <br/> en utilisant les enregistrements EMR_SETWINDOWEXTEX (section 2.3.11.30) et EMR_SETVIEWPORTEXTEX (section 2.3.11.28), <br/> ainsi que les enregistrements EMR_SETWINDOWORGEX (section 2.3.11.31) et EMR_SETVIEWPORTORGEX (section 2.3.11.30), respectivement.<br/> En mode graphique GM_ADVANCED, les bords inférieur et droit DOIVENT être inclus lors du tracé des rectangles. |
| GM_COMPATIBLE | Le texte TrueType DOIT être écrit de gauche à droite et à l'endroit, même si le reste des graphiques <br/> est tourné autour de l'axe x ou de l'axe y en raison de la transformation monde‑vers‑appareil actuelle dans <br/> le contexte du dispositif de lecture. Seule la hauteur du texte DOIT être mise à l'échelle. Les arcs DOIVENT être tracés en utilisant la direction d'arc actuelle dans le contexte du dispositif de lecture, mais ils NE DOIVENT PAS respecter la transformation monde‑vers‑appareil actuelle, qui pourrait nécessiter une rotation autour de l'axe x ou y.<br/> La transformation monde‑vers‑appareil DOIT uniquement être modifiée en changeant les étendues et origines de la fenêtre et du viewport, <br/> en utilisant les enregistrements EMR_SETWINDOWEXTEX (section 2.3.11.30) et EMR_SETVIEWPORTEXTEX <br/> (section 2.3.11.28), ainsi que les enregistrements EMR_SETWINDOWORGEX (section 2.3.11.31) et EMR_SETVIEWPORTORGEX <br/> (section 2.3.11.30), respectivement. Modifier directement la transformation en utilisant les <br/> enregistrements EMR_MODIFYWORLDTRANSFORM (section 2.3.12.1) ou EMR_SETWORLDTRANSFORM (section 2.3.12.2) PEUT NE PAS être pris en charge.<br/> En mode graphique GM_COMPATIBLE, les bords inférieur et droit DOIVENT être exclus lors du tracé des rectangles. |
