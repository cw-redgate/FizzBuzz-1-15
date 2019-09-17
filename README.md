# FizzBuzz-1-15
function FizzBuzz(n) {  
   if (n % 15 === 0) {
   return "FizzBuzz";
}

if (n % 5 === 0) {
  return "Buzz";
}

if (n % 3 === 0) {
  return "Fizz";
}

return n.toString();
}

console.log(FizzBuzz(1))
console.log(FizzBuzz(2))
console.log(FizzBuzz(3))
console.log(FizzBuzz(4))
console.log(FizzBuzz(5))
console.log(FizzBuzz(6))
console.log(FizzBuzz(7))
console.log(FizzBuzz(8))
console.log(FizzBuzz(9))
console.log(FizzBuzz(10))
console.log(FizzBuzz(11))
console.log(FizzBuzz(12))
console.log(FizzBuzz(13))
console.log(FizzBuzz(14))
console.log(FizzBuzz(15))
