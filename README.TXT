Project: better-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate conditional statements.
How to start this project: Create one or more TicketMachine objects.


PART III
47. I'm assuming that, if I enter the value zero as the parameter, nothing would be inserted into the balance.
     I was right, the balance doesn't change but this error message is sent: "Use a positive amount rather than: 0".

48. The error message wouldn'T appear, since the value of insertMoney can now be equal to 0. 
    I was right, no message is printed.

49. For the boolean expression, I simply interchanged the "amount" and "0" (0 > amount). 
50. It was for the diameter of the circle. It was well suited because the diameter of a circle cannot be less than 0, so if it was, the operation wouldn't work. 

52.It is possible, but nothing will be printed if you try to print a ticket without inserting any money.
53. No, because you won't be able to purchase a ticket if the amount in the balance isn't enough. Therefore, the value of the balance can never be negative.

55. saving = price * discount;
56. mean = total / count;
57. if (ticket  > budget) { 
   System.out.println("Too expensive"); 
   }
    else { 
         System.out.println("Just right");
   }
58. if (ticket  > budget) { 
   System.out.println("Too expensive. Your budget is " + budget + " cents"); 
   }
    else { 
         System.out.println("Just right");
   }
   The second one(question 58) is easier to understand because it gives you the amount you have so you can figure out how much you're missing to print a ticket.

59. Because the original one shows how much money there is left in the balance to refund (int amountToRefund; amountToRefund = balance;), while the second one (question 59.) simply clears the balance immediately. 
60. It sends the error message "unreachable statement under the "balance = 0;". Because we would lose the value in balance.
61. Instead of just "price" this constructor says "int price". The "int price" field doesn't give the price of a ticket anymore.

64. A field (private int discount), a "setDiscount" method(public void setDiscount(int amount)), and the assignment statement would be "discount = price - amount; price = discount;". There wouldn't be a need to change any other methods from the code.



