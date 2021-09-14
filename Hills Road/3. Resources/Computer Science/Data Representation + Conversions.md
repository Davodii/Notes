# Converting between type of Data
---
## Decimal, Hexadecimal and Binary
Decimal, Hex and Binary are the most commonly used data representation types since they are the easiest to under stand and are quite easy to convert between each of them.

#### Decimal 
The decimal system refers to the counting system we use in our day-to-day lives where each digit in a number is multiplied by `10^(position of digit)`.

#### Binary
Binary is used by computers to store data since it only uses on and off to store values. Each bit used represents a power of `2`. Starting with the far right bit which represents `1` or `2^0` then there is the next bit to the left which is `2` or `2^1` and so on.

#### Hexadecimal
Hexadecimal is most commonly used to better visualize binary. The way hexadecimal works is by instead of using `10` to multiply digits it uses `16`.

Hex uses `16` total characters to represent values and these are:
`0 1 2 3 4 5 6 7 8 9 A B C D E F`.

#### Decimal to Hex Conversion
To convert a decimal number into a hexadecimal number, you first divide the number by `16`. You take the whole number output and convert that into one of the characters of hex. You then take the remainder and then divide that by `16`. Continue on until the divisible number remains in a loop.

Here is an example of this:
`Convert 168 into hex:`
`168 / 16 = 10 remainder 8`
`Convert 10 to hex: 10 = A`
`8 / 16 = 0 remiander 8`
`convert 8 to hex: 8 = 8`
`Final hexcode is = A8`

#### Hex To Decimal
To convert from a hexadecimal number to a decimal, you take the decimal equivalent of each character and multiply it by `16^(position of character)` and add up the results.

Here is an example of this:
`Convert 8A into decimal`
`10 * 16^0 = 10`
`8  * 16^1 = 128`
`10 + 128 = 138`

---