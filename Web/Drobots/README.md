CHALLENGE NAME: Drobots

DESCRIPTION: Pandora's latest mission as part of her reconnaissance training is to infiltrate the Drobots firm that was suspected of engaging in illegal activities. Can you help pandora with this task?
////
After machine is spawned we and connect to it, We can see that it is a login page ...

![Alt text](./loginPage.png "login page")


Now let's go to the files and navigate their contents.
There is a function called login() in the database.py file that matches the username and password in the database.
But, we can clearly see that it is vulnerable due to a basic SQLi ...

![Alt text](./loginFunction.png "login page")
