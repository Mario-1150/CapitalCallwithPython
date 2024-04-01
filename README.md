# Capital Call Simulation with Python
## Overview
This Python script provides a simple simulation of a capital call porcess in the context of private equity investments. It demonstrates the concepts of object-oriented programming, specificlly focusing on inheritances and class structures.

The simulation represents a scenario where a private equity fund requries capital froma set of investors (Capital Call). Each investor contributes a certain amount of capital and the script tracks the totla contribution to determine if the capital call is successful.

## Prerequisites 
- Python 3.x <
- NumPy library

## Code Structure
The **InvestorBlock** Class serves as a base class representing an investor block and contains a method "**investordetail()**" to print out a header fro the simulation

Transaction data is summarized by an array "arr" that holds the names of the investors involved. The list "**trx**" contains the transaction numbers and the "**REQUIRED_CAPITAL**" variable is a constant set for the amount needed in the capital call

The dictionary "**cf_ledger**" maps the transaction numbers to contirbution amounts.

Our two functions "**add_value()**" and "**is_valid**" work to aggregate the contribution amounts up to a specificed transaction number and check if the total contirbutions meet the required capital.

The investor block classes (Limited Partner nlocks) are derived classes from "**InvestorBlock**" each representing a specific investor and all include a method "**initialinvestment()**" to print details of the investor's contribution.


