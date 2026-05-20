---
title: "Download BTP Subaccount Audit log recods into CSV File daily"
url: "https://community.sap.com/t5/integration-forum/download-btp-subaccount-audit-log-recods-into-csv-file-daily/m-p/14393397#M275"
date: "Mon, 11 May 2026 09:04:05 GMT"
author: "Puli_Bhuvaneswari"
feed_url: "https://community.sap.com/khhcw49343/rss/Community?interaction.style=forum"
---
Hello SAP Experts,BTP Subaccount Audit log recods I want to Create iFlow to extract auditlog records daily for BTP Subaccount in CF. iFlow should be triggered by program in S/4HANA, iFlow must call the /v2/auditlogrecords API with server-side paging for over 500 records, filter by event types (data-access, data-modification, security-events, configuration), aggregate results, convert to CSV, and enable download to local PC or email the file. JSON file format is not accepted in our organization. Has anyone implemented a similar iFlow design?
