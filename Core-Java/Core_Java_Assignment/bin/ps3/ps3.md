# Abstract Class and Interface
## Problem Statement 3:
#### Solve following sub problems,
3.1 Create an abstract class Instrument which is having the abstract function play. Create three more sub classes from Instrument which is Piano, Flute, Guitar. Override the play method inside all three classes printing a message as follows,
“Piano is playing tan tan tan tan” for Piano class
“Flute is playing toot toot toot toot” for Flute class“Guitar is playing tin tin tin”  for Guitar class
Note: You must not allow the user to declare an object of Instrument class.
- Create an array of 10 Instruments.
- Assign different type of instrument-to-Instrument reference.
- Check for the polymorphic behavior of play method.
- Use the instanceofoperator to print that which object stored at which index of instrument array.
3.2 Create an interface MedicineInfo to represent a drug manufactured by a pharmaceutical company. Provide  an  abstract method displayLabel()  in  this interface to  print  Name  and  address of  the company.
Do following tasks,
- Implement MedicineInfo interface with Tablet, Syrup and Ointment classes.
- Override the displayLabel() method in each of these classes to print information suitable to the type of medicine. For example, in case of tablets, it could be “store in a cool dry place”, in case of ointments it could be “for external use only” etc.
Create a class TestMedicine . Write main function to do the following:
- Declare an array of Medicine references of size 10.
- Create a medicine object of the type as decided by a randomly generated integer in the range 1 to 3. (Refer Java API Documentation to find out random generation feature.
- Check the polymorphic  behavior of the displayLabel() method.