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

### Interaction with the Program:
**Interaction with the system begins**:

1. **User Input: Number of Pokémon in the Party**
    - The program will prompt the user to input the number of Pokémon in their party (from 1 to 6).
    - **Valid Input**: The user enters a valid number (1-6), and the program proceeds to prompt for details of each Pokémon.
    - **Invalid Input**: If the input is outside this range (e.g., 0, 7, or non-numeric), the program will ask the user to "try again."

2. **User Input: Pokémon Details (Name, Types, Level, Held Item)**
    - For each Pokémon, the user will provide:
      - Name
      - Type(s)
      - Level (1-100)
      - Held item (if any)
    - **Valid Input**: If valid types and levels are entered, the Pokémon is added to the party. If the Pokémon is holding an item, the user can specify it.
    - **Invalid Input**: Invalid types or out-of-range levels will prompt the user to try again.

3. **Main Menu Options**:
    The user can interact with the following options in the main menu:
    - **View Pokémon Storage**: Displays the contents of storage boxes (up to 2 Pokémon per box).
    - **Deposit Pokémon**: Allows users to deposit a Pokémon from their party to storage.
    - **Withdraw Pokémon**: Lets users withdraw Pokémon from the storage and add it back to the party.
    - **Deposit Item**: Users can assign an item to a Pokémon and transfer it to a Pokémon in the storage boxes.
    - **Withdraw Item**: Users can withdraw an item from a Pokémon in the storage and either assign it to a Pokémon in the party or discard it.
    - **Exit**: Exits the program with a message thanking the user.

4. **Special Pokémon Interaction (Polymorphism)**:
    - If the user interacts with a **`SpecialPokemon`**, the special ability will be displayed, showcasing the use of polymorphism. This is done by overriding the `toString` method to include the special ability, allowing the Pokémon to display unique information.

---
