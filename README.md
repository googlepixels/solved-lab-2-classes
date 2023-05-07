Download Link: https://assignmentchef.com/product/solved-lab-2-classes
<br>
5/5 - (1 vote)

The purpose of this assignment is give you some experience writing classes in C++, the various special functions they make use of (such as copy constructors, assignment operators, and destructors), as well as and introduction dynamically allocating memory within those classes.

DescriptionThis program will represent a hypothetical car dealership, which consists of showrooms that contain the vehicles for sale. To that end, there are three classes you will be writing:

•       Vehicle

•       Showroom

•       Dealership

For this assignment, main.cpp will be provided for you, so you don’t have to worry about the structure of the program. Instead, you can focus solely on the structure of the classes and their interactions.

VehicleThe Vehicle class is the basic container of this assignment. You will need to store the following data:

•       The make of the vehicle (such as Mazda, Toyota, etc)

•       The model of the vehicle (such as Mustang, Model S, F-150, etc)

•       The year

•       The price

•       How many miles does the vehicle have on it?

In addition to a constructor which takes in the necessary information, you will also need the following functions defined. You will also want to define a destructor, just to print out when that destructor is called (this is so you can get familiar with that concept).

ShowroomThe Showroom class is a bit more sophisticated. Its purpose is to store an array of Vehicle objects. Each Showroom that you create could have a different number of Vehicles, so you will have to use dynamic memory allocation in this case. Your Showroom should contain variables for the following:

•       The name of the Showroom

•       A pointer to the array of Vehicles, and because pointers don’t have any addition info on their own…

•       A maximum capacity of the array

•       A count of how many Vehicles you currently have

In addition, you should create the following functions (plus the special functions—a copy constructor, assignment operator, and destructor):

DealershipThe Dealership class in some ways is very similar to the Showroom. It will store a dynamic array, this time of Showroom objects. It will also need a name and ways to keep track of how many Showrooms it can store, versus how many it is currently storing.

Based on the layout of main.cpp (and the test output), you will also need a way to print everything in its inventory (which consists of Showrooms which consist of Vehicles), but also a way to get the average price of each vehicle.

Be sure to define the big three as well.

TipsA few tips about this assignment:

•       Remember the “Big Three” or the “Rule of Three” o If you define one of the three special functions (copy constructor, assignment operator, or destructor), you should define the other two

•       You can print out a tab character (the escape sequence ‘t’ ) to help line up the output.

•       Don’t try to tackle everything all at once. Work on one class at a time. Can’t have a Showroom without a Vehicle…

•       You can customize the way numbers are displayed in C++ (particularly floating-point numbers).

The header file &lt;iomanip contains this functionality. Look into std::fixed and std::setprecision()

•       Refer back to the recommended chapters in your textbook as well as lecture videos for an explanation of the details of dynamic memory allocation o There are a lot of things to remember when memory allocation