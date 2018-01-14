//Basic JavaScript method
$(".myCheckboxes").change(function(){ 
    if(this.checked) 
       alert("checked"); 
});


//Using JQuery method - 
$(".myCheckboxes").change(function(){ 
      if($(this).is(":checked")) 
         alert("checked"); 
});

/*
$() is the jQuery constructor function.

this is a reference to the DOM element of invocation.

So basically, in $(this), you are just passing the this in $() as a parameter so that you could call jQuery methods and functions.

*/

this // is equivalent to calling document.getElementById("myDiv") 

$("#myDiv")[0] === document.getElementById("myDiv");

$("#myDiv")[0] === this

.each(function(i,e){
	//'i' is the array
	//'e' is the current element of the array
});

.each //is equivalent to "for loop"


//Passing Object
moment(new Date())



//Passing function

moment.updateLocale('en', {
    isPM : function (input) {
        return ((input + '').toLowerCase()[0] === 'p');
    }
});

