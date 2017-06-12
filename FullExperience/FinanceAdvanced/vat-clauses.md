---
title: "VAT Clauses"
ms.custom: na
ms.date: "03-03-2017"
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: "article"
helpviewer_keywords: 
  - "VAT, setting up clauses"
  - "VAT clauses"
  - "VAT, clauses"
  - "VAT clauses, overview"
ms.assetid: c60a10c8-7ab6-462e-b92b-ee339860c05c
caps.latest.revision: 7
ms.author: "edupont"
translation.priority.ht: 
  - "da-dk"
  - "de-at"
  - "de-ch"
  - "de-de"
  - "en-au"
  - "en-ca"
  - "en-gb"
  - "en-in"
  - "en-nz"
  - "es-es"
  - "es-mx"
  - "fi-fi"
  - "fr-be"
  - "fr-ca"
  - "fr-ch"
  - "fr-fr"
  - "is-is"
  - "it-ch"
  - "it-it"
  - "nb-no"
  - "nl-be"
  - "nl-nl"
  - "ru-ru"
  - "sv-se"
---
# VAT Clauses
VAT clauses are used to provide descriptive information about the VAT that is being reported on a sales document. The VAT clause information is displayed on a printed document alongside the VAT identifier or VAT rate.  
  
 For example, you may have specified that the VAT identifier associated with a sales line is a certain type of VAT. You can then create a VAT clause that displays information about the VAT. You set up a VAT clause in the **VAT Clauses** window. You can also provide translated VAT clause descriptions in the report. The translated text will be based on the language code of the customer. You set up the translations in the **VAT Clause Translations** window.  
  
 By default, when you specify a VAT posting group on a sales document, the VAT clause that has been associated with the VAT posting group is automatically used and copied to the sales line. If you change the VAT Product Posting group or the VAT Business Posting group on a sales line, then the VAT clause will be updated automatically to reflect the VAT clause code that is associated with the new group.  
  
 You can modify or delete a VAT clause, and your modifications will be reflected in a generated report. However, [!INCLUDE[navnow](../ApplicationDesign/includes/navnow_md.md)] does not keep a history of the change. On the report, the VAT clause descriptions are printed and displayed for all lines in the report alongside the VAT amount and the VAT base amount. If a VAT clause has not been defined for any lines on the sales document, then the whole section is omitted when the report is printed.  
  
 The following reports support the display of VAT clauses:  
  
-   Sales \- Invoice  
  
-   Sales – Credit Memo  
  
-   Service \- Invoice  
  
-   Service – Credit Memo  
  
-   Reminder  
  
-   Finance Charge Memo  
  
## See Also  
 [How to: Set Up VAT Clauses](../Finance/how-to-set-up-vat-clauses.md)