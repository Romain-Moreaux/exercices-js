/*
Écrivez une fonction récursive qui prend un entier et calcule la somme cumulée de 0 à cet entier

factorielle(n) =
  si (n = 0) alors 1
  sinon n * factorielle(n-1)
*/

// forme recursives
function recSum(n){
    return n === 1 ? 1 : n + recSum(n-1);
}

console.log(recSum(04)); //10


function recFac(n) {
    return n === 1 ? 1 : n * recFac(n-1);
}

console.log(recFac(5));


//Faux
// function recSub(n) {
//     return n === 1 ? 1 : n - recSub(n-1);
// }
//
// console.log(recSub(5));

/*
Étant donné un entier, créez une fonction qui renvoie la somme de tous les chiffres individuels de cet entier. Par exemple: si n = 4321, renvoyer 4 + 3 + 2 + 1 soit la valeur 10
*/

function sumDigit(n){
  if (n < 1) return 0;
  else
    return Math.floor(n%10 + sumDigit(n/10));
  // while (n >= 10){
  //   n /= 10;
  // }
  // return Math.floor(n);
}

console.log(sumDigit(01234));
