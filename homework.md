<b> Part 1 </b><br>
What are actions used for?<br>
Actions are objects that contain the type that the case uses and any info that needs to be sent into the function. <br>
What type of object must an action be?<br>
Plain javascript object<br>
At a minimum, what is the one property the action should have?<br>
Type<br>
And what is this property used for? <br>
To determine what switch gate the function follows<br>
What is the responsibility of the reducer? <br>
To take in the action, pass it to the correct case and perform whatever that case needs to be done. <br>
What is the responsibility of the store? <br>
The store is a set of functions which handles the reducer, it's subscription and the dispatches. It is also where the state is kept, accessible through the getState function.

<b>Part 2</b><br>
1) impure<br>
2) impure<br>
3) pure<br>
4) impure<br>
5) pure<br>
