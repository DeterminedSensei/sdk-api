---
UID: NE:vmr9.__MIDL___MIDL_itf_vmr9_0000_0010_0001
title: VMR9Mode (vmr9.h)
description: The VMR9Mode enumeration type specifies the rendering mode of the Video Mixing Renderer 9 (VMR-9) filter.
helpviewer_keywords: ["VMR9Mode","VMR9Mode","VMR9Mode enumeration [DirectShow]","VMR9ModeEnumeration","VMR9Mode_Mask","VMR9Mode_Renderless","VMR9Mode_Windowed","VMR9Mode_Windowless","dshow.vmr9mode","enumeration [DirectShow]","vmr9/VMR9Mode","vmr9/VMR9Mode_Mask","vmr9/VMR9Mode_Renderless","vmr9/VMR9Mode_Windowed","vmr9/VMR9Mode_Windowless"]
old-location: dshow\vmr9mode.htm
tech.root: dshow
ms.assetid: 708c45e4-e92b-4fe5-900f-7cd806011f5e
ms.date: 4/26/2023
ms.keywords: VMR9Mode, VMR9Mode , VMR9Mode enumeration [DirectShow], VMR9ModeEnumeration, VMR9Mode_Mask, VMR9Mode_Renderless, VMR9Mode_Windowed, VMR9Mode_Windowless, dshow.vmr9mode, enumeration [DirectShow], vmr9/VMR9Mode, vmr9/VMR9Mode_Mask, vmr9/VMR9Mode_Renderless, vmr9/VMR9Mode_Windowed, vmr9/VMR9Mode_Windowless
req.header: vmr9.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: VMR9Mode
req.redist: 
ms.custom: 19H1
f1_keywords:
 - __MIDL___MIDL_itf_vmr9_0000_0010_0001
 - vmr9/__MIDL___MIDL_itf_vmr9_0000_0010_0001
 - VMR9Mode
 - vmr9/VMR9Mode
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - HeaderDef
api_location:
 - Vmr9.h
api_name:
 - VMR9Mode
---

# VMR9Mode enumeration


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <b>VMR9Mode</b> enumeration type specifies the rendering mode of the <a href="/windows/desktop/DirectShow/video-mixing-renderer-filter-9">Video Mixing Renderer 9</a> (VMR-9) filter.

## -enum-fields

### -field VMR9Mode_Windowed:0x1

Windowed mode.

### -field VMR9Mode_Windowless:0x2

Windowless mode.

### -field VMR9Mode_Renderless:0x4

Renderless mode.

### -field VMR9Mode_Mask:0x7

Bitwise <b>OR</b> of all above flags; not used by applications.

## -remarks

For a description of the various VMR-9 modes, see <a href="/windows/desktop/DirectShow/vmr-modes-of-operation">VMR Modes of Operation</a>.

## -see-also

<a href="/windows/desktop/DirectShow/directshow-enumerated-types">DirectShow Enumerated Types</a>



<a href="/windows/desktop/api/vmr9/nf-vmr9-ivmrfilterconfig9-getrenderingmode">IVMRFilterConfig9::GetRenderingMode</a>



<a href="/windows/desktop/api/vmr9/nf-vmr9-ivmrfilterconfig9-setrenderingmode">IVMRFilterConfig9::SetRenderingMode</a>
