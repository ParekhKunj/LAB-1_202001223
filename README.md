# LAB-1_202001223
IT314- Lab 1 -> Identifying Functional and Non-Functional Requirements
**Q.1. Identify FRs and NFRs:**

**Functional Requirements:**

- Any user on the internet should be able to browse/search books online in LIS so LIS should provide search access to all the users on the internet.
  First we require login functionality for Users. This will help us to identify whether the user is a member of LIS or librarian or not.
  
- If the user wants to be part of this library then she/he follows some registration procedure through sign up functionality. It should also contain the procedure of     payment of membership.Our system should be able to do the transaction with any online payment mode like credit card , debit card, UPI , netbanking  etc.

- For the members of LIS they should be able to search the books and also they should be able to issue that book online for that system should show whether the        searched book is available or not.

- If the current book that the user wants to read is occupied then the user should be notified whenever the book will be returned. Also the system should queue the      book issue request based on the first come first serve basis and notify users accordingly for the availability of the book.

- When a user issues the book ,the user should be also notified about its return date. System should generate mail for the reminder of returning the book also.

- If the user forgets to return the book before the deadline and without notifying about extending the book issue time then the user should be panelized by some   charges and the amount that user has to pay should be notified and marked as having borrowed that much money in their account.

- If a user wants to borrow a book for more days than given tenure then the user should pay some additional charges for extending the return date.
Users should be reminded yearly about paying their membership fees. 

- Librarian can access all books that are borrowed and taken back so he/she can easily cross check by how many books are currently available by accessing the current number of books. Also administrators can keep track of how much amount is their in its system currently.
If a user wants some new book that is released in the market and not in LIS then User can Request administrator through help functionality. It also helps in guiding how to use the system and resolve any other issues that the user is facing.


**Non - Functional Requirements:**

- System should be able to manage all the users simultaneous access (at least 1000 people concurrent access to LIS) (performance)

- Payment of the user should be reliable and secure.(reliability and security)

- Search functionality should not take more than 5 s to provide the result .(speed)

- System should run on both mobile and desktop.(portability)

- Users should have a limit on issuing books on a monthly basis.(maintainability) 

- All the transactions that are made by users should be atomic and reliable. Means that all the changes made by any user should be reflected to the system. (atomicity)
 
- Users should be able to access the system from anywhere inside the LAN network through any device at any time. (Usability)

- Database capacity should be extended if number of users increased then their default size.

- System should have a good UI so that any user can easily access it.

- System should have copyright so that anyone can not upload  that same copyrighted book.and System administrator password should be well encrypted so that any data of the user will not be leaked. (data-integrity)


**Q.2. Identify scope, features and non-functional aspects of the following problem.**

**Scope -** 
-  This device is very useful for the people who can not hear , it helps them to recognize which kind of sound is happening around them. 

-  It will work in low-latency phones so it is accessible by many users at any time (24x7).

**Features -**
-  Based on noise around the user it should display the name of the object from which noise is coming and location of that object.

- I dangerous situation like car is near the user in that kind of situation to avoid unexpected accidents AI should take decisions automatically and turn on  flashlight so that user can identify that he/she is in danger and it should display the instructions on the mobile screen like how far it is and what should the user should do and which location is safe etc.

-  It should also assist voice requests as in some situations it is difficult to type and get answers for their queries.

-  This system should also display voice calls in message  form if the user wants to call and talk with anyone.

-  AI should be adoptable and we should also be able to add new voices so that next time the system should recognize the sound. Like the user's mother should be able to add her sound manually.

-  It should also have a login/sign up  feature of  the user and save its data so that if a user login from another device AI can still access its previous data.
   

**Non Functional - Requirement-**

-  It should not be very costly and if possible it should be free application so that every user can access it

-  It should give alert signals quickly in dangerous situations.

-  It should match the speed of the human voice while converting the voice message to text message.

-  AI should be as accurate as possible so that it can convert voice message correctly into text messages and the user will get the correct message.




 
