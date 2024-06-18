# MonkeyFinder

MonkeyFinder is a .NET MAUI application that helps users find information about different types of monkeys.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Components](#components)
  - [App.xaml](#appxaml)
  - [App.xaml.cs](#appxamlcs)
  - [AppShell.xaml](#appshellxaml)
  - [AppShell.xaml.cs](#appshellxamlcs)
  - [GlobalUsings.cs](#globalusingscs)
  - [MauiProgram.cs](#mauiprogramcs)
  - [Monkey.cs](#monkeycs)
  - [MonkeyService.cs](#monkeyservicecs)
  - [DetailsPage.xaml](#detailspagexaml)
  - [DetailsPage.xaml.cs](#detailspagexamlcs)
  - [MainPage.xaml](#mainpagexaml)
  - [MainPage.xaml.cs](#mainpagexamlcs)
  - [BaseViewModel.cs](#baseviewmodelcs)
  - [MonkeyDetailsViewModel.cs](#monkeydetailsviewmodelcs)
  - [MonkeysViewModel.cs](#monkeysviewmodelcs)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/MonkeyFinder.git
    ```
2. Navigate to the project directory:
    ```bash
    cd MonkeyFinder
    ```
3. Restore the necessary packages:
    ```bash
    dotnet restore
    ```
4. Build the project:
    ```bash
    dotnet build
    ```

## Usage

1. Run the application:
    ```bash
    dotnet run
    ```
2. Follow the instructions in the app to find information about different types of monkeys.

## Project Structure

```plaintext
MonkeyFinder/
├── .gitignore
├── App.xaml
├── App.xaml.cs
├── AppShell.xaml
├── AppShell.xaml.cs
├── BaseViewModel.cs
├── DetailsPage.xaml
├── DetailsPage.xaml.cs
├── GlobalUsings.cs
├── MainPage.xaml
├── MainPage.xaml.cs
├── MauiProgram.cs
├── Monkey.cs
├── MonkeyDetailsViewModel.cs
├── MonkeyFinder.csproj
├── MonkeyFinder.sln
├── MonkeysViewModel.cs
├── MonkeyService.cs
└── README.md
```
## Components

### App.xaml
The `App.xaml` file defines the root resources and styles for the application.

### App.xaml.cs
The `App.xaml.cs` file contains the code-behind logic for the `App.xaml` file. It initializes the application and sets up the main page.

### AppShell.xaml
The `AppShell.xaml` file defines the visual structure of the application using Shell. It sets up the routes and navigation structure.

### AppShell.xaml.cs
The `AppShell.xaml.cs` file contains the code-behind logic for the `AppShell.xaml` file.

### GlobalUsings.cs
The `GlobalUsings.cs` file includes global using directives to simplify the inclusion of namespaces throughout the project.

### MauiProgram.cs
The `MauiProgram.cs` file sets up the MAUI application, configuring services and the app builder.

### Monkey.cs
The `Monkey.cs` file defines the model for a Monkey, including properties such as name, location, details, and image URL.

### MonkeyService.cs
The `MonkeyService.cs` file contains the logic to fetch monkey data, potentially from a web service or local database.

### DetailsPage.xaml
The `DetailsPage.xaml` file defines the UI for displaying detailed information about a selected monkey.

### DetailsPage.xaml.cs
The `DetailsPage.xaml.cs` file contains the code-behind logic for the `DetailsPage.xaml` file, handling user interactions and data binding.

### MainPage.xaml
The `MainPage.xaml` file defines the UI for the main page of the application, where users can browse through the list of monkeys.

### MainPage.xaml.cs
The `MainPage.xaml.cs` file contains the code-behind logic for the `MainPage.xaml` file, managing the main page's user interactions and data binding.

### BaseViewModel.cs
The `BaseViewModel.cs` file provides a base class for view models in the MVVM pattern, implementing common functionalities like property change notifications.

### MonkeyDetailsViewModel.cs
The `MonkeyDetailsViewModel.cs` file defines the view model for the `DetailsPage.xaml`, managing the data and commands related to a specific monkey's details.

### MonkeysViewModel.cs
The `MonkeysViewModel.cs` file defines the view model for the `MainPage.xaml`, managing the list of monkeys and related commands.
