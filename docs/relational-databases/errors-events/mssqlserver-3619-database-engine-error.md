---
title: "MSSQLSERVER_3619 | Microsoft Docs"
ms.custom: ""
ms.date: "04/04/2017"
ms.prod: "sql-server-2016"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "database-engine"
ms.tgt_pltfrm: ""
ms.topic: "language-reference"
helpviewer_keywords: 
  - "3619 (Database Engine error)"
ms.assetid: 7d94f8d9-65ca-4fde-9c17-7b83e94a3779
caps.latest.revision: 18
author: "BYHAM"
ms.author: "rickbyh"
manager: "jhubbard"
---
# MSSQLSERVER_3619
  
## Details  
  
|||  
|-|-|  
|Product Name|SQL Server|  
|Event ID|3619|  
|Event Source|MSSQLSERVER|  
|Component|SQLEngine|  
|Symbolic Name|SYS_NOLOG|  
|Message Text|Could not write a checkpoint record in database ID %d because the log is out of space. Contact the database administrator to truncate the log or allocate more space to the database log files.|  
  
## Explanation  
The transaction log is out of disk space.  
  
## User Action  
Truncate the log to release some space, or allocate more space to the log. For more information see, "Troubleshooting a Full Transaction Log (Error 9002)" in SQL Server Books Online.  
  