---
title: "Shadow Credentials & WSUS Exploitation"
description: 
 Exploring and Understanding Shadow Credentials(msDS-KeyCredentialLink)& WSUS Exploitation in Active Directory.
author: Jardel
date: 2026-04-27 14:10:00 +0800
categories: [Active Directory]
tags: ["AD"]
render_with_liquid: false
pin: false
image:
  path: /commons/tree_700x400_enhanced_v2.jpg
---

# Enum
During port scan enumeration, several interesting findings were identified, which warranted further investigation. 

The target was confirmed to be a Windows Active Directory environment; therefore, initial enumeration efforts were focused on SMB and LDAP services.


![img](/commons/netexec.png)


It was observed that an SMB share named Shares was accessible using the default Guest account without a password. This finding warranted further inspection to determine whether any sensitive or interesting files were present.


![img](/commons/smb.png)



## Example


# Conclusion

