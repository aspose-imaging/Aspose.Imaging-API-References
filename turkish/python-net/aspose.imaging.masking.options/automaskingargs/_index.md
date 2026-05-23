---
title: "AutoMaskingArgs Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.imaging.masking.options/automaskingargs/
---

**Summary:** Represents the arguments that are specified for automated masking methods

**Module:** [aspose.imaging.masking.options](/imaging/python-net/aspose.imaging.masking.options/)

**Full Name:** aspose.imaging.masking.options.AutoMaskingArgs

**Inheritance:** IMaskingArgs

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [AutoMaskingArgs()](#AutoMaskingArgs__1) | AutoMaskingArgs sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| max_iteration_number | int | r/w | İterasyonların maksimum sayısını alır veya ayarlar. |
| number_of_objects | int | r/w | Nesnelerin sayısını alır veya ayarlar<br/>            başlangıç görüntüsünü ayırmak için (isteğe bağlı), varsayılan değer 2'dir (nesne ve arka plan). |
| objects_points | [Point[][]](/imaging/python-net/aspose.imaging/point[]/) | r/w | Ayrılmış nesnelere ait noktaları alır veya ayarlar (isteğe bağlı)<br/>            NumberOfObjects koordinatları, başlangıç görüntüsündeki NumberOfObjects nesnelere aittir.<br/>            Bu parametre, segmentasyon yöntemi hassasiyetini artırmak için kullanılır. |
| objects_rectangles | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ayrılmış nesnelere ait nesne dikdörtgenlerini alır veya ayarlar (isteğe bağlı).<br/>            Bu parametre, segmentasyon yöntemi hassasiyetini artırmak için kullanılır. |
| orphaned_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Artık herhangi bir nesneye ait olmayan noktaları alır veya ayarlar (isteğe bağlı).<br/>            Bu parametre yalnızca yeniden segmentasyon durumunda kullanılır. |
| precision | float | r/w | Segmentasyon yönteminin hassasiyetini alır veya ayarlar (isteğe bağlı). |


### Constructor: AutoMaskingArgs() {#AutoMaskingArgs__1}


```
 AutoMaskingArgs() 
```

AutoMaskingArgs sınıfının yeni bir örneğini başlatır

