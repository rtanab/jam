# Under construction...
# Jam
Jam is a game using dice and this program is for practicing to make a program.

# Object
To learn how to program game. Also learning how to make AI in game. To understand how to avoid cheeting finally.

# Rule
1. Throw 5 dices to arrange each numbers at most 3 times.
1. If you have a special hand(Jam, Carre, Full, Petite-Suite, Grande-Suite, Maximum or Minimum), you can get special points. The special hands have different points (I'll write it later).
1. If you don't have any special hands or numbers, you have to abort one of special hands or numbers.
1. If the sum of your numbers is more than 63 points, you can get the extra 25 points. (N + 25)

# Point
* Numbers
  * You can put sum of each numbers.
    * I.E. (1, 1, 3, 5, 6) -> 1 + 1 = 2, so you can get 2 points for number "1".
* Special
  * Jam - 50 points: 5 same numbers.
    * I.E. (1, 1, 1, 1, 1)
  * Carre - 40 points: 4 same numbers.
    * I.E. (1, 1, 1, 1, 5)
  * Full - 30 points: 2 pairs of numbers which are 3 same numbers and 2 same numbers.
    * I.E. (1, 1, 1, 2, 2) -> 1,1,1 and 2,2.
  * Petite-Suite - 20 points: 4 numbers in a row.
    * I.E. (1, 3, 4, 5, 6) -> 3,4,5,6 is 4 numbers in a row.
  * Grande-Suite - 30 points : 5 numbers in a row.
    * I. E (1, 2, 3, 4, 5) -> 1,2,3,4,5 is 5 numbers in a row.
  * Maximum - Sum of the number of the dices, but it needs to be more than number of Minimum: You can get this hand whenever you want it.
  * Minimum - Sum of the number of the dices, but it needs to be less than number of Maximum: You can get this hand whenever you want it.

#　Plan
1. Make it at first, little by little.
1. Make enemy(AI?)
1. Configure CPU's strength(Hard, Medium, Easy)
1. Learn how to avoid cheeting by myself.
