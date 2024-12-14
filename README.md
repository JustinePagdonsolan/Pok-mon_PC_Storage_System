# Pokémon Storage System - An Educational Game

<p align="center">
   <img src="https://static.vecteezy.com/system/resources/previews/027/127/571/non_2x/pokemon-logo-pokemon-icon-transparent-free-png.png" width="500" height="500"> <!-- Pokémon Logo -->

## Overview:
The **Pokémon Storage System** is a console-based application that simulates a **Pokémon storage system**, allowing users to manage their Pokémon by depositing and withdrawing them into storage boxes. This project applies **Object-Oriented Programming (OOP)** principles and connects to **SDG 12: Responsible Consumption and Production**, promoting sustainable practices, responsible resource management, and waste reduction through an engaging Pokémon-themed interface.

---

## OOP Principles Applied:
This project demonstrates several key **Object-Oriented Programming (OOP)** principles:

| **Principle**     | **Explanation**                                                                                                                                 |
|-------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| **Encapsulation** | The **`Pokemon`** class encapsulates attributes such as name, types, level, and held items, while using methods (getters and setters) to control access. |
| **Inheritance**   | The **`Pokemon`** class serves as a base for other Pokémon types, allowing for easy extension and customization for more specific behaviors.          |
| **Polymorphism**  | Polymorphism is demonstrated in this system with the **`SpecialPokemon`** class, which extends the base **`Pokemon`** class. The `toString` method is overridden in the **`SpecialPokemon`** subclass to include a **special ability** attribute, which allows for different behaviors depending on the actual object type. |
| **Abstraction**   | The **`Pokemon`** class is abstract, providing a blueprint for creating different types of Pokémon, focusing on their storage and management.         |

<p align="center">
   <img src= "https://poketouch.files.wordpress.com/2019/05/eevee_sparkles_gif.gif">

## SDG Integration: SDG 12 - Responsible Consumption and Production
This project is aligned with **SDG 12: Responsible Consumption and Production**, which focuses on **sustainable resource management** and **minimizing waste**. The **Pokémon Storage System** encourages players to manage their Pokémon efficiently, limiting the number of Pokémon that can be stored in a box at once and ensuring no overuse of space. This mirrors the real-world concept of **managing finite resources** in a sustainable and responsible manner.

### Key ways this project integrates SDG 12:
| **SDG Concept**            | **Project Application**                                                                 |
|----------------------------|-----------------------------------------------------------------------------------------|
| **Resource Management**    | Just as businesses must manage resources, the system enforces **limits on storage capacity**, ensuring that players cannot exceed the set capacity of the boxes. |
| **Waste Minimization**     | The system encourages players to make thoughtful decisions about what Pokémon to store or withdraw, minimizing waste by using storage efficiently.     |
| **Educational Value**      | The game helps children understand **sorting, managing, and reducing waste** in a fun and engaging way, teaching important life skills on sustainability and resource management. |

---

## Instructions for Running the Program:

### What the Program Does:
The **Pokémon Storage System** allows players to manage their Pokémon through a **virtual Pokémon PC system**. The game is organized into three main actions: **Depositing Pokémon**, **Withdrawing Pokémon**, and **Managing Items**.

<p align="center">
   <img src="https://pngimg.com/uploads/pokeball/pokeball_PNG29.png" width="250" height="250">  <!-- Pokéball Icon -->

| **Action**                | **Description**                                                                                           |
|---------------------------|-----------------------------------------------------------------------------------------------------------|
| **View Pokémon Storage**  | Displays the current contents of the Pokémon boxes (up to 2 Pokémon per box).                              |
| **Deposit Pokémon**       | Allows the user to deposit a Pokémon from their party into one of the boxes, with a capacity of 2 Pokémon per box. |
| **Withdraw Pokémon**      | Lets the user withdraw a Pokémon from the box and add it back to the party, with a maximum of 6 Pokémon in the party. |
| **Deposit Item**          | Users can assign an item to a Pokémon in the party and transfer it to a Pokémon in the storage boxes.      |
| **Withdraw Item**         | Lets the user withdraw an item from a Pokémon in the storage box. The item can then be assigned to a Pokémon in the party or discarded. |
| **Exit**                  | Exits the program after a prompt confirming exit.                                                         |

---

### Interaction with the program:
**Interaction with the system begins**:
Upon starting the program, the user will interact with the system through a series of menus and prompts. Below are the possible scenarios and outcomes based on user input and decisions.

User Input: Number of Pokémon in the Party

Scenario: The program will ask how many Pokémon the user has in their party (from 1 to 6).
Possible Outcome:
If the input is between 1 and 6, the program continues, and the user is prompted to enter details for each Pokémon.
If the input is outside this range (e.g., 0, 7, or a non-numeric value), the user is prompted to "try again" until a valid number is entered.
User Input: Pokémon Details (Name, Types, Level, Held Item)

Scenario: For each Pokémon, the user will provide the name, type(s), level, and held item.
Possible Outcomes:
If valid types are entered (e.g., "fire", "water"), and the level is within the valid range (1-100), the Pokémon is successfully added to the party.
If the types entered are invalid (e.g., "dragonfly"), the system will ask the user to try again.
If the level is out of range or non-numeric, the program will prompt the user to enter a valid level.
If the user selects that the Pokémon is holding an item, the program will prompt for a valid item name (no numbers or special characters allowed).
If the Pokémon is not holding an item, the program will assign "None" to the held item.
Main Menu: Options for Interactions

Scenario: Once the party is initialized, the main menu will be displayed, offering the following options:
View Pokémon Storage
Deposit Pokémon
Withdraw Pokémon
Deposit Item
Withdraw Item
Exit PC
Option 1: View Pokémon Storage

Scenario: The user chooses to view the contents of the storage.
Possible Outcome:
The system displays the current contents of the 3 storage boxes (each box can hold up to 2 Pokémon).
If a box is empty, it will display "No Pokémon in this box."
If there are Pokémon in the box, their details (name, level, types, held item) will be shown.
Option 2: Deposit Pokémon

Scenario: The user decides to deposit a Pokémon from their party into one of the storage boxes.
Possible Outcomes:
The system will display a list of Pokémon in the user's party.
The user selects which Pokémon to deposit (if the party size is 2 or more).
The system will ask which box to deposit the selected Pokémon into (1-3).
If a box is full (i.e., already has 2 Pokémon), the program will prompt the user to select another box or go back to the menu.
The Pokémon will be added to the selected box, and the program will confirm the deposit.
If the user selects "Go Back", the program will return to the main menu.
Option 3: Withdraw Pokémon

Scenario: The user chooses to withdraw a Pokémon from one of the storage boxes and add it back to their party.
Possible Outcomes:
The system will prompt the user to choose a box (1-3).
If the box is empty, the program will notify the user and prompt them to choose another box or go back.
If there are Pokémon in the selected box, the user can choose which Pokémon to withdraw.
If the party already has 6 Pokémon, the system will not allow the user to withdraw any more Pokémon.
After successful withdrawal, the selected Pokémon will be added to the party, and the program will confirm the withdrawal.
If the user selects "Go Back", the program will return to the box selection.
Option 4: Deposit Item

Scenario: The user chooses to deposit an item to a Pokémon.
Possible Outcomes:
The user is prompted to select a Pokémon from their party that is holding an item.
Then, the user is asked to choose a Pokémon in the storage box to assign the item to.
If the selected Pokémon in the box is holding an item, the system will ask if the user wants to swap the items or not.
The items will either be swapped or the item will be assigned to the selected Pokémon, depending on the user's choice.
If the user selects "Go Back", the program will return to the main menu.
Option 5: Withdraw Item

Scenario: The user chooses to withdraw an item from a Pokémon in one of the storage boxes.
Possible Outcomes:
The user is prompted to select a box (1-3).
If the box is empty, the program will notify the user and prompt them to choose another box or go back.
If the box contains Pokémon, the user selects which Pokémon's item to withdraw.
If the selected Pokémon is not holding an item, the program will notify the user.
Once the item is withdrawn, the system will ask the user where to place the item:
Option 1: Assign the item to a Pokémon in the party (swapping items if the Pokémon is already holding something).
Option 2: Discard the item.
The system will confirm the action taken (item swapped or discarded).
If the user selects "Go Back", the program will return to the main menu.
Option 6: Exit PC

Scenario: The user decides to exit the program.
Possible Outcome:
The program will display a message saying "Thank you for using the Pokémon PC! Have a great adventure, Trainer!"
The program will exit, and the user will be returned to their terminal or command prompt.
Special Pokémon Interaction (Polymorphism)

Scenario: The user interacts with SpecialPokemon objects, which are subclasses of the base Pokemon class.
Possible Outcomes:
When a SpecialPokemon is created, it includes a special ability attribute that is unique to that Pokémon.
Polymorphism: The toString method is overridden in SpecialPokemon to display the special ability along with the usual Pokémon details (name, level, types, and held item).
If the user views or interacts with a SpecialPokemon, the system will print the special ability in the details, showcasing polymorphism and how it behaves differently for SpecialPokemon instances compared to regular Pokemon objects.
---

## How the Game Works:

| **Feature**               | **Description**                                                                 |
|---------------------------|---------------------------------------------------------------------------------|
| **Managing Pokémon**      | You can store up to 2 Pokémon per box (with 3 boxes in total). The game prevents you from exceeding this capacity, encouraging critical thinking about space management. |
| **Depositing & Withdrawing Pokémon** | You can deposit and withdraw Pokémon from your party into the storage system while maintaining balance and organization. |
| **Item Management**       | Items can be assigned to Pokémon, and the game allows swapping items between Pokémon in your party and storage, emphasizing efficient resource use. |

<p align="center">
   <img src="https://pa1.narvii.com/6201/fac18f22f6333faa69d85712e83266dedaa504f0_hq.gif">  <!-- Pokémon Storage Animation -->

---

## Special Pokémon and Special Abilities:
In addition to basic Pokémon management, the system also demonstrates the use of **polymorphism** with the **`SpecialPokemon`** class. 

- **`SpecialPokemon`** is a subclass that extends the base **`Pokemon`** class.
- It introduces a unique attribute, the **special ability**, which can represent various special powers a Pokémon might possess (e.g., "Fire Blast", "Thunder Shock").
- The **`toString`** method is overridden in **`SpecialPokemon`** to display the special ability of each Pokémon, differentiating it from regular Pokémon. This allows for different behaviors based on the specific Pokémon type.

For example:
- A **`SpecialPokemon`** with a special ability will show the ability in the output, making it clear that this Pokémon is unique compared to regular ones in the system.

---
