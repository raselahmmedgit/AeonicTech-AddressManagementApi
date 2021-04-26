## Programming Language, Web Technologies, Frameworks and Scripts used to Build this Application.

I have build this CMS using the following:

1. ASP.NET Core 5.0
2. C#
3. Bootstrap 4
4. SQL Server
5. ASP.NET Core Identity
6. Entity Framework Core 5.0

## Installation

Download the Application files in your system and click the .sln file to open it with Visual Studio 2019 or newer version. 

You need to follow the following Steps:

## Step 1: Change connection string

Then open the `appsettings.json` file given in the root of the Application and change the connection string to your database. By default it is:

`
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=vaio;Database=AeonicTechTestApp;Trusted_Connection=True;",
    "IdentityConnection": "Server=vaio;Database=AeonicTechTestApp;Trusted_Connection=True;"
 }
}
`

Create database in Your SqlServer as AeonicTechTestApp

Run database script one by one in Application Folder Data/SqlDbScripts `Data/SqlDbScripts`

Database script `1-1-db-script.sql` and `1-2-db-script.sql`

Then run Application.

By default the Admin user will be created with the following Credentials:

`Username - admin@mail.com`
`password - Qwer!234`

## Step 2: Login to Application using Admin URL

The login URL of the Application is:

`https://localhost:11401/account/login`

Login with the following Credentials:

`Username - admin@mail.com`
`password - Qwer!234`
