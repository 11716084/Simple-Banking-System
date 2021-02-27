# Simple-Banking-System
Description
You have created the foundation of our banking system. Now let's take the opportunity to deposit money into an account, make transfers and close an account if necessary.
Now your menu should look like this:
1. Balance
2. Add income
3. Do transfer
4. Close account
5. Log out
0. Exit


If the user asks for Balance, you should read the balance of the account from the database and output it into the console.

Add income item should allow us to deposit money to the account.

Do transfer item should allow transferring money to another account. You should handle the following errors:
    If the user tries to transfer more money than he/she has, output: Not enough money!
    If the user tries to transfer money to the same account, output the following message: You can't transfer money to the same account!
    If the receiver's card number doesn’t pass the Luhn algorithm, you should output: Probably you made a mistake in the card number. Please try again!
    If the receiver's card number doesn’t exist, you should output: Such a card does not exist.
    If there is no error, ask the user how much money they want to transfer and make the transaction.
If the user chooses the Close account item, you should delete that account from the database.

Do not forget to commit your DB changes right after executing a query!
