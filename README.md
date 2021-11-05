# Vyakya-Task

# Task 1:
Parse the given list and provide in a format expected as output. Input and
Output data can be downloaded from the link provided below.
1. Perform validations on date and amount columns
2. Identify Phone numbers and email id in the list
3. Find max amount and min amount in the output
4. Identify Deposits transaction list and withdrawals transaction list
separately and all withdrawals should have negative indication.


# Task 2:
Process the provided data to arrive at an analysis based on rule sets provided.
Input data is provided in the form of Excel with 3 sheets.
Sheet 1: Conflicting Roles
This sheet represents the rule set, where if any user with the ‘Base Role’ had
any access to the ‘Conflicting Role’ then such user is said to have an
‘Unauthorized Access’
Sheet 2: Access Listing validation
This sheet consists of the user list with their department and access roles.
Sheet 3: Invoices
This sheet consists of Invoices posted by various users from sheet 2. 
1. Filter Invoices in Sheet 3 if User is not found in Sheet 2.
2. Compute if user has Unauthorised access using the rule set in sheet 1
and user access details in sheet 2.
3. Compute and filter all invoices posted by unauthorised users in sheet 3
4. Against the Unauthorised access – specify Conflicting rule id (If more
than one rule is violated, specify a comma separated rule id)

## Output:
List of invoices with new columns “Authorised Yes/No”, “Conflicting rules”,
“Department” to be provided in the form of Excel.
