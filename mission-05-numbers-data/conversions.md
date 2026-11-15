# mission 5 - number representation and text encoding

## task 5.1 - manual conversions

### decimal 13 to binary
repeated division by 2:
13 / 2 = 6 remainder 1
6 / 2 = 3 remainder 0
3 / 2 = 1 remainder 1
1 / 2 = 0 remainder 1
remainders read from bottom to top give 1101
so 13 in decimal = 1101 in binary

### decimal 25 to binary
repeated division by 2:
25 / 2 = 12 remainder 1
12 / 2 = 6 remainder 0
6 / 2 = 3 remainder 0
3 / 2 = 1 remainder 1
1 / 2 = 0 remainder 1
remainders read from bottom to top give 11001
so 25 in decimal = 11001 in binary

### binary 1010 to decimal
place values:
1*2^3 + 0*2^2 + 1*2^1 + 0*2^0
= 8 + 0 + 2 + 0
= 10

### binary 1101 to decimal
place values:
1*2^3 + 1*2^2 + 0*2^1 + 1*2^0
= 8 + 4 + 0 + 1
= 13

### hexadecimal a to decimal
hex digit a represents 10
10 * 16^0 = 10

### hexadecimal 1f to decimal
place values where f is 15:
1*16^1 + 15*16^0
= 16 + 15
= 31

### binary 1111 to hexadecimal
place values:
1*2^3 + 1*2^2 + 1*2^1 + 1*2^0
= 8 + 4 + 2 + 1
= 15
decimal 15 is f in hexadecimal
so 1111 in binary = f in hexadecimal

## task 5.2 - python verification
| expression | python result | manual answer | match |
| --- | --- | --- | --- |
| bin(13)[2:] | 1101 | 1101 | yes |
| bin(25)[2:] | 11001 | 11001 | yes |
| int("1010", 2) | 10 | 10 | yes |
| int("1101", 2) | 13 | 13 | yes |
| hex(10)[2:] | a | a | yes |
| int("1f", 16) | 31 | 31 | yes |
| hex(int("1111", 2))[2:] | f | f | yes |

## task 5.4 - text encoding
- ascii decimal code for uppercase a: 65
- ascii decimal code for lowercase a: 97
- example character outside basic ascii: euro symbol € or smiley emoji 😊
text encoding maps characters to numbers so computers can store and display text
ascii provides 128 basic characters while unicode utf-8 supports symbols and characters across languages
