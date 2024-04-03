# FuzzyLogic---Error-Mitigation
##Components:
1. Input Variables:
   - Data Redundancy
   - Degradation Level
   - Error History
     
2. Output Variable:
   - Error Mitigation Action
     
3. Membership Functions:
   - Each input and output variable has linguistic terms associated with it, such as 'low', 'medium', and 'high', with corresponding triangular membership 
     functions.
4. Fuzzy Rules:
   - Three fuzzy rules are defined based on combinations of input variables to map to appropriate output actions.

5. Defuzzification:
    - The control system aggregates the rules and computes a crisp output value representing the error mitigation action.
    
6. User Interface:
   - The script prompts the user to input values for data redundancy, degradation level, and error history.
   - It then computes and displays the error mitigation action based on the provided inputs.
     
7. Test Cases:
   - The script also includes a set of sample test cases to demonstrate how the system behaves with different input combinations.
