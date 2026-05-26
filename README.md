# Integrating Azure OpenAI with Blazor Maps

An intelligent location discovery application built with Blazor, Azure OpenAI, and Maps. Search for any location type and discover relevant places across major cities with AI-generated insights and beautiful interactive map visualizations.

## Features

- **AI-Powered Search**: Uses Azure OpenAI to generate location data based on natural language queries
- **Interactive Maps**: Built with [Blazor Maps](https://www.syncfusion.com/blazor-components/blazor-maps) with real-time marker visualization
- **Smart Markers**: Customizable markers with context-aware tooltips and location details
- **Rich Tooltips**: Display detailed information about locations with formatted text and images
- **Multi-City Coverage**: Automatically discovers relevant places across 15 major cities
- **Real-Time Updates**: Dynamic search results that update instantly as you type

## Prerequisites

* [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or later
* [Visual Studio Code](https://code.visualstudio.com/)
* [.NET SDK 8.0](https://dotnet.microsoft.com/download/dotnet/8.0) or later

## Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/SyncfusionExamples/Integrating-Azure-OpenAI-with-Syncfusion-Maps-in-Blazor.git
cd Integrating-Azure-OpenAI-with-Syncfusion-Maps-in-Blazor
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

### Key Components

- `AISampleService` - Communicates with Azure OpenAI to generate location data 
- `Index.razor` - Displays the interactive map and search interface 
- `Index.razor.cs` - Manages search state, marker collection, and data transformation 

## Technologies Used

- **Blazor**: Server-side web framework for interactive UI
- **Azure OpenAI**: AI service for intelligent location generation
- **Syncfusion Blazor**: Professional UI components (Maps, TextBox, Spinner)
- **OpenStreetMap**: Free tile layer for map rendering
- **.NET 8.0**: Modern runtime and framework

## References

- [Blazor Maps Documentation](https://blazor.syncfusion.com/documentation/maps/getting-started-webapp)
- [Populate Data in Blazor Maps](https://blazor.syncfusion.com/documentation/maps/populate-data)
- [Azure OpenAI Documentation](https://learn.microsoft.com/en-us/azure/ai-services/openai/)

