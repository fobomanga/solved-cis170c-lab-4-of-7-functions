Download Link: https://assignmentchef.com/product/solved-cis170c-lab-4-of-7-functions
<br>
Lab Overview—Scenario/Summary

You will code, build, and execute a program that simulates a coin toss and a dice roll.

Learning outcomes:

<ol>

 <li>Write functions using parameters.</li>

 <li>Be able to debug a program with syntax and logic errors.</li>

 <li>Be able to use the debug step-into feature to step through the logic of the program and to see how the variables change values.</li>

</ol>

<strong> </strong>Preparation:

If you are using the Citrix remote lab, follow the login instructions located in the lab area in Course Home.

Locate the Visual Studio icon, and launch the application.




<table width="673">

 <tbody>

  <tr>

   <td width="673"><strong>Step 1: </strong>Requirements: <strong>Coin Toss and Dice Rolling program</strong></td>

  </tr>

  <tr>

   <td width="673">Write a program that simulates flipping a coin and rolling a dice. A user will input their choice of flipping a coin (C), rolling a dice (D), or exiting (E). If the user chooses a coin toss, the program will ask how many times the coin should be tossed, and then will simulate tossing the coin that many times and print the result to the user. If the user chooses rolling a die, the program will ask how many sides the die has and how many times it should be rolled.  The program will then simulate rolling a die (with the number of sides specified) that many times. The program will continue until the user presses E.  <strong>This should be a lot of fun!</strong><strong>Here are some great things to think about as you begin your program! </strong> You will need two functions. A string flipCoin() and a int rollDice(int) function<strong>. </strong>These functions will generate a random number. For the coin flip, the random number should be in the range of 1 to 2. If the number is 1, the function should return <em>heads.</em> If the random number is 2, the function should return <em>tails.</em> For the roll dice function, the random number should be in the range of 1 to the number of sides. The function should return the result of the die roll.Important notes: You will want to seed your random number generator. To do this at the beginning of your program #include &lt;ctime&gt;.Use the following commands to seed the random number generator.//Get the system time to use it to seed the random number generatorunsigned seed = time(0); //seed the random number generatorsrand(seed); To get a random number between 1 and 2, use the following code: int toss = 1 + rand() % 2;. <strong>Sample Output from the Program</strong> Welcome to the random value generator!Would you like to flip a coin (C), roll a die (D), or exit (E)? CHow many times do you want to flip the coin? 5Flip 1 : tailsFlip 2 : headsFlip 3 : headsFlip 4 : headsFlip 5 : tailsWould you like to flip a coin (C), roll a die (D), Exit (E)? DHow many sides does your die have? 6How many times do you want to roll the die? 5Roll 1 : 5Roll 2 : 3Roll 3 : 2Roll 4 : 2Roll 5 : 2Would you like to flip a coin (C), roll a die (D), or exit (E)? DHow many sides does your die have? 20How many times do you want to roll the die? 3Roll 1 : 19Roll 2 : 16Roll 3 : 15Would you like to flip a coin (C), roll a die (D), or exit (E)? EThanks for playing!Press any key to continue.<strong> </strong></td>

  </tr>

  <tr>

   <td width="673"><strong>Step 2: </strong>Processing Logic</td>

  </tr>

  <tr>

   <td width="673">Using the pseudocode below, write the code that will meet the requirements.Main FunctionDeclare the number of tosses, number of sides, and user choice.Seed the random number generator. while user choice !=EAsk the user if they want to flip a coin, roll a die, or exit.If the choice is CAsk the user how many times to flip the coin.For i=1 to number of flips Step 1Call flipCoin()Print resultIf the choice is DAsk the user how many sides the die has.Ask the user how many times to roll the die.For i=1 to number of rolls Step 1Call rollDice()Print resultElseDisplay the closing message.  flipCoin FunctionGenerate an integer random number between 1 and 2.If a 1 is generated return heads, else return tails.rollDice FunctionGenerate a random number between 1 and the number of sides.Return the result of the roll. </td>

  </tr>

  <tr>

   <td width="673"><strong>Step 3: </strong>Create a New Project</td>

  </tr>

  <tr>

   <td width="673">Create a new project and name it LAB4. Write your code using the processing logic in Step 2 (above). Make sure that you save your program.</td>

  </tr>

  <tr>

   <td width="673"><strong>Step 4: </strong>Compile and Execute</td>

  </tr>

  <tr>

   <td width="673">a)      Compile your program. Eliminate all the syntax errors. b)      Build your program, and verify the results of the program. Make corrections to the program logic, if necessary, until the results of the program execution are what you expect. </td>

  </tr>

  <tr>

   <td width="673"><strong>Step 5: </strong>Print Screenshots and Program</td>

  </tr>

  <tr>

   <td width="673"> 1.      Capture a screen print of your output (do a print screen and paste into an MS Word document).2.      Copy your code and paste it into the same MS Word document that contains the screen print of your output.3.      Save the Word document as Lab04_LastName_FirstInitial.  </td>

  </tr>

  <tr>

   <td width="673"><strong>END OF LAB</strong></td>

  </tr>

 </tbody>

</table>

<strong> </strong>