
### Suivi de Budget


Note: this file has two versions: the first does not include tight handling of user input, to show the 'core' solution; the second includes tighter handling of user input.

**User Stories**
- When I start up the application, I am given the following options:
    - Add a new entry to the budget tracker
    - Display the total account balance
    - View all previous entries
- If I choose to add a new entry, I am asked to provide:
    - A title describing the budget item
    - Whether the budget item is Income or Expense
    - The total amount of the budget item
    - The date of the transaction in "MM-DD-YYYY" string format
- If I choose to display the total account balance:
    - The program adds all income and subtracts all expense items to display the net balance
- If I choose to view all previous entries:
    - The program prints all details of all previous entries in a human readable format

**Technical Requirements**
- Stores all entries in a .csv file
- Load the previously created entries when the user initializes the application
