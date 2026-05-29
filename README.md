# BillingSystem

BillingSystem is a simple Java desktop billing application built with Swing. It provides a point-of-sale style UI that lets users select common items, calculate delivery and tax, and display a final invoice total.

## Features

- Java Swing graphical user interface
- Item selection for:
	- Fruits (50 Tk)
	- Veges (100 Tk)
	- Biscuits (30 Tk)
	- Pizza (200 Tk)
	- Water Pot (15 Tk)
- Automatic cost calculation for:
	- Total item cost
	- Delivery charge (5% of item total)
	- Mileage cost
	- CGST and SGST (9% each)
	- Subtotal, tax, and grand total
- Built-in calculator panel for additional quick calculations

## Project Structure

- `src/billingsystem/BillingSystem.java` — application entry point
- `src/billingsystem/Billing_System.java` — main Swing form and billing logic
- `nbproject/` — NetBeans project metadata

## Requirements

- Java JDK 8 or later

## Run Locally

### Option 1: Run from NetBeans

1. Open the project folder in NetBeans.
2. Run the project using the IDE's Run command.

### Option 2: Run from the command line

Open PowerShell in `d:\c\BillingSystem` and execute:

```powershell
javac -d build/classes src/billingsystem/*.java
java -cp build/classes billingsystem.BillingSystem
```

## Notes

- This project uses only standard Java Swing APIs and does not require external dependencies.
- If the GUI window is too large, adjust the display resolution or modify the frame size in `src/billingsystem/Billing_System.java`.

## License

This project is provided as-is for learning and demonstration purposes.
