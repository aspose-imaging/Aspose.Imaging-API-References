---
title: DataRecoveryMode Enumeration
type: docs
weight: 8960
url: /python-net/api-reference/aspose.imaging/datarecoverymode/
---

The data recovery mode.

**Namespace:** [aspose.imaging](/imaging/python-net/api-reference/aspose.imaging/)

**Full Name:** aspose.imaging.DataRecoveryMode

**Assembly:**  Aspose.Imaging Version: 23.3.0

## **Members**
|**Member name**|**Description**|
| :- | :- |
|NONE|No data recovery is implied. Whenever the file format has some corrupted data the appropriate exception is thrown.|
|CONSISTENT_RECOVER|The consistent recovery mode tries to recover all data as long as corruption does not break the file format and allows correct further processing.|
|MAXIMAL_RECOVER|The maximal recovery mode recovers all data even if the file format has corrupted structure and further processing may yield unattended effects.|
