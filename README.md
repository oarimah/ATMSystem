# atmSystem
atm system used to calculate transfer deposit and withdrawal operations 

Withdrawal
• If the client is a student and…
o If the transaction is performed during the weekend, then there is no fee
o Otherwise, the fee is 0.1% of the amount withdrawn.
• If the client is not a student and…
o If the balance of the account is less than $1,000, then the fee is 0.2% of the amount
withdrawn.
o If, however, the balance is $1,000, or more, but less than $10,000, the fee is 0.1% of the
amount withdrawn.
o If the balance is more than $10,000, then there is no fee.
Deposit
• If the client is a student and…
o If the amount withdrawn is more than $100 and…
 If the balance of the account is more than $1,000, then the fee is 1% of the
amount withdrawn.
 Otherwise, the fee is 0.5% of the amount withdrawn.
o If, however, the amount withdrawn is $100 or less and…
 If the balance of the account is more than $5,000, then the fee is 0.5% of the
amount withdrawn.
 Otherwise, there is no fee.
• If the client is not a student and…
o If the amount withdrawn is more than $500 and…
 If the balance of the account is more than $5,000, then the fee is 1% of the
amount withdrawn.
 Otherwise, the fee is 0.5% of the amount withdrawn.
o If, however, the amount withdrawn is $500 or less and…
 If the balance of the account is more than $10,000, then the fee is 0.5% of the
amount withdrawn.
 Otherwise, there is no fee.
Transfer
• If the client is a student and…
o If the amount withdrawn is less than $100 and…
 If the balance of the account the money is coming from is less than $1,000 and…
• If the balance of the account the money is going to is less than $1,000,
then the fee is 0.1% of the amount withdrawn.
• Otherwise, the fee is 0.05% of the amount withdrawn.
 If, however, the balance of the account the money is coming from is $1,000, or
more and…
• If the balance of the account the money is going to is less than $1,000,
then the fee is 0.5% of the amount withdrawn.
• Otherwise, the fee is 0.25% of the amount withdrawn.
o If the amount withdrawn is $100, or more, and…
 If the balance of the account the money is coming from is less than $1,000 and…
• If the balance of the account the money is going to is less than $1,000,
then the fee is 0.05% of the amount withdrawn.
• Otherwise, the fee is 0.025% of the amount withdrawn.
 If, however, the balance of the account the money is coming from is $1,000, or
more and…
• If the balance of the account the money is going to is less than $1,000,
then the fee is 0.25% of the amount withdrawn.
• Otherwise, the fee is 0.125% of the amount withdrawn.
• If the client is a not student and…
o If the amount withdrawn is less than $100 and…
 If the balance of the account the money is coming from is less than $1,000 and…
• If the balance of the account the money is going to is less than $1,000,
then the fee is 0.2% of the amount withdrawn.
• Otherwise, the fee is 0.1% of the amount withdrawn.
 If, however, the balance of the account the money is coming from is $1,000, or
more and…
• If the balance of the account the money is going to is less than $1,000,
then the fee is 1% of the amount withdrawn.
• Otherwise, the fee is 0.5% of the amount withdrawn.
o If the amount withdrawn is $100, or more, and…
 If the balance of the account the money is coming from is less than $1,000 and…
• If the balance of the account the money is going to is less than $1,000,
then the fee is 0.1% of the amount withdrawn.
• Otherwise, the fee is 0.05% of the amount withdrawn.
 If, however, the balance of the account the money is coming from is $1,000, or
more and…
• If the balance of the account the money is going to is less than $1,000,
then the fee is 0.5% of the amount withdrawn.
• Otherwise, the fee is 0.25% of the amount withdrawn.

Note: The above calculation of the fees for the Deposit, Withdrawal and Transfer operations are in the
FeesCalculator class in the bank.utils package. 

