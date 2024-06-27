
**Overview**

The `ErrorHandling` contract demonstrates the use of three different error handling methods in Solidity: `require`, `revert`, and `assert`. These methods are used to enforce certain conditions and ensure that the contract's state remains valid.

**Contract Details**

The contract contains three functions, each implementing a different error handling method to check if the given age is greater than 21, which is the required age to apply for the UPSC exam.

**Functions**

1. **`UPSC_Require`**
   - Uses the `require` statement to check if the age is greater than 21.
   - If the condition is not met, the transaction is reverted with the message: "Age greater than 21 required to apply for UPSC".

2. **`UPSC_Revert`**
   - Uses the `revert` statement to check if the age is greater than 21.
   - If the condition is not met, the transaction is explicitly reverted with the message: "Age less than 21, cannot apply for UPSC".

3. **`UPSC_Assert`**
   - Uses the `assert` statement to check if the age is greater than 21.
   - If the condition is not met, the transaction is reverted, consuming all remaining gas.
