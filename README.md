# Consumer-Loan-Assistant
(Ever wonder just) How much those credit card accounts are costing you ?

# Abstract
This project will help you get a handle on consumer debt. The Consumer Loan Assistant Project you would build computes payments and loan terms given balance and interest information. We look at focus traversal among controls, how to do input validation, and the message box for user feedback.

# Overview
In this project, we will build a consumer loan assistant. You input a loan balance and yearly interest rate. You then have two options: (1) enter the desired number of payments and the loan assistant computes the monthly payment, or (2) enter the desired monthly payment and the loan assistant determines the number of payments you will make. An analysis of your loan, including total of payments and interest paid is also provided. The finished project is saved as LoanAssistant in the \HomeJava\HomeJava Projects\ project group. Start NetBeans (or your IDE). Open the specified project group. Make LoanAssistant the main project. Run the project.

<img width="370" alt="la1" src="https://user-images.githubusercontent.com/96791396/147596832-6eb65bef-f5cd-4053-b56b-0aab9b91ece0.png">

All label controls are used for title information. Two button controls are used to compute results and to start a new analysis. Two small button controls (marked with X; only one is seen at a time) control whether you compute the number of payments or the payment amount. One button exits the project. Four text field controls are used for inputs and a large text area is used to present the loan analysis results. The loan assistant appears as:

<img width="296" alt="la2" src="https://user-images.githubusercontent.com/96791396/147596971-f1e3af90-21e7-47ef-b414-957317ce2e23.png">

In this initial configuration, you enter a Loan Balance, an Interest Rate (annual rate as a percentage) and a Number of Payments value. Click Compute Monthly Payment. The payment will appear in the ‘yellow’ text field and a complete loan analysis will appear in the large text field. Here are some numbers I tried:

<img width="292" alt="la3" src="https://user-images.githubusercontent.com/96791396/147596994-41c54ff3-b1a9-4c26-b04b-a1c6345d2c06.png">

So, if I borrow $10,000 at 5.5% interest, I will pay $301.96 for three years (36 months). More specific details on exact payment amounts, including total interest paid, is shown under Loan Analysis. At this point, you can click New Loan Analysis to try some new values:

<img width="294" alt="la4" src="https://user-images.githubusercontent.com/96791396/147597016-09106bc6-bd42-488f-a82f-316fd6823d29.png">

Note the Loan Balance, Interest Rate, and Number of Payments entries remain. Only the Monthly Payment and the Loan Analysis have been cleared. This lets you try different values with minimal typing of new entries. Change any entry you like to see different results – or even change them all. Try as many combinations as you like. At some point, clear the text fields and click the button with an X next to the Number of Payments text field. You will see:

<img width="292" alt="la6" src="https://user-images.githubusercontent.com/96791396/147597052-97a54105-b440-413b-b56a-ef1108b7a77e.png">

Notice the Number of Payments box is now yellow. The button with an X has moved to the Monthly Payment text field. In this configuration, you enter a Loan Balance, an Interest Rate and a Monthly Payment. The loan assistant will determine how many payments you need to pay off the loan. Here are some numbers I tried

<img width="291" alt="la5" src="https://user-images.githubusercontent.com/96791396/147597080-1f5ab18f-acfe-4dcf-bfa9-75d8e8c1261b.png">

It will take 59 payments (the last one is smaller) to pay off this particular loan. Again, you can click New Loan Analysis to try other values and see the results. That’s all you do with the loan assistant project – there’s a lot going on behind the scenes though. The loan assistant has two modes of operation. It can compute the monthly payment, given the balance, interest and number of payments. Or, it can compute the number of payments, given the balance, interest, and payment. The text field representing the computed value is yellow. The button marked X is used to switch from one mode to the next. To exit the project, click the Exit button.
