# Smart-Cart-System-in-EMU-8086-Assembly-Language
It's a general or Smart cart System on an 8086 Assembly Language #COAL PROJECT
Overview

The Smart Cart System is a console-based shopping application written in x86 Assembly Language. It enables users to select products across various categories, specify quantities, and generate a bill summary. The project demonstrates the use of assembly language for implementing a functional and interactive system with features such as menu-driven navigation, input validation, and real-time computation of costs.

Features

User-Friendly Interface:

Displays a welcome message and project credits.

Color-coded display elements.

Category Selection:

Four main categories: Clothes, Shoes, Dairy, and Meat.

Product Selection:

Lists available products in each category with prices.

Allows users to select items and specify quantities.

Real-Time Billing:

Updates the total cost after each selection.

Displays the total amount before asking for the next action.

Error Handling:

Displays error messages for invalid inputs.

Bill Summary:

Provides a detailed summary of items purchased and their quantities.

Displays the final total amount.

Project Structure

The project comprises:

Main Procedure:

Manages the overall program flow, including category selection, product listing, and billing.

Macros and Procedures:

convert1: Converts numerical values to their ASCII representation for display.

quantity: Captures multi-digit numerical input for item quantities.

cc: Custom number-to-string conversion.

ask: Prompts the user for input.

error1: Displays error messages.

ClearScreenAndMoveCursor: Clears the console screen and resets the cursor.

Data Section:

Contains messages, product descriptions, and prices.

Includes variables to track quantities and total amounts.

How It Works

Initialization:

Displays the welcome message and category options.

Initializes key data variables.

Category and Product Selection:

Users select a category (Clothes, Shoes, Dairy, or Meat).

Available products within the selected category are displayed.

Users select products and specify quantities.

Billing:

The program calculates the cost based on user inputs and updates the total.

Displays the updated total amount after each product selection.

Error Handling:

If invalid input is provided, an error message is shown, and the user is prompted again.

Bill Summary:

At the end of the session, the program displays a detailed summary of all purchased items and their respective quantities.

Exit:

The program exits cleanly after displaying the final bill.
