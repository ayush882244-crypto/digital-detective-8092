# mission 5 - numbers and data

## 1 task / objective
practice number conversions between decimal binary and hexadecimal verify with python build number converter script and explain text encoding

## 2 work completed
completed seven manual conversions showing full working
verified all manual conversions in python terminal
built and tested number_converter.py program with three numbers
documented ascii codes and character encoding concept

## 3 commands / tools used
- python3: ran interactive python shell and conversion script
- bin(): built-in function to convert integer to binary string
- hex(): built-in function to convert integer to hexadecimal string
- int(): built-in function to parse string to integer with base

## 4 my understanding

### task 5.1 - manual number conversions
| question | your working and answer |
| --- | --- |
| convert decimal 13 to binary | 13/2=6 rem 1, 6/2=3 rem 0, 3/2=1 rem 1, 1/2=0 rem 1, reading bottom to top gives 1101 |
| convert decimal 25 to binary | 25/2=12 rem 1, 12/2=6 rem 0, 6/2=3 rem 0, 3/2=1 rem 1, 1/2=0 rem 1, reading bottom to top gives 11001 |
| convert binary 1010 to decimal | (1*8) + (0*4) + (1*2) + (0*1) = 8 + 0 + 2 + 0 = 10 |
| convert binary 1101 to decimal | (1*8) + (1*4) + (0*2) + (1*1) = 8 + 4 + 0 + 1 = 13 |
| convert hexadecimal a to decimal | a represents 10 so (10*1) = 10 |
| convert hexadecimal 1f to decimal | (1*16) + (15*1) = 16 + 15 = 31 |
| convert binary 1111 to hexadecimal | (1*8) + (1*4) + (1*2) + (1*1) = 15 which is f in hexadecimal |

### task 5.2 - python verification
| expression tested | python output | matches manual calculation |
| --- | --- | --- |
| bin(13) | 0b1101 | yes |
| bin(25) | 0b11001 | yes |
| int('1010', 2) | 10 | yes |
| int('1101', 2) | 13 | yes |
| int('a', 16) | 10 | yes |
| int('1f', 16) | 31 | yes |
| hex(0b1111) | 0xf | yes |

### task 5.3 - number converter script
the script asks user for a decimal integer and converts it using built-in functions
bin() takes an integer and converts it to binary representation prefixed with 0b
hex() takes an integer and converts it to hexadecimal representation prefixed with 0x
slicing [2:] removes the prefix to display clean digits

test results:
| test number | binary output | hexadecimal output |
| --- | --- | --- |
| 13 | 1101 | d |
| 25 | 11001 | 19 |
| 42 | 101010 | 2a |

### task 5.4 - text encoding
- ascii decimal codes:
  uppercase letter a has ascii code 65
  lowercase letter a has ascii code 97
- why computers need encoding standard:
  computers only store binary bits so an encoding standard provides a common mapping from numbers to characters so text can be read consistently
- character outside basic ascii:
  euro symbol € or hindi letter क or smiley emoji 😊

## 5 difficulties faced
handling the 0b and 0x prefixes returned by python conversion functions

## 6 how i resolved them
used string slicing [2:] to strip off the prefixes when displaying the output

## 7 evidence / files
- mission-05-numbers-data/number_converter.py

## 8 commit details
commit message: build number converter and practise data representation
