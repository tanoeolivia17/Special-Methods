# Encapsulation Smart Door System

## Project Overview
This repository contains a Python implementation of a **Smart Door Access System** for UMaT. The project focuses on demonstrating **Encapsulation** in Object-Oriented Programming (OOP) by protecting sensitive staff access codes from direct modification.

## Features
- **Public Attribute:** `s_name` for staff identification.
- **Private Attribute:** `__access_code` to ensure data privacy.
- **Encapsulated Access:** Uses the `@property` decorator to implement getter and setter logic, ensuring:
    - Validation: Access codes must meet a minimum length requirement.
    - Controlled Access: Provides an interface for viewing and updating the code securely.

## Setup
1. Clone this repository.
2. Ensure you have Python 3.x installed.
3. Run the script using `python main.py` (or your chosen filename).

## Author
Developed as part of the OOP Case Study activity for UMaT.