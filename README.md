# Assignment1
#Question1<br>

#Question2<br>
The main function takes the input for the echo energies and calls the recursive function check.<br>
The recursive function is called two times in main function 2 times such that the first element is not added as location in the trail and the second time is added by chaning the current variable to the first element. The five arguments of the check function are index(which is the current index in the echo array we are on while surfing through the array),the echo array,total echo energies,current variable(the last location in the trail) and the count variable(number of locations in trail till now).<br>
The recursive function is surfing through the array while adding the locations in the trail while ensuring the conditions<br>
The stopping condition is when the index variable is equal tp n-1, it also assigns the the value of count variable to a global variable m after checking the condition of count being greater than m(m is initially 0)<br>
