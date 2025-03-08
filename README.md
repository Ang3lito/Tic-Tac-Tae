# Tic-Tac-Toe Game

This is a web-based Tic-Tac-Toe game developed using **ASP.NET Core 9 with MVC**. It supports multiplayer gameplay via **SignalR**, an AI opponent, and a scoreboard system.

## Features
- **Multiplayer Support** using SignalR
- **AI Opponent** for single-player mode
- **Scoreboard System** to track wins, losses, and draws
- **Responsive UI** using Bootstrap/Tailwind CSS

## Prerequisites
Ensure you have the following installed:
- [.NET SDK 9.0](https://dotnet.microsoft.com/en-us/download/dotnet/9.0)
- [Node.js (for frontend dependencies)](https://nodejs.org/)
- A modern web browser (Chrome, Firefox, Edge, etc.)
- when you open the project in visual studio 2022 Install necessary NuGet packages (Microsoft.AspNetCore.SignalR)

How to Add a NuGet Package in Visual Studio 2022

Method 1: Using NuGet Package Manager (GUI)
Open Your Project

Launch Visual Studio 2022 and open your ASP.NET Core or .NET project.
Open NuGet Package Manager

Right-click on the project (e.g., TicTacToe) in the Solution Explorer.
Select Manage NuGet Packages....
Browse and Install Packages

Go to the "Browse" tab.
Search for the package you need (e.g., Microsoft.AspNetCore.SignalR).
Click Install, then confirm the changes.
Verify Installation

Once installed, go to the "Installed" tab to check the package.
The package is now ready to use in your project.

## Getting Started

### 1. Clone the Repository (if applicable)
---------------------------------------------------------
git clone https://github.com/your-repository/Tic-Tac-Toe.git
cd Tic-Tac-Toe/TicTacToe
---------------------------------------------------------

### 2. Restore Dependencies
---------------------------------------------------------
dotnet restore
---------------------------------------------------------

### 3. Run the Application
---------------------------------------------------------
dotnet run
---------------------------------------------------------


Alternatively, you can run it in Visual Studio by opening `TicTacToe.sln` in the file and pressing **F5** or click the https/ green play button


### 4. Access the Game
Once the app is running, open your browser and navigate to:
---------------------------------------------------------
http://localhost:5000
---------------------------------------------------------



