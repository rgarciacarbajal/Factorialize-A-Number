# Factorialize-A-Number

function factorial (num) {
  let sum = 1;
  for (let i = num; i > 0; i--){
    sum *= i;
  }
  return sum;
}

console.log(factorial(5));
console.log(factorial(7));
console.log(factorial(3));
