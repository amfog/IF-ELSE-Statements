# IF-ELSE-Statements
if else syntax and how to use it 

/*
  if (condition1){
    execute  code here
  }else if (condition2){
    execute this code
  }else if (condition3){
    execute this code
  }else {
    execute code in here }*/
    
    
void main() {
  var salary = 25000;
//assigning the value of the variable salary which is 25000
  if (salary > 20000){
//here, i am asking if salary is greater than 20000 then print wow.
    print('WOW');
  } else {
//if it is not greater than 25000 then print you need to work hard.
    print ("You need to work harder");}
/* if (condition) {
execute the code of the condition is true}
else{
execute the code in here if the condition is false }
*/

  //if else if ladder statements
  var marks = 91;
  if (marks >= 90 && marks< 100 ){
    print("A+ Grade");
  }else if (marks >=80 && marks < 90 ){
    print("A Grade");

  }else if (marks >= 70&& marks > 80){
    print ("B Grade");
  }else if (marks >= 60 && marks > 70){
    print ("C Grade");
  }else if (marks > 30 && marks < 60){
    print("D Grade");
  }else if (marks >= 0 &&marks <30 ){
    print("you have failed");
  }

// what if variable marks is more than 100 or -1

  else { print ("invalid Marks, Please try again");}


/* if else condition is about your input so try to put all the possible odds to your code.*/



