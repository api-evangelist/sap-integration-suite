---
title: "Using WS_DELIVERY_UPDATE_2 in a Loop"
url: "https://community.sap.com/t5/abap-forum/using-ws-delivery-update-2-in-a-loop/m-p/14405545#M964"
date: "2026-05-28"
author: "rmn1"
feed_url: "https://community.sap.com/khhcw49343/rss/Community?interaction.style=forum"
---
Hi All, I've stumbled upon a strange behaviour when calling WS_DELIVERY_UPDATE_2 in a loop. Given 2 valid vbeln, when being executed individually both gave success response and VL33N showed an intended result. But when using it in a loop, somehow the 2nd document gave error message instead, which consists of HU of the 1st document, even though no HU is provided in the parameter.
