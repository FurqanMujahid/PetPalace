# 🐾 PetPalace

PetPalace is a comprehensive platform built to empower pet shops by allowing them to create and manage their own websites, offering products, services, and appointment scheduling for pet owners. Built with **ASP.NET Core 8**, this project integrates e-commerce, appointment management, and a variety of pet-related services.

## 📑 Table of Contents

- [About the Project](#about-the-project)
- [Features](#features)
- [Technologies Used](#technologies-used) 
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Configuration](#configuration)
- [Usage](#usage)
  
---

## 📖 About the Project <a name="about-the-project"></a> 

PetPalace aims to connect pet shop owners and pet lovers in one place. It enables shop owners to register their shops, showcase their products and services, schedule appointments, and process payments, all while creating a smooth experience for pet owners.

### ✨ Project Motivation

The idea behind PetPalace is to make it easier for pet owners to find all the services they need in one place, while providing shop owners with a streamlined way to manage and grow their online presence.

---

## 🌟 Features <a name="features"></a>

- **Role-Based Access**: Supports roles like **Shop Owner**, **Admin**, and **User**, each with tailored access levels.
- **E-commerce**: Includes a shopping cart for products with a Stripe-integrated checkout.
- **Appointment Scheduling**: Enables users to schedule appointments with pet services.
- **Services Management**: Allows shop owners to manage offered services, and users can select and book required services.
- **Testimonials**: Users can provide feedback to build trust and encourage service improvement.
- **Pet Profiles**: Allows users to add and manage details about their pets.
- **Special Sales**: Shop owners can promote special sales on products to attract more customers.
- **Responsive Design**: Fully optimized for both desktop and mobile devices.
- **Team Members**: Allows team members and veterinarians to manage their responsibilities and schedules.

## 📸 Project Screenshots 

<table>
  <tr>
    <th>Register</th>
    <th>User Login</th>
    <th>Product</th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/d65ed01c-058f-4471-80a5-5810bd7a9771" alt="Register" width="200"></td>
    <td><img src="https://github.com/user-attachments/assets/4b2bdaf4-1880-4dba-b1f9-b959b7c7cd4f" alt="User Login" width="200"></td>
    <td><img src="https://github.com/user-attachments/assets/b26fae4a-7f78-4d47-870c-7a617b8fad56" alt="Product" width="200"></td>
  </tr>
  <tr>
    <th>Add to Cart</th>
    <th>Appointment</th>
    <th>Team Member</th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/0a1ed02b-08a4-481a-92ce-b58922cd22b5" alt="Add to cart" width="200"></td>
    <td><img src="https://github.com/user-attachments/assets/04c93f35-5a9f-4798-9e7b-18f390ff7efe" alt="Appointment" width="200"></td>
    <td><img src="https://github.com/user-attachments/assets/f6137eba-9651-4adc-ba91-8a8d4b8e5cf7" alt="Team Member" width="200"></td>
  </tr>
  <tr>
    <th>Services</th>
    <th>Special Sale</th>
    <th>Feedback Index</th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/b301d8bd-3e79-415f-8133-c1f817d4fa5b" alt ="Services" width="200"></td>
    <td><img src="https://github.com/user-attachments/assets/2e475f87-626a-4c3c-8d64-8a6eb249cd8d" alt="Special Sale" width="200"></td>
    <td><img src="https://github.com/user-attachments/assets/94699306-ea5d-4807-9841-040289edea57" alt="Feedback index" width="200"></td>
  </tr>
  <tr>
    <th>Contact</th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/10c9e3ba-e20d-4365-b8a8-5c017e4e6405" alt="Contact" width="200"></td>
  </tr>
</table>




---

## 💻 Technologies Used <a name="technologies-used"></a>

- **ASP.NET Core 8** - Backend framework
- **Entity Framework Core** - ORM for managing database operations
- **Stripe API** - Payment processing integration
- **SQL Server** - Database management system
- **DevExpress** - Advanced report generation
- **Session and Cache** - For handling shopping cart and user session data

---

## 🚀 Getting Started <a name="getting-started"></a>

### Prerequisites

Ensure you have the following installed:
- [.NET Core 8 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [SQL Server](https://www.microsoft.com/en-us/sql-server)
- [Visual Studio 2022](https://visualstudio.microsoft.com/) or later
- A [Stripe account](https://stripe.com/) for payment processing

### Installation

1. **Clone the repository**:
   git clone https://github.com/FurqanMujahid/PetPalace.git
   cd PetPalace

2. **Set up the database**:
Update the database connection string in appsettings.json to match your SQL Server configuration.

3. **Run migrations**:
dotnet ef database update

4. **Set up Stripe**:

  - Add your Stripe API keys under the Stripe section.

5. **Run the application**:
dotnet run
---
## 🔧 Configuration <a name="configuration"></a>
Ensure your appsettings.json is properly set up with:
- Database connection strings
- Stripe API keys (for payment processing)
---
## 📋 Usage <a name="usage"></a>
- Shop Owners can register, add their pet shop details, manage products, services, and schedules.
- Users can browse products, add items to the cart, schedule appointments, and complete purchases.
- Admins can monitor platform activities, manage user roles, and oversee registered shops.
