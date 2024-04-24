# Menu App

## Description
The Menu app is a web application built using ASP.NET, C#, SQL Server, Bootstrap, and Entity Framework. It allows users to view, add, edit, and delete pizzas along with their ingredients. The app consists of a table for dishes, a bridge table to link dishes with ingredients, and a table for ingredients. Users can perform CRUD (Create, Read, Update, Delete) operations on both pizzas and ingredients.

## Features
1. **View Pizzas:** Users can view a list of pizzas along with their ingredients.
2. **Add Pizza:** Users can add a new pizza to the menu, specifying its name and ingredients.
3. **Edit Pizza:** Users can edit existing pizzas, updating their name and ingredients.
4. **Delete Pizza:** Users can delete pizzas from the menu.
5. **CRUD Operations for Ingredients:** Similar to pizzas, users can also perform CRUD operations on ingredients.

## Technologies Used
- ASP.NET
- C#
- SQL Server
- Bootstrap
- Entity Framework

## Setup Instructions
1. Clone the repository to your local machine: `git clone https://github.com/your-username/menu-app.git`
2. Open the solution file (.sln) in Visual Studio.
3. Make sure you have SQL Server installed and configured.
4. Update the connection string in the `web.config` file to point to your SQL Server database.
5. Open the Package Manager Console and run `Update-Database` command to apply the database migrations.
6. Build and run the application in Visual Studio.

## Usage
1. Navigate to the homepage of the Menu app.
2. Browse through the list of pizzas and ingredients.
