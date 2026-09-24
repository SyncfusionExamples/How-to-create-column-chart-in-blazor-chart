# How to Create a Column Chart in Blazor Chart

## Overview

This sample demonstrates how to create a column chart using Syncfusion [Blazor Charts](https://www.syncfusion.com/blazor-components/blazor-charts). The implementation binds a collection of business data to a chart series and renders it using the column chart visualization type.

The sample configures a category-based X-axis and maps data fields to chart points through series data binding. Column charts are commonly used to compare values across categories and provide a clear visual representation of trends and differences.

## Key Features

- Uses the `SfChart` component to render chart data.
- Configures a category axis through `ChartPrimaryXAxis`.
- Sets `ValueType="ValueType.Category"` for category-based X-axis rendering.
- Binds chart data using the `ChartSeries.DataSource` property.
- Maps category values through the `XName` property.
- Maps numeric values through the `YName` property.
- Renders a column chart using `Type="ChartSeriesType.Column"`.
- Displays chart data from a strongly typed `ChartData` collection.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone this repository.
2. Open the project file:
   - `Column.csproj`
3. Restore NuGet packages when prompted.
4. Build the project.
5. Run the application using **Ctrl+F5**.

**Visual Studio Code**

1. Clone this repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the project directory.

```bash
cd Column
dotnet restore
dotnet run
```

5. Open the local URL displayed in the terminal after the application starts.

## Project Structure

`Pages/Index.razor` - Main sample page that configures and renders the Syncfusion Blazor column chart.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Refer to the official documentation: https://help.syncfusion.com/chart-sdk/blazor/charts/getting-started

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.