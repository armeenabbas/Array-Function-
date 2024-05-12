##ARRAY##
This TypeScript example demonstrates basic array usage, focusing on how to declare arrays, access array elements, and index arrays. The example includes arrays of numbers and strings, showcasing simple operations like accessing specific elements.

Overview
In this project, you'll find examples of how to:

Declare arrays with predefined elements.
Access elements in an array using indices.
Comment and uncomment lines to observe different outputs.
Code Explanation
Variable Declarations
Multiple variables (rollno0, rollno1, etc.) are declared with type annotations to hold numbers, showing individual assignments:

var rollno0:number = 1;
var rollno1:number = 2;
var rollno2:number = 3;
var rollno3:number = 4;
var rollno4:number = 5;

Array Declarations
Two arrays are declared: studentName and studentRollNo. studentName is an array of strings containing names, and studentRollNo is an array of numbers representing roll numbers.
var studentName: string[] = ["ahsan", "Naeem", "Ali", "Yasir"];
var studentRollNo: number[] = [10, 20, 30, 40, 50, 60, 70];

Accessing Array Elements
The code demonstrates how to access an array element by its index. For example, accessing the fourth name in the studentName array:
console.log(studentName[3]); // Outputs: "Yasir"

Conclusion
This example provides a foundational understanding of working with arrays in TypeScript. By examining and manipulating the provided code, users can learn how to declare arrays, access array elements, and utilize indexing to handle data efficiently.

