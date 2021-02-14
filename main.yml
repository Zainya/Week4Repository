//index.js

//Using template literals instead of concatenation, write a function that takes firstName
//and lastName and returns ‘firstName lastName’
function createFullname(firstName, lastName) {
    return `${firstName} ${lastName}`;
 
    }
console.log(createFullname('Mary', 'Lamb'));


//Write the same function as above as an arrow function with a different name.

const createFullName = (firstName, lastName) => firstName + ' ' + lastName;

console.log(createFullName('Zainya', 'Mcgarrell'));

//Using setTimeout, write an anonymous (has no name assigned to it) arrow function in the callback parameter position. The function should alert ‘Time is up!

function sayHi(phrase, who) {
    alert( phrase + ', ' + who );
  }
  
  setTimeout(sayHi, 1000, "Time is up");

//b. Write an arrow function named askAreWeThereYet that alerts ‘Are we there yet?’. Using setInterval, pass askAreWeThereYet into 
//      the callback parameter position. Choose whatever length of time you want for the interval.

let askAreWeThereYet = () => {
    console.log('Are we there yet?');
}

setInterval(askAreWeThereYet, 8000);


// In this step you are going to write a function that takes a callback to better understand how callbacks work.


// Write a function named processSplicedValue that takes 3 parameters – an array, the index of the element to be 
// spliced from the array, and a callback that will process the sliced element.
// Inside the function, use the first two parameters to splice an element from the array.

let myArray = ['Zainya', 25, 'Mcgarrell', 4, 'Mary', 29, 'Lamb', 5];

function processSplicedValue(myArray, element, callback) {
    myArray.splice(element, 1);
     callback(myArray);
}

processSplicedValue(myArray, 1, (newArray) => {
    console.log(newArray);
});


// Call the callback function and pass the spliced value into it.
let myArr = ['Zainya', 25, 'Mcgarrell', 64, 'Mary', 29, 'Lamb', 5];

function processSplicedValue2(myArr, element, callback) {
   let value = myArr.splice(element, 1);
    callback(value);
}

processSplicedValue2(myArr, 1, (newArr) => {
    console.log(newArr);
});


//Outside of the function, create an array of strings, call processSplicedValue, and pass in the array you just created, an index number, and console.log into it. 
//For example: processSplicedValue(arrayName, 2, console.log);

let arrayOfStrings = ['Zainya', 'Zahari', 'Zane', 'Zainel', 'Chanel', 'Lesly', 'Jaevon']
processSplicedValue(arrayOfStrings, 4, console.log)


//Call the processSplicedValue function again, but this time pass in an anonymous arrow function that alerts the spliced value.
