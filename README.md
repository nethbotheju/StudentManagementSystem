# Student Management System

A desktop application built using C# for managing student information.

---

## Setup Instructions

### Prerequisites
1. Install the following dependencies:
   - [.NET SDK 9.0.201 (Windows x64)](https://dotnet.microsoft.com/)
   - [Windows Desktop Runtime 6.0.36 (Windows x64)](https://dotnet.microsoft.com/)

2. Verify the installation by running the following command in your terminal or command prompt:
   ```bash
   dotnet --version
   ```
   Ensure that the output matches the installed version of the .NET SDK (e.g., `9.0.201`).

---

## Running the Application

1. **Navigate to the Project Root Directory**  
   Open a terminal or command prompt and navigate to the root directory of the project.

2. **Restore Dependencies**  
   Execute the following command to restore all required NuGet packages:
   ```bash
   dotnet restore
   ```

3. **Build the Project**  
   Compile the project using the following command:
   ```bash
   dotnet build
   ```

4. **Run the Application**  
   Navigate to the `StudentManagementSystem` folder within the project directory:
   ```bash
   cd StudentManagementSystem
   ```
   Start the application by running:
   ```bash
   dotnet run
   ```