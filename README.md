# KidsLibrary – Educational Stories for Children

A website featuring educational stories for children with a progress path, developed using **ASP.NET Core MVC**.

## Overview

KidsLibrary is an interactive web platform that offers children a collection of educational stories in a safe, engaging environment. A built-in **progress path** lets children move through the stories step by step, making learning structured, motivating, and easy to track.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | ASP.NET Core MVC |
| Language | C# |
| Frontend | Razor Views, HTML, CSS, JavaScript |
| Data Access | Entity Framework Core |
| IDE | Visual Studio |

> Update this table with the exact .NET version, database, and libraries used.

## Project Structure

```
KidsLibrary/
├── Program.cs            # Application entry point and configuration
├── appsettings.json      # Application settings
├── KidsLibrary.csproj    # Project file
└── KidsLibrary.sln       # Visual Studio solution
```

## Key Features

- Collection of educational stories for children
- Progress path to track a child's advancement through the stories
- Child-friendly, easy-to-navigate interface
- Built with the MVC pattern for clean separation of concerns

> Edit this list to match the features you implemented (user accounts, story categories, quizzes, rewards, etc.).

## Getting Started

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download)
- [Visual Studio](https://visualstudio.microsoft.com/) (optional)
- A database server, if the project uses one

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/WalaaMohammedObaid/KidsLibrary.git
   cd KidsLibrary
   ```

2. **Configure the application**

   Update the connection string and any settings in `appsettings.json`.

3. **Apply database migrations** (if applicable)
   ```bash
   dotnet ef database update
   ```

4. **Run the application**
   ```bash
   dotnet run
   ```

5. Open the URL shown in the terminal in your browser.

## Author

**Walaa Mohammed Obaid**
GitHub: [@WalaaMohammedObaid](https://github.com/WalaaMohammedObaid)
