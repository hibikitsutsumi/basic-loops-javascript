//for loop
var i;

for(i = 0; i < 10; i+=1){
  console.log(i); // always terminate with semicolon even though it will not change the result.
}


//while loop
var j = 0;
while(j < 10){
  console.log(j);
  j+=1; // do not forget this line, it will cause infinite loop without condition.
}

//Factrial number(while)
var number = 5;
var sum = 1;
while(number > 0){
  sum *= number;
  number -= 1;
}
alert(sum);

//factrial number(for)
var i 
for(i = 5; i < 0; i-=1){
   console.log(i);

}
alert(sum);

var i 
for(i = 5; i < 0; i-=1){
   sum *=number;
}

