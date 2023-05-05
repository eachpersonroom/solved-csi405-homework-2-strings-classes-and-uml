Download Link: https://assignmentchef.com/product/solved-csi405-homework-2-strings-classes-and-uml
<br>
<h1>Part 1: The Stock class</h1>

Design a class named Stock that contains the following:

<ol>

 <li>A Symbol enum field named <strong>symbol </strong>for the stock’s symbol</li>

 <li>A double data field name previousClosingPrice that stores the stock price for the previous day</li>

 <li>A double data field named currentPrice that stores the stock price for the current time</li>

 <li>A constructor that creates a stock with specified <strong>symbol</strong> and name</li>

 <li>The accessor functions for all data fields</li>

 <li>The mutator functions for previousClosingPrice and currentPrice</li>

 <li>A function named getChangePercent() that returns the percentage changed from previousClosingPrice to currentPrice</li>

 <li>The Enum “Symbol” – will be used to denote stock for companies

  <ol>

   <li>Declare the stock symbols for the following: Microsoft, Apple, Google, Amazon, AT&amp;T</li>

   <li>The symbol should have a string value which is the company name</li>

   <li>Example Symbol.MSFT represents Microsoft stock.</li>

  </ol></li>

</ol>

Draw the UML diagram(s). Implement the classes. Write a test program that creates a Stock object with the stock symbol MSFT and the previous closing stock price of 58.9. Set a new current price to 59 and display the price change percentage. Repeat for one other company.

<h1>Part 2: Morse code generator</h1>

Morse code is a code where each letter of the English alphabet, each digit, and various punctuation characters are represented by a series of dots and dashes. Figure 1 shows part of the code. Write a program that asks the user to enter a string and then converts that string into Morse code. Use hyphens for dashes and periods for dots.

Some points to consider:

<ol>

 <li>Design: Figure out what classes and methods you need to develop. Ex. Utility classes, class to represent Morse code generator, etc</li>

 <li>Architecture: Create a UML of your architecture idea. Make it re-usable and configurable by someone other than yourself</li>

 <li>The input can be given in two ways

  <ol>

   <li>Command line args</li>

   <li>Passed into a function</li>

  </ol></li>

 <li>Use string buffers when you are (or are going to) manipulating large Strings</li>

 <li>Use appropriate accessors for your variables and methods</li>

 <li><strong>EXPLAIN: What strategy you used to store the morse code encoding table and WHY? </strong><strong>. Can add it as comment on the class. </strong></li>

</ol>

<h1>Part 3: Car Instrument Simulator</h1>

For this part, you will design a set of classes that work together to simulate a car’s fuel gauge and odometer. The classes you will design are the following:

<ul>

 <li>The FuelGauge class: This class will simulate a fuel gauge. Its responsibilities are as follows:

  <ul>

   <li>To know the car’s current amount of fuel, in gallons o To report the car’s current amount of fuel in gallons</li>

   <li>To be able to increment he amount of fuel by 1 gallon. This simulates putting fuel in the car (The car can hold max 15 gallons)</li>

   <li>To be able to decrement the amount of fuel by 1 gallon, if the amount of fuel is greater than 0 gallons. This simulates burning fuel as the car runs.</li>

  </ul></li>

 <li>The Odometer class: This class will simulate the car’s odometer. Its responsibilities are as follows:

  <ul>

   <li>To know the car’s current mileage o To report the car’s current mileage</li>

   <li>To be able to increment the current mileage by 1 mile. The maximum mileage the odometer can store is 999,999 miles. When this amount is exceeded, the odometer resets the current mileage to 0</li>

   <li>To be able to work with a FuelGauge object. It should decrease the FuelGuage object’s current amount of fuel by 1 gallon for every 22 miles travelled. (The car’s fuel economy is 22 miles per gallon)</li>

  </ul></li>

</ul>

Demonstrate the classes by creating instances of each. Simulate filling the car up with fuel, and the run a loop that increments the odometer until the car runs out of fuel. During each loop iteration, print the car’s current mileage and amount of fuel.

<ul>

 <li>Each part should have its code files in its respective package mentioned above</li>

 <li>The homework should be submitted as 1 eclipse project zipped</li>

 <li>UML diagrams can be submitted separately from the project zip file (but in the same submission on blackboard)</li>

 <li>Deadlines mentioned on blackboard are final. ONLY consider those deadlines</li>

 <li>You only need to use what has been taught to date in the class to solve this homework. Do not over-think it</li>

</ul>

You will be graded based on the understanding of your concepts and the implementation