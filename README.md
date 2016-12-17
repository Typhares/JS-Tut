# JS-Tut
js  excercises w shane maene
/*
var testStr = "some text";
var totalCount = -1;

function countingE(  )  {

var total =  0
	declaring a local variable that will hold the value of total numbers of e 

for ( counter = 0;  counter < testStr.length;  counter++ )  {
	condition: is there more string to loop through Y/N; T/F?
	how does the condition know that it has reached the end of the array/string.
	it compares the array.length to the counter. JS indexing is zero-based, if array.length is 50; the the last character in the array 49, therefore the ending value of counter is now 50 and the loop exits.
	
	iteration, keep looping back one more time, until the condition is not met
	the value of i changes to 1+ (which is the position of the last character that it checked) for example if we are on the 50th loop and counter started at zero, the value of counter is now 49.


	LOOP BODY
	if statement tests for the value of an "e" in the current index of testStr, print out the string "Found an e!"; and also add the total number of 'e's found as of this position in the array.
	The two dependent actions that the if statement must do each time it finds an 'e": compute the total number of 'e's in testStr and log a message "  ";

	if( testStr[counter] === 'e') {
		console.log("Found an e!");
		//do something add up all the e's 
		total++;
		
	}

	}
	return total


}
console.log("Total 'e'-count in testStr was" + countingE( ) ) ; //logging the returned value upon invoking the countingE function
totalCount = countingE ( );
//console.log("Total 'e'-count in testStr was" + totalCount);


*/
