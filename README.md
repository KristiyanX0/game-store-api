# GameStore API

A minimal ASP.NET Core Web API built with .NET 10.

## Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0)
- [Git](https://git-scm.com/)
- (Optional) [Visual Studio 2022](https://visualstudio.microsoft.com/) or [VS Code](https://code.visualstudio.com/) with the [C# Dev Kit](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csdevkit) extension

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/game-store-api.git
cd game-store-api
```

### 2. Restore dependencies

```bash
dotnet restore
```

### 3. Run the application

```bash
cd GameStore.Api
dotnet run
```

The API will start on `https://localhost:5001` (or `http://localhost:5000` for HTTP).

### 4. Test the API

Open your browser or use `curl`:

```bash
curl http://localhost:5000/
```

Expected response: `Hello World!`

## Project Structure

```
GameStore.slnx           # Solution file
GameStore.Api/           # Web API project
  Program.cs             # Application entry point & route definitions
  appsettings.json       # Base configuration
  appsettings.Development.json  # Development overrides
```

## Development

To run in watch mode (auto-reloads on file changes):

```bash
cd GameStore.Api
dotnet watch
```

## Build

```bash
dotnet build
```
