Caring Hands Management System


 Project Overview

 
The Caring Hands Management System is a Java-based application designed to manage donation drives for charitable organizations. The system allows users to create, view, cancel, and manage donation drives, add donors and beneficiaries, and disburse donations. This application promotes the efficient tracking of donations, ensuring transparency and the proper distribution of resources.

Key features of the system:

Create Donation Drives: Start a new donation drive with a specified start and end date.
Cancel Donation Drives: End an ongoing donation drive if needed.
Disburse Donations: Allocate collected donations to beneficiaries.
Manage Donors and Beneficiaries: Add, remove, and view donors and beneficiaries associated with each drive.
View Donation History: Track past disbursements and drive details.

The project utilizes key Object-Oriented Programming (OOP) principles to design a scalable and maintainable system:

Encapsulation

The CaringHandsManager class encapsulates the logic for managing drives, donors, and beneficiaries. This class contains methods for creating, updating, and deleting donation drives, as well as managing users and donations. The details of the implementation are hidden from the user interface, providing a clean and manageable structure.

Abstraction

Complex operations like adding a donor or disbursing donations are abstracted into easy-to-use methods, hiding the complexity from the user. This abstraction makes it easy to interact with the system without needing to understand the underlying logic.

Inheritance

While this code doesn't directly use inheritance for the main functionality, you could extend it to have specific classes for different types of donations or drive categories, creating a more sophisticated hierarchy.

Polymorphism is demonstrated by method overloading, where methods like printAllDrivesWithIndex() can behave differently based on input parameters (e.g., showing all drives or only past disbursements).

Details of the Chosen SDG and Its Integration into the Project
This project is designed to support the United Nations Sustainable Development Goal (SDG) of No Poverty (SDG 1), which aims to eradicate poverty in all its forms everywhere by 2030.

Integration into the Project:
Donation Drives: The system allows organizations to manage donation drives that collect resources from donors and distribute them to those in need. By enabling more efficient tracking and disbursement, the application supports efforts to help alleviate poverty.
Disbursement Transparency: By offering detailed reporting of disbursements, the system ensures that donations reach the intended beneficiaries, enhancing accountability and transparency.
In this context, the Caring Hands Management System plays a vital role in optimizing charitable actions to fight poverty, by ensuring the efficient allocation of resources and providing a transparent overview of donations and beneficiaries.

Pre-requisites:
Java Development Kit (JDK) version 8 or higher must be installed on your system. You can download it from Oracle’s official website.
Ensure that Java is properly configured on your machine by running the following command in your terminal or command prompt ( java -version)

Steps to Run the Program:
Clone the Repository: First, clone the repository to your local machine using the following command
Navigate to the Project Folder: Open a terminal or command prompt and navigate to the folder where the project is stored
Compile the Code: Use the following command to compile the Main.java file
Run the Program: After the code is compiled, run the program using the following command
Interact with the Program: The program will display a main menu with several options. You can navigate through the menu by inputting the corresponding number and performing tasks like creating drives, adding donors and beneficiaries, disbursing donations, and viewing past activities.
Exit the Program: To exit the program, simply select option 99 from the main menu.


