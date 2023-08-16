# Movie App - ASP.NET MVC

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Welcome to the Movie App, an ASP.NET MVC application that allows users to browse and search for movies. This README provides a brief overview of the app, how to set it up locally, and how to contribute to the project.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Browse a list of movies with details such as title, release year, and genre.
- Search for movies based on title or genre.
- View detailed information about a specific movie.
- User-friendly interface for easy navigation.

## Getting Started

### Prerequisites

- [.NET Core SDK](https://dotnet.microsoft.com/download) (version x.x or higher)
- [Visual Studio](https://visualstudio.microsoft.com/) or [Visual Studio Code](https://code.visualstudio.com/) (optional)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/movie-app.git
   cd movie-app
   ```

2. Build the application:

   ```bash
   dotnet build
   ```

3. Set up the database:
   
   - Update the connection string in `appsettings.json` to point to your SQL Server instance.
   - Run Entity Framework migrations to create the database schema:

     ```bash
     dotnet ef database update
     ```

4. Run the application:

   ```bash
   dotnet run
   ```

The app should now be accessible at `http://localhost:7277`.

## Usage

- Browse movies on the home page.
- Use the search bar to find movies by title or genre.
- Click on a movie to view its details.

## Contributing

Contributions are welcome and encouraged! To contribute to the project, follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`.
3. Make your changes and commit them: `git commit -m "Add your feature"`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Create a pull request detailing your changes.

Please ensure your code follows the project's coding standards and conventions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
