---

title: Dimension priority and dimension context for resolution
description: For each pricing dimension, it is now possible to assign a priority by cost, purchase, sales, or other context defined by the system administrator.
author: MargoC
manager: AnnBe
ms.date: 06/01/2018
ms.assetid: f77a28ed-2758-42e1-8672-ba8b39062b0d
ms.topic: article
ms.prod: 
ms.service: business-applications
ms.technology: 
ms.author: margoc
audience: Admin

---
#  Dimension priority and dimension context for resolution 


[!include[banner](../../includes/banner.md)]

For each pricing dimension, it is now possible to assign a priority by cost,
purchase, sales, or other context defined by the system administrator. The
pricing API runs recursively to match input dimensions to price setup in order
of dimension priority, defaulting to zero only in a no-match scenario.
