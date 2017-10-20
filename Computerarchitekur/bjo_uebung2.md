Barnabas Jovanovics

## 1a) 14

1. In Binaer umwandeln 14 -> 1110
2. Normalisierung 1110 = 1.110 * 2^3
3. VZ-Bit: + -> 0
4. Exponent: +3 +127 -> 10000010
5. Fraction: M = 1.11 F = 11000000000000000000000
6. Bitmuster:  
  1-Vz-Bit  8-Bit-Exponent  23-Bit Fraction  
  0100|0001|0110|0000|0000|0000|0000|0000
7. HEX-Darstellung  
  4 1 6 0 0 0 0 0

## 1b) 13/32

1. In Binaer umwandeln 13/32 = 13 * 2^-5 -> 0.01101
2. Normalisierung 0.01101 = 1.101 * 2^-2
3. VZ-Bit: + -> 0
4. Exponent: -2 +127 -> 01111101
5. Fraction: M = 1.101 F = 10100000000000000000000
6. Bitmuster:  
  1-Vz-Bit  8-Bit-Exponent  23-Bit Fraction  
  0011|1110|1101|0000|0000|0000|0000|0000
7. HEX-Darstellung  
  3 E D 0 0 0 0 0

## 1c) -13/32

1. In Binaer umwandeln 13/32 = 13 * 2^-5 -> -0.01101
2. Normalisierung -0.01101 = -1.101 * 2^-2
3. VZ-Bit: - -> 1
4. Exponent: -2 +127 -> 01111101
5. Fraction: M = 1.101 F = 10100000000000000000000
6. Bitmuster:  
  1-Vz-Bit  8-Bit-Exponent  23-Bit Fraction  
  1011|1110|1101|0000|0000|0000|0000|0000
7. HEX-Darstellung  
  B E D 0 0 0 0 0

## 1d) 7.125

1. 0.125 * 2 0  
0.25 * 2 0  
0.5 * 2  1  
111.001
2. Normalisierung 111.001 = 1.11001 * 2^2
3. VZ-Bit: + -> 0
4. Exponent: +2 +127 -> 10000001
5. Fraction: M = 1.101 F = 11001000000000000000000
6. Bitmuster:  
  1-Vz-Bit  8-Bit-Exponent  23-Bit Fraction  
  0100|0000|1110|0100|0000|0000|0000|0000
7. HEX-Darstellung  
  4 0 E 4 0 0 0 0

## 1e) -42

1. In Binaer umwandeln -101010
2. Normalisierung -101010 = -1.0101 * 2^5
3. VZ-Bit: - -> 1
4. Exponent: +5 +127 -> 10000100
5. Fraction: M = 1.101 F = 01010000000000000000000
6. Bitmuster:  
  1-Vz-Bit  8-Bit-Exponent  23-Bit Fraction  
  1100|0010|0010|1000|0000|0000|0000|0000
7. HEX-Darstellung  
  C 2 2 8 0 0 0 0

--- 

## 2a) 42280000

1. In Binaer umwandeln  0|01000100|01010000000000000000000
2. Fraction: 01010000000000000000000, Mantisse 1.0101
3. Exponent: 01000100 = 132 - 127 = 5
4. Vz-Bit 0 -> +
5. Normalisierung 1.0101 * 2^5 = 101010
6. In Dezimal umwandeln 101010 = 42

</br></br>

## 2b) BFC80000

1. In Binaer umwandeln  1|01111111|10010000000000000000000
2. Fraction: 10010000000000000000000, Mantisse 1.1001
3. Exponent: 01111111 = 127 - 127 = 0
4. Vz-Bit 1 -> -
5. Normalisierung -1.1001
6. In Dezimal umwandeln -1.1001 =  
1/2+1/16 = 0.5625  
-1.5625  

## 2c) C18A0000

1. In Binaer umwandeln  1|10000011|00010100000000000000000
2. Fraction: 00010100000000000000000, Mantisse 1.000101
3. Exponent: 10000011 = 131 - 127 = 4
4. Vz-Bit 1 -> -
5. Normalisierung -10001.01
6. In Dezimal umwandeln -10001.01 =  
1/4 = 0.25  
-17.25

</br></br>

---

## 3 3EE00000 + 3F880000

1. In Binaer umwandeln  0|01111101|11000000000000000000000
2. Fraction: 1100000000000000000000, Mantisse 1.11
3. Exponent: 01111101 = 125 - 127 = -2
4. Vz-Bit 0 -> +
5. Normalisierung 1.11 * 2^-2 -> 0.0111

0.0111

1. In Binaer umwandeln  0|01111111|00010000000000000000000
2. Fraction: 00010000000000000000000, Mantisse 1.0001
3. Exponent: 01111111 = 131 - 127 = 0
4. Vz-Bit 0 -> +
5. Normalisierung 1.0001

1.0001  

</br></br>

1.0001  
0.0111
1.1000

0011|1111|1100|0000|0000|0000|0000|0000
3FC0000

---

# Ueberschuss-3-Code :)


|UTF-8 Byte(s)| Code point| Looks like|
|---|---|---|---|
|c3 9c| U+dc| Ü|
|62|U+62|b|
|65|U+65|e|
|72|U+72|r|
|73|U+73|s|
|63|U+63|c|
|68|U+68|h|
|75|U+75|u|
|c3 9f|U+df|ß|
|2d|U+2d|-|
|33|U+33|3|
|2d|U+2d|-|
|43|U+43|C|
|6f|U+6f|o|
|64|U+64|d|
|65|U+65|e|
|20|U+20| |
|e2 98 ba|U+263a| ☺ |

36 UNICODE  
22 UTF-8  
14
