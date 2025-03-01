# Arpit's ING Assessment

# Running the Application

To run this app:

1. Execute the following command in your terminal:
   ```
   ./mvnw spring-boot:run
   ```

# Testing the Application

To run tests:

1. Execute the following command in your terminal:
   ```
   ./mvnw test
   ```

# Explanation

The DataLoader class generates a list containing the current mortgage rates. 
The interestRate property displays the rate with three decimal places, matching the format used by the EU gov.

Note: The monthly cost calculation is the total cost by summing the total fee with the loan value and then dividing by the number of months.

# Next Steps
Create Custom Exception for the application
