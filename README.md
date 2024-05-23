# Soroban-Accelerated-Bootcamp-final-project
Key Changes:

1.Account Struct: Added a frozen field to the Account struct.

2.Token Struct: Now contains a HashMap to store account balances and their frozen status.

3.freeze_account and unfreeze_account Functions: Added these functions to freeze and unfreeze accounts.

4.Transfer and transfer_from Functions: Updated to check if the account is frozen before allowing a transfer.
