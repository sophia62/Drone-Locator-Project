# Drone Package Delivery System

## Overview

This is a simple C# console application that simulates a drone delivery system for BYUI. The user can add items to a cart, check out, and receive an estimated delivery time based on the package's weight and the distance to their street.

### Features
- **Menu Options**:
  1. Add items to the cart
  2. Remove items from the cart
  3. View the cart
  4. Checkout and get estimated delivery time
  5. Exit the program
- **Street Distance Calculation**: The program reads distances from a file (`streetDistances.txt`) to calculate delivery time.
  
### How to Use
1. Run the program.
2. Follow the menu to add or remove items, view your cart, or check out.
3. Enter your street name at checkout to get an estimated delivery time.

### Requirements
- **C#** with .NET 8.0
- **Text File**: `streetDistances.txt` should be in the same folder.

### How to Run
1. Clone the project.
2. Build and run with:

```bash
dotnet run
```
