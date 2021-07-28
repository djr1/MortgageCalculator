# MortgageCalculator

Many believe that one of the best investments that anyone can make is buying a house. Houses in general will appreciate and the interest on the loan is tax deductible. Unfortunately, most of us become so mind boggled when presented with all of the paperwork for buying a house that we really don't understand much of what went on (trust me on this). For this problem, I want to concentrate on the mortgage loan.

Before you go out looking at houses, you need to have a price range in mind. That price range is based on how much the monthly payment is going to be. A monthly payment consists of principal, interest, taxes, and insurance (PITI). The principal is a portion of the actual loan that is being paid back. The interest is what you are paying as interest on the remainder of the loan each month. Taxes refer to property taxes and insurance is self-explanatory. The majority of the monthly payment is made up of (PI) which is principal and interest.

In order to figure out how much house we can buy, we need to know what the monthly payment is going to be. To figure out the monthly payment, we must do a what-if analysis. That is, for instance, what-if we are looking at a $450,000.00 house. Further, we must do a what-if on the interest rate. As an example, presently the interest rate is somewhere in the range of 3% (fixed for the life of the loan). 

Here is the formula for finding the monthly payment for any loan:

P = L[m(1 + m)<sup>n</sup>]/[(1 + m)<sup>n</sup> - 1], where <p></p>

L is the loan amount in dollars<p></p>
m is the monthly interest rate (the yearly interest rate will be entered as example, 6.0, 
	meaning 6%, so m would need to be .06 / 12 or .005 for the above formula to work)<p></p>
n is the number of months the loan is for<p></p>

You are to write a complete Java program fully documented that allows the user the ability to enter a loan amount in dollars (e.g. 300000.00), a yearly interest rate (e.g. 3.5), and a number of years the loan is for (e.g. 30). You must then calculate the monthly payment that will be paid each month for the duration of the loan and the total interest paid on the loan over that same period of time.<p></p>

Here is exactly what your program is to output (asterisks and all), and user input is in bold:<p></p>

<pre>
*******************
Mortgage Calculator
*******************

Enter Loan Amount: $<b>100000.00</b>
Enter Interest Rate: %<b>3.5</b>
Enter Number Of Years: <b>30</b>

Monthly Mortgage Payment: $449.0446878088234
Total Interest Paid: $61656.08761117642

</pre>

<b>Note1:</b> Each inputted value is to be > 0.0. If an inputted value is entered incorrectly, output the message “Incorrect Input – Terminating Program” Here is an example. You are to terminate the program immediately when an illegal input occurs. <p></p>

<pre>
*******************
Mortgage Calculator
*******************

Enter Loan Amount: $<b>100000.00</b>
Enter Interest Rate: %<b>-1.0</b>
Incorrect Input - Terminating Program
</pre>
  
You will need to use the pow Java method that is part of the Math class. The pow method accepts two doubles and returns a double. For instance, System.out.println (Math.pow (2.0, 3.0)); will output 8.0 to the screen since 2.0 raised to the 3.0 equals 8.0.
