---
title: "Instruction Pointers (IPs) view - .NET memory sampling data"
description: The The IPs view for .NET memory allocation profiling data that was collected by using the sampling method lists the assembly instructions that allocated memory.
ms.date: "11/04/2016"
ms.topic: "conceptual"
helpviewer_keywords:
  - "Instruction Pointers view"
ms.assetid: 7d91cc14-e8e9-4ebb-b14f-b9f0da770508
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.technology: vs-ide-debug
monikerRange: 'vs-2017'
ms.workload:
  - "dotnet"
---
# Instruction Pointers (IPs) View - .NET memory sampling data

 [!INCLUDE [Visual Studio](~/includes/applies-to-version/vs-windows-only.md)]
The IPs view for .NET memory allocation profiling data that was collected by using the sampling method lists the assembly instructions that allocated memory during the profiling run. Columns of the view also list the size and number of allocations.

 Only exclusive values are listed.

|Column|Description|
|------------|-----------------|
|**Process ID**|The process ID (PID) of the profiling run.|
|**Process Name**|The name of the process.|
|**Module Name**|The name of the module that contains the instruction.|
|**Module Path**|The path of the module that contains the instruction.|
|**Source File**|The source file that contains the instruction.|
|**Function Name**|The name of the function.|
|**Function Line Number**|The line number of the start of this function in the source file.|
|**Function Address**|The starting address of the function.|
|**Source Line Begin**|The starting line number in the source file at which the allocation occurred.|
|**Source Line End**|The ending line number in the source file at which the allocation occurred.|
|**Source Character Begin**|The offset of the starting character in the source file line at which the allocation occurred.|
|**Source Character End**|The offset of the ending character in the source file line at which the allocation occurred.|
|**Instruction Address**|The address of the instruction.|
|**Exclusive Allocations**|The total number of objects that were created by the instruction.|
|**Exclusive Allocations %**|The percentage of all objects that were created in the profiling run that were allocated by the instruction.|
|**Exclusive Bytes**|The number of bytes of memory that were allocated in the profiling run that were allocated by the instruction.|
|**Exclusive Bytes %**|The percentage of all bytes of memory that were allocated in the profiling run that were allocated by the instruction.|

## See also
- [Instruction Pointers (IPs) View](../profiling/instruction-pointers-ips-view-sampling-data.md)
