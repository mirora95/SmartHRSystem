# SmartHRSystem

SmartHRSystem is a cross-platform Human Resource Management System (HRMS) application. It provides HR-related functionalities—such as employee management, attendance, and more—accessible via mobile and web platforms. The solution is built using modern .NET technologies, aiming for scalability and multi-device support.

## Features

- Cross-platform: Runs on Android, iOS, Windows, MacCatalyst, and Tizen.
- Built with .NET MAUI for unified mobile/desktop experience.
- ASP.NET Core Web API backend.
- Example API endpoint at `/weatherforecast` for demonstration.

## Technologies Used

- **Languages:** C#
- **Frameworks:** .NET MAUI, ASP.NET Core
- **Platforms:** Android, iOS, Windows, MacCatalyst, Tizen
- **Libraries:** Microsoft.Extensions.Logging, Microsoft.Maui, etc.

## Getting Started

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/download)
- Visual Studio 2022+ with MAUI workload
- Platform-specific SDKs (for Android/iOS/MacCatalyst/Tizen as needed)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/mirora95/SmartHRSystem.git
   ```
2. Open the solution in Visual Studio.
3. Restore NuGet packages.
4. Set the startup project (`SmartHRSystem.Mobile` for the app, `SmartHRSystem.Api` for the API).
5. Build and run on your target platform (choose Android/iOS/Windows/MacCatalyst/Tizen).

## Usage

- Launch the app and navigate using the provided shell/page structure.
- The API is available at `/weatherforecast` endpoint for testing.
- Example mobile functionality includes a counter button for demonstration (see `MainPage.xaml.cs`).

## Contributors

- [Orasta Mirdadoeva](https://github.com/mirora95)
