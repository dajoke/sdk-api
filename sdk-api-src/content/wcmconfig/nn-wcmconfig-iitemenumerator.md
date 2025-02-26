---
UID: NN:wcmconfig.IItemEnumerator
title: IItemEnumerator (wcmconfig.h)
description: Enumerates the items of a collection of settings and attributes.
helpviewer_keywords: ["IItemEnumerator","IItemEnumerator interface [SMI]","IItemEnumerator interface [SMI]","described","smi.iitemenumerator","wcmconfig/IItemEnumerator"]
old-location: smi\iitemenumerator.htm
tech.root: SMI
ms.assetid: f43245f1-81d9-4b06-8f0c-d490618a99fa
ms.date: 12/05/2018
ms.keywords: IItemEnumerator, IItemEnumerator interface [SMI], IItemEnumerator interface [SMI],described, smi.iitemenumerator, wcmconfig/IItemEnumerator
req.header: wcmconfig.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: WcmConfig.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: SMIEngine.dll
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IItemEnumerator
 - wcmconfig/IItemEnumerator
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - SMIEngine.dll
api_name:
 - IItemEnumerator
---

# IItemEnumerator interface


## -description

Enumerates the items of a collection of settings and attributes.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IItemEnumerator</b> interface inherits from the <a href="/windows/desktop/api/unknwn/nn-unknwn-iunknown">IUnknown</a> interface. <b>IItemEnumerator</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -remarks

SMI and SMI collections are not thread-safe. Modifying a collection will not invalidate an enumerator. Further operations on the enumerator do not result in exceptions, and could encounter an enumerator in an inconsistent state.
