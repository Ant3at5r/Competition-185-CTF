# Competition-185-CTF

CTF for CPT 185

## <u> OSINT</u>

### Question 1

What does OSINT stand for ?

` Open source intelligence`

### Question 2

*The Army Reserve Cyber Protection Brigade (ARCPB) *

The Army Reserve Cyber Protection Brigade (ARCPB) was formed

`2016`

### Question 3

*Military Cyber Warrant Officers*

When was the Cyber warrant formally created ?

ANSWER format

MONTH DAY, YEAR

`September 1, 2014`

### Question 4

*Re named*

in what year was Fort Gordan renamed Fort Eisenhower ?

`2023`

### <u>CIPHER</u>

### Question 6

*ASCII*

For the following cipher (ASCII coding), determine the decoded string: %6E%65%77%73%70%61%70%65%72

Hint:

> a (%61) b (%62) c (%63) d (%64) e (%65) f (%66) g (%67) h (%68) i (%69) j (%6A) k (%6B) l (%6C) m (%6D) n (%6E) o (%6F) p (%70) q (%71) r (%72) s (%73) t (%74) u (%75) v (%76) w (%77) x (%78) y (%79) z (%80)

`newspaper`

### Question 7

*Letter Bars*

Solve this Letter Bars cipher: FYHVYHZ YFK XHFAA ZHFL YAFK ZX

> The Letter Bars alphabet is:
> I V H E ZX YZ ZYI NTK YFK HFE ZHFL YAFK KYYFI XHFAA ANNYF NKWNN KTYZZA ANHKKN AIYHYKK FYHVYHZ AYYZZKY NZFMNFA KLHNFKZA AHYHAHKK AFHFHHZAI FHTZNYZNK

`tinkle`

### Question 8

*Gronsfield cipher*

Solve this Gronsfeld cipher: wsrikuzpu and a key of 713662

> | The Gronsfeld cipher is similar to the Vigenere cipher, but we use numerics values to perform the shift of letters, rather than a character key. For example, "applecore" with a key of "12345" becomes:<br>applecore<br>brspjdqui<br>and where 'a' is shifted by 1 to get a 'b', and 'p' shifted by 2 gives an 'r'. |     |
> | --- | --- |

`processor`

### Question 9

*Solitaire cipher*

Solve this Solitaire cipher: tfgvnskt and a card shuffle of {1 37 19 3 6 10 23 15 52 13 9 40 16 31 5 51 4 24 41 39 30 7 50 38 42 17 49 28 14 21 36 48 35 18 20 29 46 8 33 34 26 2 27 44 25 12 11 47 43 22 45 32}

> | With a card shuffle of {10 42 5 48 11 12 38 6 21 40 34 18 13 52 39 32 28 50 22 30 27 41 46 31 37 43 36 29 2 16 3 26 35 49 51 25 8 17 7 20 15 14 23 9 19 24 47 44 45 1 4 33}, then we have 10 for the first card and map 'a' to 'k' (0+10=10). We then have 42 for the second card, and where 'p' is represented by 15, and so we get get 57. We now take 57 (mod 26), we get 5, and which is 'f'. In Python, 57 (mod 26) is simply 57 % 26. The result is:<br> Plaintext: a p p l e c o r e<br> 0 15 15 11 4 2 14 17 4<br> Card: 10 42 5 48 11 12 38 6 21<br> -------------------------------------<br> 10 57 20 59 15 14 52 23 25<br> (mod 26) 10 5 20 7 15 14 0 23 25<br> k f u h p o a x z<br> The mapping is:<br> a b c d e f g h i j k l m n o p q r s t u v w x y z<br> 0 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 21 22 23 24 25<br> To define a value on the cards for the cipher, we could use:<br> Clubs: Ace, 2,... 10, J, Q, K becomes to 1, 2, ... 10, 11, 12, 13.<br> Diamonds: Ace, 2, ... ,10, J, Q, K becomes 14, 15, ... 23, 24, 25, 26.<br> Hearts: Ace, 2, ... 10, J, Q, K becomes 27, 28, ... 36, 37, 38, 39.<br> Spades: Ace, 2, ... 10, J, Q, K becomes 40, 41, ...49, 50, 51, 52. |     |
> | --- | --- |

`sunshine`

### Question 10

*PigLatin*

Solve this PigLatin cipher: reetay

> With PigLatin, we have two rules:
> If the word starts with a vowel (AEIOU), we add a 'way' onto the sentence, so that 'apple' becomes 'appleway';
> If the word start with one or more consonants, we move them to the word and add 'ay', so that 'treat' becomes 'reattay'.

`tree`

### Question 11

*Javanais cipher*

Solve this Javanais cipher: spavadave

> With the Javanais, we insert an 'av' between a vowel and a consonant, and also insert 'av' if a word starts with a vowel

`spade`

### Question 12

*Malespin cipher*

Solve this Malespin cipher: grenca

> With the Malespin, we swap A -- E, B -- T, F -- G, I -- O, and M -- P

`france`

### Question 13

*Keyboard cipher*

Solve this Keyboard cipher: [rst;

> A Keyboard alphabet for a QWERTY keyboard can move the letters by one space to the right: 
> snvfrghjokl;,mp[wtdyibecux

`pearl`

### Question 14

*Keyboard cipher*

Solve this Keyboard cipher: dewbxg

> A Keyboard alphabet for a QWERTY keyboard can move the letters by one space to the left: 
> \vxswdfguhjknbio]earycqzt/

`french`

### Question 15

*Gold-Bug cipher*

Solve the gold bug cipher to recover the plaintext: ¶‡6-8

> The Gold-Bug cipher was included in a short story by Edgar Allan Poe and which was published in 1843. It tells the tale of William Legrand and how he was bitten by a gold-colored bug. The mapping is:
> abcdefghijklmnopqrstuvwxyz
> 52-†81346,709*‡.$();?¶]¢:[
> In the book he writes:
> Here Legrand, having re-heated the parchment, submitted it to my inspection. The following characters were rudely traced, in a red tint, between the death's-head and the goat:
> 53‡‡†305))6*;4826)4‡.)4‡);806*;48†8¶60))85;1‡(;:‡*8†83(88)5*†;
> 46(;88*96*?;8)*‡(;485);5*†2:*‡(;4956*2(5*—4)8¶8*;4069285);)6†8
> )4‡‡;1(‡9;48081;8:8‡1;48†85;4)485†528806*81(‡9;48;(88;4(‡?
> 34;48)4‡;161;:188;‡?;
> This is translated as:
> 5 - A
> 3‡‡† - good
> 305)) - glass
> 6* - in
> ;48 - the

`voice`

### Question 16

*ADFGVX cipher*

Solve the ADFGVX cipher to find the plaintext of: DV VG VV GV GD AX

`airgun`

### Question 17

*Bacon cipher*

What is the plain text for the following Bacon cipher: BAAAA AABAA BAABA ABAAA ABBAA AAAAA

> a AAAAA g AABBA n ABBAA t BAABA
> b AAAAB h AABBB o ABBAB u-v BAABB
> c AAABA i-j ABAAA p ABBBA w BABAA
> d AAABB k ABAAB q ABBBB x BABAB
> e AABAA l ABABA r BAAAA y BABBA
> f AABAB m ABABB s BAAAB z BABBB

`retina`

### Question 18

*Polybius cipher*

What is the plain text for the following Polybius cipher: 21 11 24 34 45

`faint`

### Question 19

*Dvorak cipher*

What is the plain text for the Dvorak cipher of: LCNRY

> Plain: abcdefghijklmnopqrstuvwxyz
> Cipher: axje.uidchtnmbrl'poygk,qf;

`pilot`

## Question 20

*Atbash cipher*

What is the Atbash cipher for the word: HSVW

> Plain: abcdefghijklmnopqrstuvwxyz
> Cipher: ZYXWVUTSRQPONMLKJIHGFEDCBA

`Shed`

### Question 21

*Rot13 cipher*

What is the plain text for the Rot13 cipher of: FUBJTEBHAQ

> Plain: abcdefghijklmnopqrstuvwxyz
> Cipher: NOPQRSTUVWXYZABCDEFGHIJKLM

`showground`

### Question 22

*ROT47 cipher*

What is the ROT47 cipher for: barkingupthewrongtree

> Plain: abcdefghijklmnopqrstuvwxyz 1234567890!.:,;'
> Cipher: 23456789:;<=>?@ABCDEFGHIJK `abcdefgh_P]i[jV

`32C<:?8FAE96HC@?8EC66`

### Question 23

*tap cipher*

What is the plain text for the following tap cipher: .. . ..... . ... .... ... .... ..... .....

> The tap cipher uses a Polybius mapping, and where we tap (.) out the row and then tap the column count:
>  For example:
>  .... ..... . . .... .... .... ..... . .....
>  T A S T E

`funny`

### Question 24

*Baudot code*

What the plaintext for the following Baudot code: 001110101011010000010110010000

> | The coding is:<br> 0 1 2 3 4 5 6 7 8 9<br> '*' 'E' '\n' 'A' ' ' 'S' 'I' 'U' '\r' 'D'<br> 10 11 12 13 14 15 16 17 18 19<br> 'R' 'J' 'N' 'F' 'C' 'K' 'T' 'Z' 'L' 'W'<br> 20 21 22 23 24 25 26 27 28 29<br> 'H' 'Y' 'P' 'Q' 'O' 'B' 'G' '' 'M' 'X',<br> Binary Letter Figure<br> 00000 Null Null<br> 00001 E 3<br> 00010 LF LF<br> 00011 A –<br> 00100 ' ' ' '<br> 00101 S Bell<br> 00110 I 8<br> 00111 U 7<br> 01000 CR CR<br> 01001 D <br> 01010 R 4<br> 01011 J '<br> 01100 N ,<br> 01101 F !<br> 01110 C :<br> 01111 K (<br> 10000 T 5<br> 10001 Z "<br> 10010 L )<br> 10011 W 2<br> 10100 H #<br> 10101 Y 6<br> 10110 P 0<br> 10111 Q 1<br> 11000 O 9<br> 11001 B ?<br> 11010 G &<br> 11011 Shift to figures <br> 11100 M .<br> 11101 X /<br> 11110 V ;<br> 11111 Shift to letters |     |
> | --- | --- |

`urgent`

### Question 25

*Morse code*

For the following Morse code, what is the plaintext: (·—) (··—) (—··) (··) (— — —)

> | A(·—) B(—···)<br>C(—·—·) D(—··)<br>E(·) F(··—·)<br>G(— —·) G(····)<br>I(··) J(·— — —)<br>K(—·—) L(·—··)<br>M(— —) N(—·)<br>O(— — —) P(·— —·)<br>Q(— —·—) R(·—·)<br>S(···) T(—)<br>U(··—) V(···—)<br>W(·— —) X(—··—)<br>Y(—·— —) Z(— —··) | 0   |     |
> | --- | --- | --- |

`audio`

### Question 26

*Homophonic cipher*

A Homophonic cipher uses several codes for each plaintext character. For the homomorphic cipher given below, which is the plaintext for the cipher of: 16 22 48 58 20 69 31 76

> a b c d e f g h i j k l m n o p q r s t u v w x y z
>  07 11 17 10 25 08 44 19 02 18 41 42 40 00 16 01 15 04 06 05 13 22 45 12 55 47
>  31 64 33 27 26 09 83 20 03 81 52 43 30 62 24 34 23 14 46 93
>  50 49 51 28 21 29 86 80 61 39 56 35 36  
>  63 76 32 54 53 95 88 65 58 57 37  
>  66 48 70 68 89 91 71 59 38  
>  77 67 87 73 94 00 90 60  
>  84 69 96 74  
>  72 78  
>  75 92  
>  79  
>  82 
> 85

`overhead`

### Question 27

*Bifid cipher*

For the Bifid cipher, for a cipher word of the following determine the plaintext: lmewqs

> First we start with a grid:
>  1 2 3 4 5
>  1 B G W K Z
>  2 Q P N D S
>  3 I O A X E
>  4 F C L U M
>  5 T H Y V R
>  Next we look up the grid, and the arrange the two character values into two rows. For example is we have a plaintext of "marylan", then "m" is "4" and "5", so we place "4" in the first row, and "5" in the second row, and continue to do this for all the letters:
>  maryland
>  43554322
>  53533334
>  Next we read along the rows and merge, to give:
>  43 55 43 22 53 53 33 34
>  Next we convert them back to letters from the grid:
>  L R L P Y Y A X
>  Let’s try the reverse, with DXETE. For we look up the grid to get:
>  24 34 35 51 35
>  We can then put then into rows to give:
>  2 4 3 4 3
>  5 5 1 3 5
>  This gives us 25 (s) 45 (m), 31 (i) 43 (l) 35 (e) – which is smile.

`factor`

### Question 28

*grey cipher*

What is gray cipher code for the value of 2?

> | With a Gray cipher each binary value in a sequence differs by just one bit. Take a value of i, and calculate i EX-OR (i >> 1), and where >> is a shift bit right. For example, if we have 4 (0100), we have:<br> i 0100<br> EX-OR 0010<br> ----<br> 0110 |     |
> | --- | --- |

`11`

### Question 29

*Straddling cipher*

For the following Straddling cipher, what is the plain text: 7 3 5 22 4 29

> | 0 1 2 3 4 5 6 7 8 9<br> E T A O N R I S<br> 2 B C D F G H J K L M<br> 6 P Q / U V W X Y Z . |     |
> | --- | --- |

`random`

### Question 30

*3-rail cipher*

For the follow cipher, we use a 3-rail code (an example given below). Which is the plaintext for the following 3-rail cipher code: FHLGT I

> 'WE ARE DISCOVERED. FLEE AT ONCE', gives:
>  W . . . E . . . C . . . R . . . L . . . T . . . E
>  . E . R . D . S . O . E . E . F . E . A . O . C .
>  . . A . . . I . . . V . . . D . . . E . . . N . .
>  to give:
>  WECRL TEERD SOEEF EAOCA IVDEN

`flight`

### Question 31

*Pollux cipher*

The Pollux cipher, we use Morse code (see below) to determine a code (see below). Which is the plaintext for the following Pollux cipher: 80749118250609

> To determine a code, and then map a dot, dash or seperator with the following:
>  Dot - 0, 7 or 
> Dash - 1, 8 or 5
>  Seperator - 2, 9, 6 or 3
>  If we take a code of "784067897459184640779", we can determine the following:
>  784067897459184640779
>  .-.. .- ..- --. .... 
> L A U G H  
>  For example "GE" becomes "— — ·" and "·", so we can then encode to 180 2 7 9 to give 180279.
>  Morse code:
>  A(·—)
>  B(—···
>  C(—·—·)
>  D(—··)
>  E(·)
>  F(··—·)
>  G(— —·)
>  H(····)
>  I(··)
>  J(·— — —)
>  K(—·—)
>  L(·—··)
>  M(— —)
>  N(—·)
>  O(— — —)
>  P(·— —·)
>  Q(— —·—)
>  R(·—·)
>  S(···)
>  T(—)
>  U(··—)
>  V(···—)
>  W(·— —)
>  X(—··—)
>  Y(—·— —
>  Z(— —··)

`bone`

### Question 32

*Fractional cipher*

The following Fractional cipher (see below), determine the plaintext: ETXGLBGPJTC

> | "Hello World" is Morse Code is:<br> .... . .-.. .-.. --- / .-- --- .-. .-.. -..<br> H E L L O SPACE W O R L D<br> We can then make this into a string with an 'x' between characters:<br> Plain text: H e l l o w o r l d<br> Morse string: ....x.x.-..x.-..x---xx.--x---x.-.x.-..x-..<br> We can now use three-character mappings to convert them back to text:<br> ['...', '..-', '..x', '.-.', '.--', '.-x', '.x.', '.x-', '.xx', '-..', '-.-', '-.x', '--.', '---', '--x', '-x.', '-x-','-xx', 'x..', 'x.-', 'x.x', 'x-.', 'x--', 'x-x', 'xx.', 'xx-']<br> <br> This mapping is:<br> A B C D E F G H I J K L M N O P Q R S T U V W X Y Z<br> . . . . . . . . . - - - - - - - - - x x x x x x x x<br> . . . - - - x x x . . . - - - x x x . . . - - - x x<br> . - x . - x . - x . - x . - x . - x . - x . - x . -<br> which will map to "ABCDEF...Z". Next we can convert them back with:<br> AGTCDHOTQODTCJ<br> For "Peter piper picked " we get:<br> .--.x.x-x.x.-.xx.--.x..x.--.x.x.-.xx.--.x..x-.-.x-.-x.x-..xx<br> P e t e r ' ' p i p e r' ' p i c k e d ' ' <br> Standard Morse code<br> E . S ... H .... B -... 1 .---- period .-.-.-<br> T - U ..- V ...- X-..- 2 ..--- comma --..--<br> I .. R .-. F ..-. C-.-. 3 ...-- query .-.-.-<br> A .- W .-- L .-.. Y --.- 4 ....- colon ---...<br> N -. D -.. P .--. Z --.. 5 ..... s/colon -.-.-.<br> M -- K -.- J .--- Q --.- 6 -.... dash -....-<br> G --. 7 --... slash -..-.<br> O --- 8 ---.. equals -...-<br> 9 ----.<br> 0 ----- |     |
> | --- | --- |

`waterfall`

### Question 33

*column cipher*

With the column cipher we lay our plain text in columns, and then use a column key, and reconstruct the columns: Using key of 10342, what is the plaintext for "hraswraswwweswwehthesth iitaiit cscrssc "

> | With the column cipher we lay our plain text in columns, and then use a column key, and recontruct the colums. If we use an order of column 3, 1, 4, 2 and 0, with a message of "whichwristwatchesareswisswristwatches", we get:<br> 31420<br> -----<br> which<br> wrist<br> watch<br> esare<br> swiss<br> wrist<br> watch<br> es <br> We now rearrange the columns back in order:<br> 0 1 2 3 4<br> ['h', 'h', 'c', 'w', 'i']<br> ['t', 'r', 's', 'w', 'i']<br> ['h', 'a', 'c', 'w', 't']<br> ['e', 's', 'r', 'e', 'a']<br> ['s', 'w', 's', 's', 'i']<br> ['t', 'r', 's', 'w', 'i']<br> ['h', 'a', 'c', 'w', 't']<br> [' ', 's', ' ', 'e', ' ']<br> The result is then:<br> Cipher: hthesth hraswrascscrssc wwweswweiitaiit | 0   |     |
> | --- | --- | --- |

`whichwristwatchesareswisswristwatches`

## <u>Malware</u>

### Question 34

*Supply Chain Madness 1*

If you aren't a SciFi nerd, you may have a hard time shifting through the sands of this malware that hit repositories arcoss the world.

`Shai-hulud`

### Question 35

*Supply Chain Madness 1.2*

If someone's repo accidentally got infected with this malware, what is the primary IOC file that would show up to indicate a compromise?

`truffleSecrets.json`

### Question 38

*Supply Chain Madness 2!*

A particular set of library modules have been in the news for several months. What is this library called?

`NPM`

### Question 39

*Supply Chain Madness 2.1*

If you know what the first part of this challenge was, then you should know what the primary way this got compromised.

Name the methodology that led to this supply chain fiasco.

`phishing`

### Question 40

*Supply Chain Madness 3.0*

This VERY recent vulnerability just got released and could affect 30-40% of the current public internet. What is this code library that is used?

Hint: The CVE was considered a 10......

`ReactJS`

### Question 41

*Supply Chain Madness 3.1*

What was Impact from this vulnerability? What could happen to vulnerable versions?

`RCE` or `remote code execution`

## <u> Incident Response</u>

### Question 42

*Stoppin the bad guys*

Think back to the basics of Incident Response; Let's say you have a bad guy that is DDOSIng your environment. You have the IP addresses and keep trying to block them, but new ones pop up constantly. There is a certain triangle used to teach methodology on what to use and determine in order to stop the bad guys.

What should you, as an incident responder, look for to determine the BEST way to stop an adversary? Hint: It's on top of the pyramid...

`TTPs`

### Question 36 (hidden)

Congratulations on starting your journey down the Incident Response path! But first, you need to understand the BASICS.

What is the standard Cyber Kill Chain that is generally used today?

``
