MAUI Banking App
 Overview

This is a cross-platform Banking Application built using .NET MAUI. The app simulates a digital banking system where users can view account details, manage transactions, and explore banking operations in an intuitive mobile and desktop-friendly interface.

This project was developed as part of my journey to learn modern cross-platform app development using .NET MAUI and C#.

 Features

User Interface:

Multi-page navigation with Shell

Responsive design for Android, Windows, and iOS

Banking Operations:

Manage Customers and Accounts

Track Transactions

Support for different Account Types (Savings, Current)

Models:

Customer, Account, Transaction, Bank

Cross-Platform Support:

Android

Windows

iOS (simulator)

 Architecture

Pattern: MVVM-ready structure for separation of concerns

Core Components:

App.xaml – App resources & styles

AppShell.xaml – Navigation shell

MainPage.xaml – Home page layout

Models/ – Strongly typed models for banking domain

Languages: C#

UI Framework: XAML with .NET MAUI controls

 Technologies Used

.NET MAUI (.NET Multi-platform App UI)

C# 12

XAML for UI design

.NET 9.0 for cross-platform compatibility

 Installation & Running

Clone the repository:

git clone https://github.com/Abdurrageem/MauiBankingApp.git
cd MauiBankingApp/MauiBankingExercise


Install dependencies:

Ensure you have .NET 9 SDK installed

Install MAUI workload:

dotnet workload install maui


Run the app:

dotnet build
dotnet maui run
