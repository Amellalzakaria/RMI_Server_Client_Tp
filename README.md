# RMI Server-Client Implementation for Machine and Salle Management

This repository contains the source code for a Java RMI (Remote Method Invocation) server-client implementation for managing machines and salle (room) objects. The system is designed to facilitate the management of various machine properties, such as ID, marque, price, and reference, as well as salle properties, including ID, code, and libelle.

## Overview

The system employs Java RMI to establish communication between the server and the client, allowing the client to access and manipulate data related to machines and salles. The project includes a comprehensive set of functionalities for adding, updating, deleting, and retrieving machine and salle information.

## Installation

To run the application, ensure that you have Java Development Kit (JDK) 8 or above installed on your system. Additionally, you will need to set up your Java IDE to support RMI.
1. Clone the repository using the following command:
git clone https://github.com/Amellalzakaria/RMI_Server_Client_Tp.git

3. Open the project in your preferred Java IDE.

4. Build the project to generate the necessary executable files.

5. Run the server first, and then run the client application.

## Usage

The application provides a user-friendly interface for interacting with the server. Users can perform various operations on the machine and salle objects, including:

- Adding a new machine or salle.
- Updating the information of an existing machine or salle.
- Deleting a machine or salle from the system.
- Searching for a machine by salle.

  ## Class Diagram

![diag class](https://github.com/Amellalzakaria/RMI_Server_Client_Tp/assets/118927619/19358ff8-a8c4-4646-ade8-e80c72861d90)

## Database Design

The application utilizes a MySQL database to store and manage the machine and salle information. Below is the description of the database design:

### Tables

1. `Machine` table: Stores details about each machine, including ID, marque, price, and reference.

   | Column  | Data Type  | Description              |
   |---------|------------|--------------------------|
   | id      | int        | Primary key for machine  |
   | marque  | varchar    | Brand or manufacturer    |
   | price   | float      | Price of the machine     |
   | ref     | varchar    | Reference of the machine |

2. `Salle` table: Stores details about each salle, including ID, code, and libelle.

   | Column  | Data Type  | Description              |
   |---------|------------|--------------------------|
   | id      | int        | Primary key for salle    |
   | code    | varchar    | Code of the salle        |
   | libelle | varchar    | Description of the salle |

### Database Schema

![diag2](https://github.com/Amellalzakaria/RMI_Server_Client_Tp/assets/118927619/e5fa3b5d-bd93-47d8-972e-3bde732a58d8)

## Screenshots

### Application Usage

Below are some screenshots showcasing the usage of the application:

1.Dashboard:

![image](https://github.com/Amellalzakaria/RMI_Server_Client_Tp/assets/118927619/0447ff05-d017-493c-827a-51ff991b72dc)
2. Adding a new salle:

![image](https://github.com/Amellalzakaria/RMI_Server_Client_Tp/assets/118927619/20648aee-5e95-43c1-92a9-2dc1516253ba)
3- Adding a new machine and assigning it to a salle.

![image](https://github.com/Amellalzakaria/RMI_Server_Client_Tp/assets/118927619/df0e4e97-ce72-4cee-8a64-67fc9f7aa220)
4. Delete a salle:

![66666](https://github.com/Amellalzakaria/RMI_Server_Client_Tp/assets/118927619/c22cd017-eb37-4efb-9c49-6da18827a74b)
5. Delete a machine:

![image](https://github.com/Amellalzakaria/RMI_Server_Client_Tp/assets/118927619/fb63ef91-cbcb-45e7-931a-1273c482344a)
6. Update a salle: 

![image](https://github.com/Amellalzakaria/RMI_Server_Client_Tp/assets/118927619/8a66df4e-4ba4-4c66-82e9-5b2dd6c705d2)

