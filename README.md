# bunq Beta Career Event 

Possible projects:

If "outside interactions" such as incoming or outgoing payments are required for your idea,
we can trigger those.

**Payment sorter**  
In our app, we have a so-called 'payment sorter'. This is a feature that allows you to split incoming
payments over multiple bank accounts. You can also build this feature yourself using our API!

Tips:
- Register a callback that will inform your application whenever there's an incoming payment.
- Listen for that callback and split your incoming money whichever way you like.

**Automatically request your Netflix payment to your roommates**  
If you're sharing a subscription like Netflix with friends or roommates, you can use our API
to automatically request money from them whenever you paid for the subscription.

Tips:
- Register a callback whenever there's an outgoing payment, and find a way to deduce it's one from
  your subscription.
- Create "RequestInquiry"s for your friends' share in the subscription.

**Pay a random charity at the end of the month**  
Create a program that will randomly select a charity and pay whatever percentage of your balance that's
left at the end of the month to that organization's bank account.

**Gambling bot**  
We'll provide you with an account with (almost) infinite money, you create a program that will wait
until someone's paid money into it, and return double or nothing. 

**Balance alert**  
Write a program that periodically checks your balance and then sends you an email if it drops below a 
certain threshold.
