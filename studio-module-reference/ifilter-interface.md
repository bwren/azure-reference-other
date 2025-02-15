---
title: "IFilter interface | Microsoft Docs"
titleSuffix: "Azure Machine Learning Studio"
ms.date: 05/06/2019
ms.service: "machine-learning"
ms.subservice: "studio"
ms.topic: "reference"

author: xiaoharper
ms.author: amlstudiodocs
manager: cgronlun
---
# IFilter interface

This article describes `IFilter`, which is the interface for working with digital signal filters in Azure Machine Learning Studio.

[!INCLUDE [studio-ui-applies-label](../includes/studio-ui-applies-label.md)]

The `IFilter` interface provides methods and properties that are used to configure and interact with digital signal filters that have been defined using one of the filter modules in Studio. For more information, see [Filter](data-transformation-filter.md). 

You use the `IFilter` interface to save a filter or apply a predefined filter to data.  

+ Specify a filter to use: its type, coefficients, etc.
+ Apply the filter to input data
+ Generate a `DataTable` of data with filter results

You can interact with `IFilter` only in Studio, or in one of the supported APIs.  

## See also  
 [Module parameter types](machine-learning-module-parameter-types.md)   
 [Module data types](machine-learning-module-data-types.md)
