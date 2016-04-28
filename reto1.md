//# courseraSwiftReto1
//Reto de la seman 2

//: Playground - noun: a place where people can play

import UIKit

var str = "Hello, playground"

/*  NOTAS

El cero es numero PAR
El cero es divisible por cualquier numero

*/

for var i = 0; i <= 100; i++ {
    if i%5 == 0 {
        print("\(i) Bingo!!!")
    }
    if i % 2 == 0 {
        print("\(i) Par")

    }
    if i % 2 == 1 {
        print("\(i) Impar")

    }
    if i >= 30 && i <= 40 {
        print("\(i) Viva Swift!!!")
        
    }
    
    
}
