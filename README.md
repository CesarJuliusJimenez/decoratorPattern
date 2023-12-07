# Problem
CIMB is a digital bank that offers GSave and UpSave savings accounts.   As with a typical Savings Account, it contains accountNumber, accountName, and a balance for that account.

The typical savings account offers an interest rate of 1%.
The benefits of the typical savings account is the same with the "Standard Savings Account" as compared to other banks.

The GSave account offers an interest rate of 2.5%.
Benefits include the "Standard Savings Account" plus access to "GCash transfer".

The UpSave account offers the highest interest rate of 4.0%.
Benefits include the "Standard Savings Account" plus "with Insurance".
Develop a decorator pattern approach that will implement the given UML diagram:

The content of your Cimb.java should <b>ONLY</b> contain the following codes with the exception of inserting your own package name:

![image](https://github.com/CesarJuliusJimenez/decoratorPattern/assets/116608904/c20b5d5c-f1e6-45f5-a20d-55d3476797e9)

You should display the following output:

![image](https://github.com/CesarJuliusJimenez/decoratorPattern/assets/116608904/0fb2695c-8935-4a59-bbe0-e859e0248fae)

Description of the following methods
<pre>
1. <b> showAccountType()</b> - Either returns "Savings Account", "GSave" or "UpSave"
2. <b> getInterestRate()</b> - Either returns 1% for Savings Account; 2.5% for GSave; 4.0% UpSave
3. <b> getBalance()</b> - Returns the balance of the account set.
4. <b> showBenefits()</b> - Either returns "Standard Savings Account" for Savings Account; 
                      benefits offered by savings account + "GSave Transfer";
                      benefits offered by savings account + "With Insurance";
5. <b> computeBalanceWithInterest()</b> - returns new balance by computing the balance plus the interest depending on the interest rate.
6. <b> showInfo()</b> - Returns details of account number, account name, and balance.
</pre>
<b> BankAcountDecorator </b> must be an interface.

Follow instructions. <b> You are not allowed to insert other methods except what is stated in the diagram </b>(setters and getters are allowed).


# Class Diagram
![Assigment 1 (8)](https://github.com/CesarJuliusJimenez/decoratorPattern/assets/116608904/f3ed3ef7-be47-4dd6-86a7-777f6f397ac9)
