**TollGate**

**Overview:**

The TollGate smart contract is designed to manage toll collection on a blockchain platform. It provides functions to check if a vehicle has a fast tag, calculate toll fees based on the number of wheels, and handle traffic fines.

**Features:**

1. **Owner:** The contract maintains the address of the owner who has the authority to deploy and manage the contract.

2. **Fast Tag Check:** This function checks if a vehicle has a fast tag. If it does, it returns "Yes".

3. **Toll Fee Calculation:** The contract calculates toll fees based on the number of wheels of the vehicle. For vehicles with four or more wheels, the toll fee is set to 100 units. Two-wheelers are exempted from toll fees, while other vehicles are not charged.

4. **Traffic Fine Handling:** If a vehicle has incurred a traffic fine, this function handles the situation by reverting the transaction and informing that the fine amount is added to the toll fees.

**Usage:**

- Deploy the contract on a supported blockchain platform.
- Call the functions provided by the contract to perform the desired actions:
  - Use `checkFastTag` to verify if a vehicle has a fast tag.
  - Utilize `getTollFees` to calculate toll fees based on the number of wheels.
  - Invoke `checkTrafficFine` to handle traffic fines.

**License:**

This project is licensed under the MIT License, which allows for free use, modification, and distribution, subject to certain conditions. Please refer to the SPDX-License-Identifier in the contract for more details.
**Author**
Fardeen makandar 

fardeenmakandar99@gmail.com
