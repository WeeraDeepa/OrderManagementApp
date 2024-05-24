# OrderManagementApp

Fullstack app to manage customers and orders

---

OrderManagement
C:\WS\REACT\AppReactNetGraphQL
.Net 7, Node, VsCode, Git for windows

go to C:\WS\REACT\AppReactNetGraphQL
open git bash-> git clone https://github.com/WeeraDeepa/OrderManagementApp.git

---

$ git config --global user.name "WeeraDeepa"
$ git config --global user.email deepa_punchihewa@yahoo.com

---

Structuring backend project
-vscode extentions 1.c# 2.c# Extentions 3.Material Icon Theams 4.Nuget package Manager
-create two folders 1.Frondend 2.Backend
-vs code terminal check .Net version -> dotnet --version
-check node version
-cd backend vs code -> create sln  
-dotnet -h
-dotnet new sln --name OrderManagementBackend
-create 3 projects

1.  dotnet new webapi -o API
2.  dotnet new classlib -o Infrastructure
3.  dotnet new classlib -o Core

    add three prjectes to sln -> dotnet sln add API
    dotnet sln add Infrastructure
    dotner sln add Core

    create relationships(API<-depend on Infra <- depent on <-Core
    cd API
    dotnet add reference ..//Infrastructure
    (check in API.csproj for details)
    cd ..
    cd Infrastructure
    dotnet add reference ..//Core

        				dotnet restore

        delete class1.cs and weatherforcast.cs
        				cd API
        				dotnet watch run
        				ctrl + c
        commit all(initial setup-backend)

---

.Net Core and React with GraphQL and HotChocolate. Entity Framework,
Apollo CodeGen, Docker, Material UI, Relational DB

---

---

GitHub deepa_punchihewa@yahoo

---
