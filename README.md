# testvar month = prompt("Enter a month");
var cat = month.toLowerCase();
var test = cat.slice(0,3);

switch(test) {
   case "feb" : confirm("Is it a leap year?") === false ? alert("28") : alert("29"); break;
   case "apr" : 
   case "jun" : 
   case "sep" :  
   case "nov" : 
   case "jun" : alert("30"); break;
   case "jul" : 
   case "aug" : 
   case "mar" : 
   case "oct" : 
   case "jan" : 
   case "dec" : alert("31"); break;
default : alert("reenter");
}
