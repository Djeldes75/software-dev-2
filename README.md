# Software Development 2 · Sales and Purchasing System

![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)
![Course](https://img.shields.io/badge/INTEC-coursework-3E9A86?style=flat)

Final project for **Desarrollo de Software 2**: a sales and purchasing system (*Sistema de Compra y Venta*)
with categories, products, customers and suppliers, users and roles, purchases and sales, built on SQL Server
stored procedures.

## Database

The [`Database`](Database) folder has the scripts, in the order to run them:

| # | Script |
|---|---|
| 1 | Create the tables |
| 2 | Connection class (`Conexion.cs`) |
| 3 – 4 | Categories |
| 5 | Products (artículos) |
| 6 | Roles and users |
| 7 | People: customers and suppliers |
| 8 | Purchases (ingresos) and stock updates |
| 9 | Sales, stock updates and cancellations |

## Application

The full Visual Studio solution is in `! DominiqueJeldes_ProyectoFinal - SistemalLab2.7z` (open it with 7-Zip).

## How to run

1. Run the scripts in `Database` in order on **SQL Server**.
2. Extract the `.7z`, open the `.sln` in **Visual Studio 2022** and set the server in `Conexion.cs`.
3. Press **F5**.

## About

Coursework by **Dominique Jeldes** for the Systems Engineering program at
[INTEC](https://www.intec.edu.do/) (Instituto Tecnológico de Santo Domingo), Dominican Republic.
Educational code: some projects are exercises or work in progress.
