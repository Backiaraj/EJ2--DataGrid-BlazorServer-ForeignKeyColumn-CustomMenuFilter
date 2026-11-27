# Blazor Server DataGrid Foreign Key Column Custom Menu Filter

## Overview

This sample demonstrates how to customize filtering behavior for a foreign key column in a Syncfusion [Blazor DataGrid](https://www.syncfusion.com/blazor-components/blazor-datagrid) by rendering a custom ComboBox component inside the Grid's menu filter interface. Rather than using the default filter UI, the sample provides a tailored filtering experience that allows users to select values from a predefined list associated with the foreign key data source. This approach is useful when foreign key values should be presented through a controlled selection experience instead of a standard filter input.

## Key Features

- Demonstrates a Syncfusion Blazor DataGrid foreign key column filtering scenario.
- Renders a custom ComboBox component inside the Grid menu filter UI.
- Uses a foreign key data source to present selectable filter values.
- Replaces the default menu filter experience with a customized component-based filter.
- Shows how Grid filtering can be integrated with a user-defined selection control.
- Includes supporting data models and sample data used by the foreign key column implementation.

## Prerequisites

* [.NET SDK 10.0](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) or later
* [Visual Studio 2026](https://visualstudio.microsoft.com/downloads/) or [Visual Studio Code](https://code.visualstudio.com/)

## How to run the project

**Visual Studio 2026**:

* Checkout this project to a location in your disk.
* Open the project (`ForeignKeyWithCustomMenuFilter.csproj`) file.
* Restore the NuGet packages.
* Run the project.

**Visual Studio Code**:

* Checkout this project to a location in your disk.
* Open the repository folder in Visual Studio Code.
* Open the integrated terminal.
* Navigate to the repository root.

```bash
cd EJ2--DataGrid-BlazorServer-ForeignKeyColumn-CustomMenuFilter
dotnet restore
dotnet run
```

Open the URL displayed in the terminal after the application starts.

## Project structure

- `Pages/` — contains the Razor page that renders the Syncfusion DataGrid and custom foreign key menu filter implementation.

## Support and feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For official documentation related to DataGrid foreign key columns, see: https://help.syncfusion.com/grid-sdk/blazor/data-grid/foreignkey-column

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
