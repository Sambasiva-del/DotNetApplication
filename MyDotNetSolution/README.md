# MyDotNetSolution

This is a .NET solution containing a main project and a test project.

## Project Structure

```
MyDotNetSolution
├── MyDotNetSolution.sln
├── src
│   └── MyDotNetProject
│       ├── MyDotNetProject.csproj
│       └── Program.cs
├── tests
│   └── MyDotNetProject.Tests
│       ├── MyDotNetProject.Tests.csproj
│       └── UnitTest1.cs
└── README.md
```

## Getting Started

To get started with this project, follow the instructions below.

### Prerequisites

- .NET SDK installed on your machine.

### Building the Project

1. Navigate to the project directory:
   ```
   cd src/MyDotNetProject
   ```

2. Build the project using the following command:
   ```
   dotnet build
   ```

### Running the Application

To run the application, use the following command:
```
dotnet run
```

### Running Tests

To run the tests, navigate to the test project directory:
```
cd ../tests/MyDotNetProject.Tests
```

Then execute the following command:
```
dotnet test
```

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.