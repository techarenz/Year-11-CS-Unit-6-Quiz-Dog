# Year-11-CS-Unit-6-Quiz-Dog

Ensure that you read all instructions <b>carefully</b>. Do not include any additional variables or methods that are not specified in this quiz description. Each question is worth one mark and is binary. That is, you either get 1 mark or 0 marks for each question (there are 13 questions on this quiz hence this quiz is worth 13 marks in total). The <i>only</i> application that is to be running on your computer is your <b>IDE</b> (until you are ready to submit your quiz). When you are ready to submit your quiz, please share it on <b>github</b> and ensure that all of your work has been <b>pushed</b> to your repository. Double check this by <b>confirming</b> that your <b>completed</b> classes exist in your repository on <b>github</b>. Submit the <b>link</b> to your repository on <b>Schoology</b>. 

Good luck, have fun! :)

# class Dog

1. A Dog class will have <b>four</b> instance variables. Ensure that each instance variable is declared as <b>private</b>.  
* age (int)
* name (String)
* color (String)
* owner (Owner)
2. A Dog class will have <b>one</b> constructor. 
* The constructor will have four parameters. The four parameters will be used to initialize the four instance variables.
3. A Dog class will have a <b>getter</b> method for each instance variable.
4. A Dog class will have a <b>setter</b> method for each instance variable.
5. A Dog class will have a <b>private</b> method called <b>addOneAge</b> that is parameterless and increments the age of the Dog.
6. A Dog class will have a method called <b>birthday</b> that <b>calls addOneAge</b> and <b>returns the age</b> of the Dog.
7. A Dog class will have a <b>toString</b> method that returns, for example, a String in the following format:
* "The dog is named Marlo and is 5 years old. This dog is black." (Quotations are shown to represent that this is a string. The quotations do not need to be included in the returned String.)

# class Owner

1. An Owner class will have <b>three</b> instance variables. Ensure that each instance variable is declared as <b>private</b>. 
* firstName (String)
* lastName (String)
* phoneNumber (String)
2. An Owner class will have one constructor.
* The constructor will have three parameters. The three parameters will be used to initialize the three instance variables. 
3. An Owner class will have a getter method for each instance variable.
4. An Owner class will have a setter method for each instance variable.

# class DogMaker

Inside the main method ...

1. Create an <b>Owner</b> object. The reference to this Owner object should be called <b>owner</b>. The firstName should be “John”, lastName “Wick”, phoneNumber “0800322520”.
2. Create a <b>Dog</b> object. The reference to this Dog object should be called <b>dog</b>. The Dog's name should be Jill, age 2, colour black and tan. This should be done in a <b>single</b> statement.
3. Use a <b>setter</b> method to change the Dog's name from Jill to Jessie.
4. Use a <b>getter</b> method and <b>print</b> statement to print out the age of Jessie. Print out the age only, and use the <b>println</b> method to print. Do this using a <b>single</b> statement.
5. Call the <b>birthday</b> method and store this into a variable called <b>age</b>.
6. Print out the contents of the variable called <b>age</b>. Use the <b>println</b> method to print.
7. Print out the <b>current state</b> of the Dog object. That is, print the <b>reference</b> to the Dog object. This will automatically call the toString method. 
