# Blazor DataGrid — Customize Background Color for Grid Exported Excel File

A sample Blazor application demonstrating how to customize the background color of the [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) component when exporting data to Excel files.

## Overview

This repository demonstrates how to apply custom styling to a Blazor DataGrid when exporting it to an Excel file. Instead of using default colors, the sample shows how to use the `ExcelTheme` and `ExcelStyle` APIs to customize the background color of different grid elements (headers, records, and captions) in the exported Excel output.

The sample includes:

- A fully functional Blazor Server application with an interactive datagrid
- Example order data with multiple columns (Order ID, Customer Name, Order Date, and Freight)
- Toolbar button for triggering Excel export with custom styling
- Reusable code patterns for applying themes during export operations

## Features

- **Custom Excel Styling** - Apply custom background colors to headers, records, and captions during export
- **Theme Customization** - Use the `ExcelTheme` API to define consistent styling across exported documents
- **Flexible Export** - One-click toolbar button for seamless Excel export with custom styling
- **Sorting & Pagination** - Built-in sorting and pagination support to handle large datasets efficiently
- **Dynamic Data Binding** - Seamlessly bind collections to the grid with automatic updates
- **Responsive Design** - Works seamlessly across desktop, tablet, and mobile browsers

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/SyncfusionExamples/blazor-datagrid-customize-background-color-for-grid-exported-excel-file.git
cd blazor-datagrid-customize-background-color-for-grid-exported-excel-file
```

### Run with Visual Studio

1. Open the solution file using Visual Studio 2022 or later.
2. Restore the NuGet packages by rebuilding the solution.
3. Build the project to ensure there are no compilation errors.
4. Run the project.

### Run with .NET CLI

```bash
# Restore dependencies
dotnet restore

# Run the project
dotnet run
```

## References

**Documentation**: https://blazor.syncfusion.com/documentation/datagrid/excel-exporting

**Online example**: https://blazor.syncfusion.com/demos/datagrid/exporting?theme=fluent2