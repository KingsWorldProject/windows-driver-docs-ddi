---
UID: NI:sidebandaudio.IOCTL_SBAUD_GET_DEVICE_DESCRIPTOR
title: IOCTL_SBAUD_GET_DEVICE_DESCRIPTOR
author: windows-driver-content
description: 
ms.assetid: 3cbc7c1d-7540-44a7-bb02-85f0556c308d
ms.author: windowsdriverdev
ms.date: 
ms.topic: ioctl
ms.prod: windows-hardware
ms.technology: windows-devices
req.header: sidebandaudio.h
req.include-header:
req.target-type:
req.target-min-winverclnt:
req.target-min-winversvr:
req.kmdf-ver:
req.umdf-ver:
req.lib:
req.dll:
req.irql: 
req.ddi-compliance:
req.max-support:
topic_type: 
-	apiref
api_type: 
-	HeaderDef
api_location: 
-	sidebandaudio.h
api_name: 
-	IOCTL_SBAUD_GET_DEVICE_DESCRIPTOR
product: Windows
targetos: Windows
---

# IOCTL_SBAUD_GET_DEVICE_DESCRIPTOR IOCTL

### Major Code:  [IRP_MJ_DEVICE_CONTROL](https://docs.microsoft.com/en-us/windows-hardware/drivers/kernel/irp-mj-device-control)

## -description




## -ioctlparameters

### -input-buffer

<text></text>

### -input-buffer-length 

<text></text>

### -output-buffer

<text></text>

### -output-buffer-length 

<text></text>

### -in-out-buffer

<text></text>

### -inout-buffer-length 

<text></text>

### -status-block

Irp->IoStatus.Status is set to STATUS_SUCCESS if the request is successful.
Otherwise, Status to the appropriate error condition as a NTSTATUS code. 
For more information, see [NTSTATUS Values](https://docs.microsoft.com/en-us/windows-hardware/drivers/kernel/ntstatus-values).

## -remarks

## -see-also