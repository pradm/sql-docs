﻿---
title: "Comparability for IRowsetFind | Microsoft Docs"
ms.custom: ""
ms.date: "03/04/2017"
ms.prod: "sql"
ms.prod_service: "database-engine, sql-database, sql-data-warehouse, pdw"
ms.service: ""
ms.component: "native-client-ole-db-date-time"
ms.reviewer: ""
ms.suite: "sql"
ms.technology: 

ms.tgt_pltfrm: ""
ms.topic: "reference"
helpviewer_keywords: 
  - "IRowsetFind comparability [ODBC]"
ms.assetid: 7d148b56-9bbe-4e55-b31f-43f115705402
caps.latest.revision: 14
author: "MightyPen"
ms.author: "genemi"
manager: "craigg"
ms.workload: "Inactive"
monikerRange: ">= aps-pdw-2016 || = azuresqldb-current || = azure-sqldw-latest || >= sql-server-2016 || = sqlallproducts-allversions"
---
# Comparability for IRowsetFind
[!INCLUDE[appliesto-ss-asdb-asdw-pdw-md](../../includes/appliesto-ss-asdb-asdw-pdw-md.md)]
[!INCLUDE[SNAC_Deprecated](../../includes/snac-deprecated.md)]

  For date/time types only, IRowsetFind supports the following comparisons:  
  
-   LT  
  
-   LE  
  
-   EQ  
  
-   GE  
  
-   GT  
  
-   NE  
  
-   IGNORE  
  
 If any other comparison is attempted, DB_E_BADCOMPAREOP is returned. This is consistent with the OLE DB specification.  
  
## See Also  
 [Date and Time Improvements &#40;OLE DB&#41;](../../relational-databases/native-client-ole-db-date-time/date-and-time-improvements-ole-db.md)  
  
  
