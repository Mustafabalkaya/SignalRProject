https://github.com/Mustafabalkaya/SignalRProject.git


# Asp.Net Core API Order Management with SignalR and QR Codes

This project encompasses an application for order management utilizing Asp.Net Core API with SignalR through QR codes. Below, you can find the content for a `readme.md` file that you can use to professionalize your project and explain it to other developers.

## Project Description

This project is developed to facilitate order intake and management for a restaurant or similar establishment through QR codes, utilizing Asp.Net Core API with SignalR. The project includes the following features:

- Database creation and updates using migrations.
- User login and registration processes.
- Order reservation procedures.
- Real-time order updates using SignalR.
- User authentication and menu management based on roles.

## Technologies and Libraries

- **Backend:**
  - ASP.NET Core Web API
  - Entity Framework Core (Migration)
  - SignalR
  - JWT Authentication

- **Frontend:**
  - HTML, CSS, JavaScript
  - Bootstrap

- **Database:**
  - Microsoft SQL Server

## Installation

1. Clone the project repository to your computer.
    ```bash
    git clone https://github.com/Mustafabalkaya/SignalRProject.git
    ```

2. Navigate to the project directory.
    ```bash
    cd SignalRProject
    ```

3. Install the required dependencies using the following command.
    ```bash
    dotnet restore
    ```

4. Apply migrations to create and update the database.
    ```bash
    dotnet ef database update
    ```

5. Run the project.
    ```bash
    dotnet run
    ```

## Usage

1. Visit `https://localhost:7092` in your browser. --> This may differ for you
2. Register or log in.
3. Create an order using the QR code scanner.
4. The order status will be updated in real-time.

## User Authentication and Menu Control Based on Roles

The project enables menu control and authorization based on user roles.

- Admin users can perform all operations.
- Staff users can perform specific tasks such as updating order statuses.
- Standard users can view and manage their own orders.

## Contributing

1. Fork this repository.
2. Add new features or fix bugs.
3. Submit a pull request.

