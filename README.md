# MobileDevLogicalTest

1. Define an array of numbers (use any random numbers). Write a program to print only the even numbers of the array. Do not use any library functions, need to do via for loops only. 

    let numbers = [2,3,45,6,79,86,97,11,14];
    for (let i=0; i<=numbers.length; i++){
	    if(numbers[i] % 2 === 0 ){
			    console.log(numbers[i])
			    }
	    }	
	
2. Find the maximum consecutive 1's in an array of 0's and 1's.
	
	let maxOnes = (arry)=>{
		let maxOnes = 0;
		let count = 0;
		for ( let i in arry){
			count = arry[i] === 1 ? count + 1 : 0 ;
			if (count > maxOnes){
				maxOnes = count
				}
		} return maxOnes; }
		
		
4. Let’s see we an api url www.example.com/api/get/1 Write a sample code to call this rest api and display the result.

var apicall = () => {
	fetch("www.example.com/api/get/1")
	.then(response => response.json())
  .then(data => console.log(data));
	}
	apicall();
	

	
