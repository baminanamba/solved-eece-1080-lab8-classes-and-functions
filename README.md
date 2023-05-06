Download Link: https://assignmentchef.com/product/solved-eece-1080-lab8-classes-and-functions
<br>
This assignment is an introduction to the C++ classes. We will learn the basic of class design, and we will put it to use creating a couple of more advanced classes.

<strong>Part A: Class Practice – Warm Up Exercises</strong> <strong>Problem Statement: </strong>

In part A, you will create two programs to solve for surface area, and volume of a specific shape. A list of geometric shapes can be found on the following:

<a href="https://www.mathsisfun.com/geometry/common-3d-shapes.html">http://www.mathsisfun.com/geometry/common-3d-shapes.html</a><u>    </u>

To get you started, review the sample_shape.cpp for sample code of a 2D rectangular object. Make sure you view it in “raw” mode.

<strong>Task 1:</strong>​ Pick a 3D shape from the ​<strong><em>mathisfun</em></strong>​ website.

Source File: lab8/shape1.cpp

Using the example solution given above as your guide, create a solution to solve for the surface area and volume of your chosen shape using C++ classes.

<em>Provide sample calculations for this shape to verify that it works properly. </em>

Please create proper test cases for this in main() to verify proper functioning.

<strong>Task 2:</strong>​ Pick another 3D shape from the ​<strong><em>mathisfun</em></strong>​ website.

Source File: lab8/shape2.cpp

Using the program developed in ​<strong><em>Task 1</em></strong>​ as a template, develop one more C++ class contained in a separate C++ program to solve for surface area and volume of your selected object.

<em>Provide sample calculations and sample output for each of these shapes. </em>

Please create proper test cases for this in main() to verify proper functioning.

<strong>Part B: Create Point Class   – Milestone One </strong>

Source File: lab8/point_class.cpp <strong>Problem Statement:  </strong>

Start by downloading the point_class.cpp file on blackboard for the <strong><em>Point</em></strong>​            class. It implements operator overloading so you can use cin/cout with point objects.

Complete the provided  “Point” class which allows a programmer to store an x, y coordinate pair. It should have at least two constructors, at least one set function, and get functions for x and y.

The overloaded I/O (cin/cout) functions have been provided for your use.

Please create proper test cases for this in main() to verify proper functioning.

<strong>Part C: Line Class  </strong>

Source File: lab8/line_class.cpp

<strong>Problem Statement: </strong>

Start by downloading the line_class.cpp from blackboard for the <strong><em>Line </em></strong>​ ​class.

It implements operator overloading so you can use cin/cout with line objects.

A line will be made up of two points.

Create an object to implement a “line” class which allows the programmer to store a line. This class must use the “point” class developed in Part B. The object should have two constructors, appropriate set/get functions, and overloaded I/O (cin/cout) functions. It should include functions the return the proper value for the following:

<ul>

 <li>Determine the slope of a line</li>

 <li>Determine the length of a line</li>

 <li>Determine the y-intercept of a line Determine if the line is vertical</li>

 <li>Determine if the line is horizontal</li>

 <li>Determine if the line is parallel to another line</li>

 <li></li>

</ul>

Please create proper test cases for this in main() to verify proper functioning.

Note: You should make it easy on yourself and use four integers representing the two ends of the line for the second constructor

<strong>Part D: Let’s Practice Strings with classes </strong>

Source File: lab8/string_manip.cpp

Start by downloading the string_manip.cpp for the <strong><em>stringManip </em></strong>​ ​class.

Please review the “cctype” and string review given on the last page of this document.

It will give you a shell to implement the following class prototype:

class stringManip {     <em>public:</em>​             stringManip(); stringManip(string input); string retrieve(); void setString(string input); void chop(); void padString(int n); void center(int length); void truncate(int n); void removeNonAlpha(); void convertToUpperCase(); void convertToLowerCase();

<em>private:</em>​

string tobeEdited;

};




All functions act on the <strong><em>tobeEdited </em></strong>​                ​string inside of the class unless indicated otherwise.




Please implement the functions indicated plus the constructors, and set/get

(retrieve and setString) functions.




Function/method descriptions.

<ol>

 <li>chop() – remove both leading and trailing spaces from the string.</li>

 <li>padString(int n) – Write a function to make sure that the string is at least “n” bytes in length. Please add a space or spaces Add blanks toAdd blanks toto the end of the string to accomplish this. If the</li>

</ol>

string length is already equal to or larger than “n”, do not modify the string.

<ol start="3">

 <li>center(int length) – Write a function to center the string within the space specified by length. You should remove any existing leading and trailing spaces in the string before centering it.</li>

</ol>

Add blanks to the front and back of the string.  If an odd number of blanks have to be added, put the extra blank on the right. You should store the result back in the “tobeEdited” string.

<ol start="4">

 <li>truncate(int n) is a function which shortens the string to n characters.</li>

</ol>

If the string is already shorter than n, the function should not change the string. The characters should be removed from the end of the string.

<ol start="5">

 <li>removeNonAlpha() is function that removes all characters (including spaces) that are not alphabetical from the string. The isalpha function may be helpful for this purpose.</li>

 <li>conver ToUpperCase() is a function that converts all lowercase characters in the string to uppercase. All other characters remain the same.</li>

 <li>convertToLowerCase() is a function that converts all lowercase characters in the string to uppercase. All other characters remain the same.</li>

</ol>


