# Vigenere Cipher in go lang
----------------------------

## Cryptography and cryptanalysis
----------------------------

#### Famous Cryptography Methods
----------------------------
Code makers are those who use cryptography to hide the meaning of the messages.

####  Cryptography by transposition
----------------------------
Transposition is the art of cryptography in which the letter is replaced from its original position. There is no cipher and the plaintext is visible, but the order of the text is messed up.

#### Rail Fence Transposition
----------------------------
Take the plain text, arrange the alternative letters on a top and a bottom line, the bottom line should be placed at the end of the top line. This transposition method can be modified by dividing the alternating alphabets into more than two lines and joining the lines at the end of the top line.

Example

Plain-text: a quick brown fox

Obere Zeile:   A  U  C  B O N O  
Untere Zeile:    Q  I    K R W F X

verschlüsselter Text: A  U  C  B O N O Q  I   K R W F X
Referenz: Singh, S. (2009). The code book: the science of secrecy from ancient Egypt to quantum cryptography (1st ed.). Bridgewater, NJ: Distributed by Paw Prints / Baker & Taylor.

#### Monoalphabetische Substitutions-Digit
----------------------------
A substitution cipher that can replace the plain-text letters and assign each plain-text letter to one of the 25 different Caesar cipher alphabets. Monoalphabetic ciphers contain either letters or symbols, or a mixture of both.

Referenz: Singh, S. (2009). The code book: the science of secrecy from ancient Egypt to quantum cryptography (1st ed.). Bridgewater, NJ: Distributed by Paw Prints / Baker & Taylor.

#### Caesar shift cipher
----------------------------
Take the plain text, replace each letter of the plain text with an alphabet that is three places lower in that language's alphabetical order. This means a Caesar shift of 3, and there are 25 different ciphers available.

Example:
Plain Alphabet: A B C D E F G H I J K L M Cipher Alphabet: N O P Q R S T U V W X Y Z

Plaintext: a quick brown fox jumps over the lazy dog Cipher-text: N DHVPX OEBJA SBK WUZCF BIRE GUR YNML QBT

Referenz: Singh, S. (2009). The code book: the science of secrecy from ancient Egypt to quantum cryptography (1st ed.). Bridgewater, NJ: Distributed by Paw Prints / Baker & Taylor

#### "Atbash" Hebrew substitution cipher
----------------------------
Atbash is a monoalphabetic substitution cipher originally used to encode the Hebrew alphabet.

Take a plain text, note the position of each alphabet from the beginning of the alphabet sequence and replace each alphabet with the letter in the same position but from the end of the alphabet sequence

Example:

Plain-Text Cipher-Text A Z B Y C X D W E V F U

Referenz: Singh, S. (2009). The code book: the science of secrecy from ancient Egypt to quantum cryptography (1st ed.). Bridgewater, NJ: Distributed by Paw Prints / Baker & Taylor.

#### Homophone Substitutions-Chiffre
----------------------------
A number from 0 to 99 is selected as a cipher alphabet to represent an alphabet in plain text. Each letter in plain text is assigned one or more cipher alphabets; the number of cipher alphabets can depend on the frequency of the alphabet in the respective language. We can think of all the two-digit numbers that correspond to the plaintext letter "a" as effectively representing the same sound in the ciphertext. However, many types of such homophone shift ciphers are possible.

Homophonic substitution ciphers are also a type of monoalphabetic ciphers, since each cipher alphabet corresponds to the same alphabet in plain text.

Referenz: Singh, S. (2009). The code book: the science of secrecy from ancient Egypt to quantum cryptography (1st ed.). Bridgewater, NJ: Distributed by Paw Prints / Baker & Taylor.

#### The Spanish Strip Cipher
----------------------------
The Spanish stripe cipher is a variant of the homophonic substitution cipher, in which a plaintext letter not only represents one ciphertext character, as in the monoalphabetic substitution cipher, but can also represent several.

Referenz: Alberto , L., & Sanguino, B. (2013). Analyzing Spanish Civil War Ciphers by Combining Combinatorial and Statistical Methods.Chair for Embedded Security – Prof. Dr.-Ing. Christof Paar Advisor: Dr. Gregor Leander

#### Polyalphabetic Ciphers
----------------------------
A polyalphabetic cipher assigns more than one cipher alphabet to each plain-text letter, and a cipher alphabet could also represent two different letters in the same plain-text.

Example: Le Vigenere Cipher

Referenz: Singh, S. (2009). The code book: the science of secrecy from ancient Egypt to quantum cryptography (1st ed.). Bridgewater, NJ: Distributed by Paw Prints / Baker & Taylor.

#### Crypto-Analysis
----------------------------

Code breakers are those who use cryptanalysis to recover the meaning of messages from the ciphertext. Cryptography can be achieved through substitution or transposition. Cryptanalysis can be achieved by frequency analysis of the letters of a certain language.

Instead of using frequency analysis for letters, the frequency of syllables occurring in plain text can also be taken into account

A digraph is a pair of two letters and in English there are 26 letters, so 26*26 =676 different pairs are possible. Frequency analysis can also be applied to digraphs.

Referenz: Singh, S. (2009). The code book: the science of secrecy from ancient Egypt to quantum cryptography (1st ed.). Bridgewater, NJ: Distributed by Paw Prints / Baker & Taylor.


