---
title: "Énumération DibBitCount"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging.apsbuilder.dib/dibbitcount/
---

L'énumération BitCount spécifie le nombre de bits qui définissent chaque pixel et<br/>                le nombre maximal de couleurs dans un bitmap indépendant du dispositif (DIB).

**Module:** [aspose.imaging.apsbuilder.dib](/imaging/python-net/aspose.imaging.apsbuilder.dib/)

**Full Name:** aspose.imaging.apsbuilder.dib.DibBitCount

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| BITCOUNT0 | Le nombre de bits par pixel est indéfini.<br/>                L'image DOIT être au format JPEG ou PNG.<br/>                Aucun de ces formats n'inclut de table de couleurs, donc cette valeur<br/>                indique qu'aucune table de couleurs n'est présente. Voir [JFIF] et [RFC2083]<br/>                pour plus d'informations concernant les formats de compression JPEG et PNG. |
| BITCOUNT1 | L'image est spécifiée avec deux couleurs. Chaque pixel du bitmap est<br/>                représenté par un seul bit. Si le bit est à 0, le pixel est<br/>                affiché avec la couleur de la première entrée de la table de couleurs ;<br/>                si le bit est à 1, le pixel a la couleur de la deuxième entrée de la table. |
| BITCOUNT2 | L'image est spécifiée avec un maximum de 16 couleurs.<br/>                Chaque pixel du bitmap est représenté par un index de 4 bits dans la<br/>                table de couleurs, et chaque octet contient 2 pixels. |
| BITCOUNT3 | L'image est spécifiée avec un maximum de 256 couleurs.<br/>                Chaque pixel du bitmap est représenté par un index de 8 bits dans la<br/>                table de couleurs, et chaque octet contient 1 pixel. |
| BITCOUNT4 | L'image est spécifiée avec un maximum de 2^16 couleurs.<br/>                Chaque pixel du bitmap est représenté par une valeur de 16 bits. |
| BITCOUNT5 | Le bitmap possède un maximum de 2^24 couleurs, et le champ Colors du DIB est NULL.<br/>                Chaque triplet de 3 octets dans le tableau bitmap représente les intensités relatives<br/>                du bleu, du vert et du rouge, respectivement, pour un pixel. La table de couleurs Colors<br/>                est utilisée pour optimiser les couleurs utilisées sur les appareils à palette, et DOIT contenir<br/>                le nombre d'entrées spécifié par le champ ColorUsed de l'objet BitmapInfoHeader. |
| BITCOUNT6 | Le bitmap possède un maximum de 2^24 couleurs |
