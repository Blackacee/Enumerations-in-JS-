# Enumerations-in-JS-

// Prevent the enum from being changed
const TestEnum = Object.freeze({
 One:1,
 Two:2,
 Three:3
});
// Define a variable with a value from the enum
var x = TestEnum.Two;
// Prints a value according to the variable's enum value
switch(x) {
 case TestEnum.One:
 console.log("111");
 break;
 case TestEnum.Two:
 console.log("222");
}
