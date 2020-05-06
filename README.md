## Vigenere
Vigenere Cipher in go lang

### Kryptographie und Kryptoanalyse

## Kryptographie


Code-Maker sind diejenigen, die Kryptographie verwenden, um die Bedeutung der Nachrichten zu verbergen.


## Kryptographie durch Transposition:
Die Transposition ist die Kunst der Kryptographie, bei der der Brief von seiner ursprünglichen Position aus ersetzt wird. Es gibt keine Chiffre und der Klartext ist sichtbar, aber die Reihenfolge des Textes ist durcheinander.

## Rail Fence Transposition:

Nehmen Sie den Plain-text, ordnen Sie die alternativen Buchstaben auf einer oberen und einer unteren Zeile an, die untere Zeile ist am Ende der oberen Zeile anzubringen. Diese Transposition Methode kann modifiziert werden, indem man die abwechselnd erscheinenden Alphabete in mehr als zwei Zeilen teilt und die Zeilen am Ende der oberen Zeile verbindet.

Beispiel

	Plain-text: a quick brown fox
	
	Obere Zeile:   A  U  C  B O N O  
	Untere Zeile:    Q  I    K R W F X

	verschlüsselter Text: A  U  C  B O N O Q  I   K R W F X

Referenz: Singh, S. (2009). The code book: the science of secrecy from ancient Egypt to quantum cryptography (1st ed.). Bridgewater, NJ: Distributed by Paw Prints / Baker & Taylor.


## Monoalphabetische Substitutions-Chiffre:

Eine Substitutionschiffre, die die plain-text buchstaben ersetzen und jeden plain-text buchstaben einem der 25 verschiedenen Caesar-Chiffre-Alphabete zuordnen kann.Monoalphabetische Chiffren enthalten entweder Buchstaben oder Symbole oder eine Mischung aus beiden.

Referenz: Singh, S. (2009). The code book: the science of secrecy from ancient Egypt to quantum cryptography (1st ed.). Bridgewater, NJ: Distributed by Paw Prints / Baker & Taylor.


## Cäsar-Verschiebungs-Chiffre:
Nehmen Sie den Plain-Text, ersetzen Sie jeden Buchstaben des Plain-Textes durch ein Alphabet, das in der alphabetischen Reihenfolge dieser Sprache drei Stellen weiter unten liegt. Dies bedeutet eine Caesar-Verschiebung von 3, und es sind 25 verschiedene Chiffren verfügbar.

Beispiel:    
Plain Alphabet:	A B C D E F G H   I   J   K L M 
Cipher Alphabet:     N O P Q R S T U  V  W  X Y Z

Plaintext: 	a  quick     brown   fox    jumps    over   the    lazy    dog
Cipher-text:	N DHVPX OEBJA SBK WUZCF BIRE GUR YNML QBT

Referenz: Singh, S. (2009). The code book: the science of secrecy from ancient Egypt to quantum cryptography (1st ed.). Bridgewater, NJ: Distributed by Paw Prints / Baker & Taylor


## "Atbash" Hebräische Substitutions-Chiffre:

Atbash ist eine monoalphabetische Substitutions-Chiffre, die ursprünglich zur Verschlüsselung des hebräischen Alphabets verwendet wurde.

Nehmen Sie einen Klartext, notieren Sie die Position jedes Alphabets vom Anfang der Alphabet Folge und ersetzen Sie jedes Alphabet durch den Buchstaben an der gleichen Position, aber vom Ende der Alphabet Folge

Beispiel:

Plain-Text
Cipher-Text
A
Z
B
Y
C
X
D
W
E
V
F
U

Referenz: Singh, S. (2009). The code book: the science of secrecy from ancient Egypt to quantum cryptography (1st ed.). Bridgewater, NJ: Distributed by Paw Prints / Baker & Taylor.


## Homophone Substitutions-Chiffre:

Eine Zahl von 0 bis 99 wird als Chiffre-Alphabet ausgewählt, um ein Alphabet im Klartext darzustellen. Jedem Buchstaben im Klartext werden ein oder mehrere Chiffre-Alphabete zugeordnet, die anzahl der Chiffre-Alphabete  von der Häufigkeit des Alphabets in der jeweiligen Sprache abhängen können. Wir können uns alle zweistelligen Zahlen, die dem Klartext Buchstaben "a" entsprechen, so vorstellen, dass sie im Chiffretext effektiv denselben Klang repräsentieren. Es sind aber viele arten von solche Homophon Verschiebechiffren möglich.


Homophone Substitutions-Chiffren sind auch eine Art monoalphabetische Chiffren, da jedes Chiffre-Alphabet dem gleichen Alphabet im Klartext entspricht.

Referenz: Singh, S. (2009). The code book: the science of secrecy from ancient Egypt to quantum cryptography (1st ed.). Bridgewater, NJ: Distributed by Paw Prints / Baker & Taylor.

## The Spanish Strip Cipher:

Die spanische Streifen-Chiffre ist eine Variante der homophonen Substitutions-Chiffre, bei der ein Klartext Buchstabe nicht nur ein Chiffretext Zeichen abbildet, wie bei der monoalphabetischen Substitutions-Chiffre, sondern auch mehrere abbilden kann.

Referenz: Alberto , L., & Sanguino, B. (2013). Analyzing Spanish Civil War Ciphers by Combining Combinatorial and Statistical Methods.Chair for Embedded Security – Prof. Dr.-Ing. Christof Paar Advisor: Dr. Gregor Leander

## Polyalphabetic Ciphers:
Eine polyalphabetische Chiffren ordnen jedem plain-text buchstaben mehr als ein Chiffre-Alphabet zu, und auch ein Chiffre-Alphabet könnte zwei verschiedene Buchstaben im gleichen plain-text darstellen.

Beispiel:
Le Vigenere Cipher

Referenz: Singh, S. (2009). The code book: the science of secrecy from ancient Egypt to quantum cryptography (1st ed.). Bridgewater, NJ: Distributed by Paw Prints / Baker & Taylor.

## Kryptoanalyse

Code-Knacker sind diejenigen, die die Kryptoanalyse verwenden, um die Bedeutung der Nachrichten aus dem Chiffretext wiederherzustellen.
Kryptographie kann durch Substitution oder Transposition erreicht werden.
Die Kryptoanalyse kann durch eine Häufigkeitsanalyse der Buchstaben einer gewissen Sprache erreicht werden. 


Anstatt eine Häufigkeitsanalyse für Buchstaben anzuwenden, kann auch die Häufigkeit der im Klartext vorkommenden Silben berücksichtigt werden


Ein Digraph ist ein Paar von zwei Buchstaben und im Englischen gibt es 26 Buchstaben, so dass 26*26 =676 verschiedene Paare möglich sind. Die Frequenzanalyse kann auch auf Digraphen angewendet werden. 



Referenz: Singh, S. (2009). The code book: the science of secrecy from ancient Egypt to quantum cryptography (1st ed.). Bridgewater, NJ: Distributed by Paw Prints / Baker & Taylor.



