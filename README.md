# Sweet and Savory

### Latest version date 2020/08/14
### By Spencer Moody

## Description
_This app will allow a user to register for an account and create, update, delete and organize their inventory of "treats"._

## Specifications

1. **Behavior:** The user is welcomed with a splash page and given the option to register as a new user or sign into an exisiting account.
* **Input Example:** "Create Account" or "Login"
* **Output Example:** / or / 

2. **Behavior:** The user can view all Treats.
* **Input Example:** "View all Treats"
* **Output Example:** /Treats

3. **Behavior:** The user can add new Treats.
* **Input Example:** "Add a New Treat"
* **Output Example:** /Treats/Create

4. **Behavior:** The user can add a new Flavor to their Treats.
* **Input Example:** "Add new Flavor"
* **Output Example:** //

5. **Behavior:** The user can edit exisiting Treats/Flavors.
* **Input Example:** "Edit Treats" or "Edit Flavors".
* **Output Example:** ///{}

6. **Behavior:** The program will allow the user to delete Treats and Flavors.
* **Input Example:** "Delete Treats" or "Delete Flavors"
* **Output Example:** ///{}

## Setup/Installation Requirements
* .NET Core 2.2 will need to be installed, it can be found here https://dotnet.microsoft.com/download/dotnet-core/2.2
* For Mac users, download MySQL here: https://dev.mysql.com/downloads/file/?id=484914
* For Windows users, download MySQL here: https://dev.mysql.com/downloads/file/?id=484919
* Install MySQL and set the system path, more information on how to do that can be found here: https://www.learnhowtoprogram.com/c-and-net/getting-started-with-c/installing-and-configuring-mysql
* Enter the following commands to create the necessary database and tables:
* Clone the GitHub repository by running `git clone https://github.com/smoody0208/SweetSavory.Solution.git` in the terminal
* Navigate to the `SweetSavory.Solution` folder
* Navigate to the `SweetSavory` subfolder and run `dotnet restore`
* Run `dotnet build` to build
* Next run the command `dotnet ef database update` to update/create the schema.
* Then run `dotnet build` to build the application.
* The web app will now be available on `http://localhost:5000/` in your browser.

## Known Bugs and Support
No know bugs.

## Tech used

* C#
* .NET Core
* Entity Framework
* Identity
* MySQL

### License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

Copyright (c) 2020 Spencer Moody