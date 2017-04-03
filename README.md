# If-else-if-else-statements
Example of an If/else if/else statement

var age = 30;

if (age >= 35) {
  console.log('You can vote AND run for President!');
} else if (age >= 30) {
  console.log('You can vote AND run for the Senate!');
} else if (age >= 18) {
  console.log('You can vote!');
} else {
  console.log('You can\'t vote, but you can write your representatives.');
}

//output = You can vote AND run for the Senate!
//a second example:

var temperature = 80;
if (temperature <= 50) {
  console.log('Put on a coat!');
} else if (temperature <= 30) {
  console.log('Put on a coat and a hat!');
} else if (temperature <=0) {
  console.log('Stay inside!');
} else {
  console.log('Wear whatever you want!');
}

//output = Waer whatever you want!

var temperature = 30;
var windchill = -10;
if (temperature <= 50 && windchill <= 50) {
  console.log('Put on a coat!');
} else {
  console.log('Wear whatever you want!');
}

//output = Put on a coat!
