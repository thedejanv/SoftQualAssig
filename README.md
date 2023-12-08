# SoftQualAssig
simple calculator written in Java; supports addition, subtraction, multiplication and division

Broj linija koda (LOC):
File "Licence" = 0. Ovde nema linija koda u "užem smislu", jer se u potpunosti sastoji od teksta koji se odnosi na licencu, dakle te linije ne doprinose funkcionalnosti programa. Zato bih rekao da je LOC=0.
File "Start.java" = 19
File "Calculator.java" = 129 (brojao sam sve linije osim praznih i 5 zakomentarisanih)
Total LOC = 0 + 19 + 129 = 148

Ciklomatska i kognitivna složenost za metodu Evaluate Expression:
Ciklomatska složenost: E = 12, N = 10; CYC = 12 − 10 + 2 = 4
Kognitivna složenost: Jedno if račvanje (i kasnije još dva "ugnježđena"), dve petlje, upućivanje na operations.tostring + pozivanje na Calculate metodu

Ciklomatska i kognitivna složenost za metodu Calculate:
Ciklomatska složenost: E = 15, N = 13; CYC = 15 − 13 + 2 = 4
Kognitivna složenost: 7 IF račvanja (plus dva "ugnježđena")

Zapažanja za Calculator.java
- Kao da su operacije (+, -, *, /) dva puta opisane
- U slučaju greške, deluje da je poruka samo "Error" bez objašnjenja
- -Verovatno je bolje toString umesto ToSTring
