# Pokémon Storage System - An Educational Game

![Pokémon Logo](https://static.vecteezy.com/system/resources/previews/027/127/571/non_2x/pokemon-logo-pokemon-icon-transparent-free-png.png) =150x150  <!-- Pokémon Logo -->

## Overview:
The **Pokémon Storage System** is a console-based application that simulates a **Pokémon storage system**, allowing users to manage their Pokémon by depositing and withdrawing them into storage boxes. This project applies **Object-Oriented Programming (OOP)** principles and connects to **SDG 12: Responsible Consumption and Production**, promoting sustainable practices, responsible resource management, and waste reduction through an engaging Pokémon-themed interface.

---

## OOP Principles Applied:
This project demonstrates several key **Object-Oriented Programming (OOP)** principles:

### 1. **Encapsulation**:
   - The **`Pokemon`** class encapsulates attributes such as the name, types, level, and held item of a Pokémon. Methods in this class (getters and setters) allow for controlled access to these attributes, ensuring the integrity of the data.
   - The **`PokemonStorage`** class encapsulates the functionality for managing the Pokémon storage system, including organizing Pokémon into boxes.

### 2. **Inheritance**:
   - The **`Pokemon`** class serves as a base class for different types of Pokémon. It allows future extensions where different Pokémon types could inherit from this base class, each with unique behaviors (if needed).

### 3. **Polymorphism**:
   - Polymorphism is demonstrated in this system with the **`SpecialPokemon`** class, which extends the base **`Pokemon`** class. The `toString` method is overridden in the **`SpecialPokemon`** subclass to include a **special ability** attribute, which allows for different behaviors depending on the actual object type.
   - For example, when printing out the Pokémon details, the system will display the specific information based on whether the Pokémon is of a general type or a special type with additional attributes.

### 4. **Abstraction**:
   - The **`Pokemon`** class is abstract, providing a blueprint for specific Pokémon types. This allows for simplified and generalized Pokémon storage and management, which could be expanded upon for more complex systems.

---

## SDG Integration: SDG 12 - Responsible Consumption and Production
This project is aligned with **SDG 12: Responsible Consumption and Production**, which focuses on **sustainable resource management** and **minimizing waste**. The **Pokémon Storage System** encourages players to manage their Pokémon efficiently, limiting the number of Pokémon that can be stored in a box at once and ensuring no overuse of space. This mirrors the real-world concept of **managing finite resources** in a sustainable and responsible manner.

Key ways this project integrates SDG 12:
- **Resource Management**: Just as businesses and organizations must carefully manage their resources, the system enforces **limits on storage capacity**, ensuring that players cannot exceed the storage limits of the system. This reflects the idea of **using resources efficiently** and avoiding overconsumption.
  
- **Waste Minimization**: The system encourages players to make thoughtful decisions about what Pokémon to store or withdraw, promoting **minimal waste** in managing resources. This concept reflects the global push for **reducing waste** and optimizing the use of available assets.

- **Educational Value for Children**: This game can serve as an educational tool for children, teaching them the importance of **sorting, managing, and reducing waste** in an engaging way. By interacting with the Pokémon world, children learn how to make efficient use of space and resources, applying these lessons to real-world challenges such as organizing their belongings and understanding the importance of sustainable resource use.

---

## Instructions for Running the Program:
### What the Program Does:
The **Pokémon Storage System** allows players to manage their Pokémon through a **virtual Pokémon PC system**. The game is organized into three main actions: **Depositing Pokémon**, **Withdrawing Pokémon**, and **Managing Items**.

![Pokéball Icon](https://pngimg.com/uploads/pokeball/pokeball_PNG29.png)  =50x50 <!-- Pokéball Icon -->

- **View Pokémon Storage**: Displays the current contents of the Pokémon boxes (up to 2 Pokémon per box).
  
- **Deposit Pokémon**: Allows the user to deposit a Pokémon from their party into one of the boxes. The system ensures the boxes do not exceed the set capacity (2 Pokémon per box).

- **Withdraw Pokémon**: Lets the user withdraw a Pokémon from the box and add it back to the party. The system ensures that the party size does not exceed 6 Pokémon.

- **Deposit Item**: Users can assign an item to a Pokémon in the party and transfer it to a Pokémon in the storage boxes, swapping held items between the Pokémon.

- **Withdraw Item**: Lets the user withdraw an item from a Pokémon in the storage box. The item can then be assigned to a Pokémon in the party or discarded.

After performing these actions, the user can **exit the system** or return to the main menu to continue managing their Pokémon and items.

### Steps to Run the Program:
1. **Clone the repository**:
   Clone the project repository to your local machine using Git:

2. **Compile the program**:
Open your terminal/command prompt and navigate to the project directory. Use the following command to compile the program:

3. **Run the program**:
After compilation, run the program with:

4. **Interact with the system**:
- The program will prompt you to input the number of Pokémon in your party.
- After that, you can perform actions such as depositing and withdrawing Pokémon and items into/from the Pokémon PC system.
- You can navigate through the menu using the number options provided and follow the prompts to manage your Pokémon storage.

---

## How the Game Works:
- **Managing Pokémon**: You can store up to 2 Pokémon per box (with 3 boxes in total). The game prevents you from exceeding this capacity, encouraging you to think critically about space management.
- **Depositing and Withdrawing Pokémon**: You can deposit and withdraw Pokémon from your party into the storage system while maintaining balance and organization.
- **Item Management**: Items can be assigned to Pokémon, and the game allows swapping items between Pokémon in your party and storage, emphasizing efficient resource use.

![Pokémon Storage Boxes](https://pa1.narvii.com/6201/fac18f22f6333faa69d85712e83266dedaa504f0_hq.gif)  =100x100 <!-- Pokémon Storage Animation -->

---
