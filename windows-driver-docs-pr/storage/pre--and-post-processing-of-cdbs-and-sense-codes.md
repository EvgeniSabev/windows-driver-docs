---
title: Pre- and Post-Processing of CDBs and Sense Codes
author: windows-driver-content
description: Pre- and Post-Processing of CDBs and Sense Codes
ms.assetid: c2af23b6-5807-4701-956e-5a2781d2082d
ms.author: windowsdriverdev
ms.date: 04/20/2017
ms.topic: article
ms.prod: windows-hardware
ms.technology: windows-devices
---

# Pre- and Post-Processing of CDBs and Sense Codes


Storport does not validate, reject, or transform in any way the SCSI command descriptor blocks (CDBs) that pass through it. Likewise, there is also no filtering or transformation of the sense codes or other sense data that is received back from a device in response to a command that fails with Check Condition status.

 

 




