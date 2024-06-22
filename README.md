# 📃 EasyDocs

EasyDocs is a document creation and editing application, similar to Google Docs. Built using ASP.NET Core MVC.

## Getting Started

### Prerequisites

- [.NET Core SDK](https://dotnet.microsoft.com/download) version 8.0 or later
- [Visual Studio](https://visualstudio.microsoft.com/) or [Visual Studio Code](https://code.visualstudio.com/)
- A database management system (e.g., SQL Server, PostgreSQL, or MySQL)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/vascabarkapa/easy-docs.git
```

2. Navigate to the project directory:
```bash
cd easy-docs
```

3. Restore the NuGet packages:
```bash
dotnet restore
```

4. Update the database connection string in the `appsettings.json` file to match your local database setup.

5. Apply the database migrations:
```bash
dotnet ef database update
```

6. Build and run the application:
```bash
dotnet run
```

7. Open your web browser and navigate to `https://localhost:5001` to access the EasyDocs application.

## Contributing

We welcome contributions to the EasyDocs project. If you'd like to contribute, please follow these steps:

1. Fork the repository
2. Create a new branch for your feature or bug fix
3. Make your changes and ensure the code passes all tests
4. Submit a pull request with a detailed description of your changes

## License

EasyDocs is licensed under the [MIT License](LICENSE).