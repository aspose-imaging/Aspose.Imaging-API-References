---
title: "OdMetadata"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "البيانات الوصفية للمستند المفتوح"
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.opendocument.objects/odmetadata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.opendocument.OdObject](../../com.aspose.imaging.fileformats.opendocument/odobject)
```
public class OdMetadata extends OdObject
```

البيانات الوصفية للمستند المفتوح
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [OdMetadata(OdObject parent)](#OdMetadata-com.aspose.imaging.fileformats.opendocument.OdObject-) | يقوم بإنشاء نسخة جديدة من الفئة `OdMetadata`. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getGenerator()](#getGenerator--) | يحصل أو يضبط المولد. |
| [setGenerator(String value)](#setGenerator-java.lang.String-) | يحصل أو يضبط المولد. |
| [getTitle()](#getTitle--) | يحصل أو يضبط العنوان. |
| [setTitle(String value)](#setTitle-java.lang.String-) | يحصل أو يضبط العنوان. |
| [getDescription()](#getDescription--) | يحصل أو يضبط الوصف. |
| [setDescription(String value)](#setDescription-java.lang.String-) | يحصل أو يضبط الوصف. |
| [getSubject()](#getSubject--) | يحصل أو يضبط الموضوع. |
| [setSubject(String value)](#setSubject-java.lang.String-) | يحصل أو يضبط الموضوع. |
| [getKeywords()](#getKeywords--) | يحصل أو يضبط الكلمات المفتاحية. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | يحصل أو يضبط الكلمات المفتاحية. |
| [getInitialCreator()](#getInitialCreator--) | يحصل أو يضبط المنشئ الأولي. |
| [setInitialCreator(String value)](#setInitialCreator-java.lang.String-) | يحصل أو يضبط المنشئ الأولي. |
| [getCreator()](#getCreator--) | يحصل أو يضبط المنشئ. |
| [setCreator(String value)](#setCreator-java.lang.String-) | يحصل أو يضبط المنشئ. |
| [getPrintedBy()](#getPrintedBy--) | يحصل أو يضبط المطبوع بواسطة. |
| [setPrintedBy(String value)](#setPrintedBy-java.lang.String-) | يحصل أو يضبط المطبوع بواسطة. |
| [getCreationDateTime()](#getCreationDateTime--) | يحصل أو يعيّن تاريخ ووقت الإنشاء. |
| [setCreationDateTime(String value)](#setCreationDateTime-java.lang.String-) | يحصل أو يعيّن تاريخ ووقت الإنشاء. |
| [getModificationDateTime()](#getModificationDateTime--) | يحصل أو يعيّن تاريخ ووقت التعديل. |
| [setModificationDateTime(String value)](#setModificationDateTime-java.lang.String-) | يحصل أو يعيّن تاريخ ووقت التعديل. |
| [getPrintDateTime()](#getPrintDateTime--) | يحصل أو يعيّن تاريخ ووقت الطباعة. |
| [setPrintDateTime(String value)](#setPrintDateTime-java.lang.String-) | يحصل أو يعيّن تاريخ ووقت الطباعة. |
| [getDocumentTemplate()](#getDocumentTemplate--) | يحصل أو يعيّن قالب المستند. |
| [setDocumentTemplate(String value)](#setDocumentTemplate-java.lang.String-) | يحصل أو يعيّن قالب المستند. |
| [getAutomaticReload()](#getAutomaticReload--) | يحصل أو يعيّن إعادة التحميل التلقائية. |
| [setAutomaticReload(String value)](#setAutomaticReload-java.lang.String-) | يحصل أو يعيّن إعادة التحميل التلقائية. |
| [getHyperlinkBehavior()](#getHyperlinkBehavior--) | يحصل أو يعيّن سلوك الارتباط التشعبي. |
| [setHyperlinkBehavior(String value)](#setHyperlinkBehavior-java.lang.String-) | يحصل أو يعيّن سلوك الارتباط التشعبي. |
| [getLanguage()](#getLanguage--) | يحصل أو يعيّن اللغة. |
| [setLanguage(String value)](#setLanguage-java.lang.String-) | يحصل أو يعيّن اللغة. |
| [getEditingCycles()](#getEditingCycles--) | يحصل أو يعيّن دورات التحرير. |
| [setEditingCycles(String value)](#setEditingCycles-java.lang.String-) | يحصل أو يعيّن دورات التحرير. |
| [getEditingDuration()](#getEditingDuration--) | يحصل أو يعيّن مدة التحرير. |
| [setEditingDuration(String value)](#setEditingDuration-java.lang.String-) | يحصل أو يعيّن مدة التحرير. |
| [getDocumentStatistics()](#getDocumentStatistics--) | يحصل أو يعيّن إحصائيات المستند. |
| [setDocumentStatistics(String value)](#setDocumentStatistics-java.lang.String-) | يحصل أو يعيّن إحصائيات المستند. |
### OdMetadata(OdObject parent) {#OdMetadata-com.aspose.imaging.fileformats.opendocument.OdObject-}
```
public OdMetadata(OdObject parent)
```


يقوم بإنشاء نسخة جديدة من الفئة `OdMetadata`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| parent | [OdObject](../../com.aspose.imaging.fileformats.opendocument/odobject) | الأصل. |

### getGenerator() {#getGenerator--}
```
public String getGenerator()
```


يحصل أو يضبط المولد.

**Returns:**
java.lang.String - المولد.
### setGenerator(String value) {#setGenerator-java.lang.String-}
```
public void setGenerator(String value)
```


يحصل أو يضبط المولد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | المولد. |

### getTitle() {#getTitle--}
```
public String getTitle()
```


يحصل أو يضبط العنوان.

**Returns:**
java.lang.String - العنوان.
### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


يحصل أو يضبط العنوان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | العنوان. |

### getDescription() {#getDescription--}
```
public String getDescription()
```


يحصل أو يضبط الوصف.

**Returns:**
java.lang.String - الوصف.
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


يحصل أو يضبط الوصف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | الوصف. |

### getSubject() {#getSubject--}
```
public String getSubject()
```


يحصل أو يضبط الموضوع.

**Returns:**
java.lang.String - الموضوع.
### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


يحصل أو يضبط الموضوع.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | الموضوع. |

### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


يحصل أو يضبط الكلمات المفتاحية.

**Returns:**
java.lang.String - الكلمات المفتاحية.
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


يحصل أو يضبط الكلمات المفتاحية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | الكلمات المفتاحية. |

### getInitialCreator() {#getInitialCreator--}
```
public String getInitialCreator()
```


يحصل أو يضبط المنشئ الأولي.

**Returns:**
java.lang.String - المُنشئ الأول.
### setInitialCreator(String value) {#setInitialCreator-java.lang.String-}
```
public void setInitialCreator(String value)
```


يحصل أو يضبط المنشئ الأولي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | المُنشئ الأول. |

### getCreator() {#getCreator--}
```
public String getCreator()
```


يحصل أو يضبط المنشئ.

**Returns:**
java.lang.String - المُنشئ.
### setCreator(String value) {#setCreator-java.lang.String-}
```
public void setCreator(String value)
```


يحصل أو يضبط المنشئ.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | المُنشئ. |

### getPrintedBy() {#getPrintedBy--}
```
public String getPrintedBy()
```


يحصل أو يضبط المطبوع بواسطة.

**Returns:**
java.lang.String - المطبوع بواسطة.
### setPrintedBy(String value) {#setPrintedBy-java.lang.String-}
```
public void setPrintedBy(String value)
```


يحصل أو يضبط المطبوع بواسطة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | المطبوع بواسطة. |

### getCreationDateTime() {#getCreationDateTime--}
```
public String getCreationDateTime()
```


يحصل أو يعيّن تاريخ ووقت الإنشاء.

**Returns:**
java.lang.String - تاريخ ووقت الإنشاء.
### setCreationDateTime(String value) {#setCreationDateTime-java.lang.String-}
```
public void setCreationDateTime(String value)
```


يحصل أو يعيّن تاريخ ووقت الإنشاء.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | تاريخ ووقت الإنشاء. |

### getModificationDateTime() {#getModificationDateTime--}
```
public String getModificationDateTime()
```


يحصل أو يعيّن تاريخ ووقت التعديل.

**Returns:**
java.lang.String - تاريخ ووقت التعديل.
### setModificationDateTime(String value) {#setModificationDateTime-java.lang.String-}
```
public void setModificationDateTime(String value)
```


يحصل أو يعيّن تاريخ ووقت التعديل.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | تاريخ ووقت التعديل. |

### getPrintDateTime() {#getPrintDateTime--}
```
public String getPrintDateTime()
```


يحصل أو يعيّن تاريخ ووقت الطباعة.

**Returns:**
java.lang.String - تاريخ ووقت الطباعة.
### setPrintDateTime(String value) {#setPrintDateTime-java.lang.String-}
```
public void setPrintDateTime(String value)
```


يحصل أو يعيّن تاريخ ووقت الطباعة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | تاريخ ووقت الطباعة. |

### getDocumentTemplate() {#getDocumentTemplate--}
```
public String getDocumentTemplate()
```


يحصل أو يعيّن قالب المستند.

**Returns:**
java.lang.String - قالب المستند.
### setDocumentTemplate(String value) {#setDocumentTemplate-java.lang.String-}
```
public void setDocumentTemplate(String value)
```


يحصل أو يعيّن قالب المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | قالب المستند. |

### getAutomaticReload() {#getAutomaticReload--}
```
public String getAutomaticReload()
```


يحصل أو يعيّن إعادة التحميل التلقائية.

**Returns:**
java.lang.String - إعادة التحميل التلقائية.
### setAutomaticReload(String value) {#setAutomaticReload-java.lang.String-}
```
public void setAutomaticReload(String value)
```


يحصل أو يعيّن إعادة التحميل التلقائية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | إعادة التحميل التلقائية. |

### getHyperlinkBehavior() {#getHyperlinkBehavior--}
```
public String getHyperlinkBehavior()
```


يحصل أو يعيّن سلوك الارتباط التشعبي.

**Returns:**
java.lang.String - سلوك الارتباط التشعبي.
### setHyperlinkBehavior(String value) {#setHyperlinkBehavior-java.lang.String-}
```
public void setHyperlinkBehavior(String value)
```


يحصل أو يعيّن سلوك الارتباط التشعبي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | سلوك الارتباط التشعبي. |

### getLanguage() {#getLanguage--}
```
public String getLanguage()
```


يحصل أو يعيّن اللغة.

**Returns:**
java.lang.String - اللغة.
### setLanguage(String value) {#setLanguage-java.lang.String-}
```
public void setLanguage(String value)
```


يحصل أو يعيّن اللغة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | اللغة. |

### getEditingCycles() {#getEditingCycles--}
```
public String getEditingCycles()
```


يحصل أو يعيّن دورات التحرير.

**Returns:**
java.lang.String - دورات التحرير.
### setEditingCycles(String value) {#setEditingCycles-java.lang.String-}
```
public void setEditingCycles(String value)
```


يحصل أو يعيّن دورات التحرير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | دورات التحرير. |

### getEditingDuration() {#getEditingDuration--}
```
public String getEditingDuration()
```


يحصل أو يعيّن مدة التحرير.

**Returns:**
java.lang.String - مدة التحرير.
### setEditingDuration(String value) {#setEditingDuration-java.lang.String-}
```
public void setEditingDuration(String value)
```


يحصل أو يعيّن مدة التحرير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | مدة التحرير. |

### getDocumentStatistics() {#getDocumentStatistics--}
```
public String getDocumentStatistics()
```


يحصل أو يعيّن إحصائيات المستند.

**Returns:**
java.lang.String - إحصائيات المستند.
### setDocumentStatistics(String value) {#setDocumentStatistics-java.lang.String-}
```
public void setDocumentStatistics(String value)
```


يحصل أو يعيّن إحصائيات المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | إحصائيات المستند. |

