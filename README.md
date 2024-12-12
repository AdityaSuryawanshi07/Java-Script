In this Java-Script module we are going to write about Java-script all topics one by one.

Topics we are going to cover are:

1. Array
2. Object

3. Lets Start From Array:
4. So Array in Java-script are special varriable which can hold more value but with same data types.
5. const fruits = ["Banana", "Orange", "Apple"];  ------ This is our simple array.



# Array Methods :

<!-- In this module we are going to learn about Java-script Array Methods. -->

    <script language="javascript"  type="text/javascript" >


        // Basic Javascript Methods :

        // 1.Array push()    --------   Used to add element to array but at the last.
        // 2.Array pop()     --------   Used to remove element to array but at the last.
        // 3.Array unshift() --------   Used to add element to array but at the beginning.
        // 4.Array length    --------   Used to calculate the length of the array.
        // 5.Array concat()  --------   Used to join two arrays end to end.
        // 6.Array at()       -------   Used to access any element in array by its Index number. 
        // 7.Array delete()   -------   Used to delete element in array with index number but use pop() instead of delete(). 
       
       //  There are more JS methods :
       
        // Array shift()   --------   Used to delete element to array but at the beginning.
        // Array splice()  --------   Used to add new elements at specific index number to array.
        // Array toSpliced() ------   Used to remove elements from specific index number to array.
        // Array slice()   --------   Used to create new array from previous array from remaining index numbers.
        // Array at()       -------   Used to access any element in array by its Index number. 
        // Array toString() -------   Used to convert the array to th string separated with the coma.

        // -----------------   Lets Start  -----------------------------------

        // Array push();

        document.write("# Lets create a simple array to perform Method's on it <br><br>");

        const fruits = ["Orange","Banana","Kivi","Mango"];
        document.write(fruits);

        document.write("<br><br>Now we are going to add new element in array with push() method. <br><br> 1. push() --- will add element at last");

        fruits.push("Water-Melon");

        document.write("<br><br>"+fruits)

// -----------------------------------------------------------------------------------------------------------------------------------


        document.write("<br><br>"+"2. pop() --- this will remove last element from array <br><br>");

        fruits.pop();

        document.write(fruits);


// -----------------------------------------------------------------------------------------------------------------------------------


        document.write("<br><br>");
        document.write("3. unshift() ------ Used to add element at first in Array. <br><br>");

        document.write(fruits);

        document.write("<br><br>");

        fruits.unshift("Cherry");

        document.write("After adding new element 'Cherry' to array : <br><br>");

        document.write(fruits);


// -----------------------------------------------------------------------------------------------------------------------------------


        document.write("<br><br>");
        document.write("4. length() ------ Used to calculate length of the Array. <br><br>");

        let size = fruits.length;

        document.write("Elements in Array are : "+size);

        document.write("<br><br>");

// -----------------------------------------------------------------------------------------------------------------------------------

        document.write("5. concat()  ----- Used to join to Arrays from end to end.");

        let colors = ["Red","Blue","Orange"];

        document.write("<br><br>");

        document.write("First array is : "+fruits +"<br>");
        document.write("Second array is : "+colors +"<br>");


        let twoArrays = fruits.concat(colors);

        document.write("<br>");

        document.write("After joining Fruits to the Colors.<br><br> New Array : "+twoArrays);


        document.write("<br><br>");

// -----------------------------------------------------------------------------------------------------------------------------------


        document.write("6. at()  --- Used to access Elements in Array by its Index Number.");
        document.write("<br><br>");

        document.write("Lets locate 'Orange' in Fruits Array.");

        document.write("<br>");

        document.write("Element at 2 No at Array Fruits is : "+fruits.at(1));

        document.write("<br><br>");
        
// -----------------------------------------------------------------------------------------------------------------------------------


        document.write("7. delete()   ----- delete() method is used to delete elements from Array but it leaves undefined spaces in Array so instead of using delete() method, use pop() or shift() method.");
        
        document.write("<br><br>");

        document.write(colors + "<br><br> Now we are going to delete first element of Array colors. <br><br>");

        delete colors[0];

        document.write(colors);

// -----------------------------------------------------------------------------------------------------------------------------------

        document.write("<br><br>");

        document.write("8. shift()   ------- Used to delete element from array but from beginning. <br><br>");

        document.write("Lets take our first array fruits and then delete its first element.  <br><br>");

        document.write(fruits);

        fruits.shift();

        document.write("<br>");
        document.write(fruits);


// -----------------------------------------------------------------------------------------------------------------------------------


        document.write("<br><br>");
        document.write(fruits+"<br><br>");

        document.write("9. splice()  ---- Used to add elements to specific index number  <br><br>");

        fruits.splice(2, 0, "Lemon", "Strawberry");
        document.write(fruits);


// -----------------------------------------------------------------------------------------------------------------------------------


        document.write("<br><br>");

        document.write("10. toSpliced()   --------------- Used to remove elements from selected index value.<br><br>#Lets delete same elemets we added from previous method. <br><br>");


        document.write(fruits+" -- We are going to delete Lemon and strawberry from the Array with toSpliced() methods <br><br>");


        spliced =  fruits.toSpliced(2,3);
        document.write(spliced);


// -----------------------------------------------------------------------------------------------------------------------------------

        document.write("<br><br>");

        document.write("11. slice()  ----- Used to create new array from given Index Number <br><br>");


        document.write(fruits +"<br><br>");

        const newArray = fruits.slice(2);

        document.write(newArray);


// -----------------------------------------------------------------------------------------------------------------------------------

        document.write("<br><br>");
        document.write("12. at()   ------- Used to access any element in array by its Index number. <br><br>"); 

        locate = fruits.at(1);
        document.write(locate);

        
 //---------------------------------------------------------------------------------------------------------------------------------

        document.write("<br><br>");

        document.write("13. toString() -------   Used to convert the array to th string separated with the coma. <br><br>");

        document.write(fruits.toString());

// ----------------------------------------------------------------------------------------------------------------------------------- 
