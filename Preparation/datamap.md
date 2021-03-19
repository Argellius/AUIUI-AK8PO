# 1. Skupina
- zkratka_predmetu - string - AK8PO
- Rocnik - int - 4
- Semestr - Int - Id do tabulky Semestr - LS, ZS
- Počet studentů - int - 1
- Forma studia - int - Id do tabulky Forma studia - Prezenční, Kombi
- Typ studia - int - Id do tabulky Typ Studia - Bc, Ing, Mgr
- Jazyk - Int - Id do tabulky Jazyk
# 2. Zaměstnanec
- krestni_jmeno: string - Adam
- prijmeni: string - Cerny
- soukromý_email: string - adam@utb.cz
- pracovni_email: string - adam@utb.cz
- doktorat: byte (Boolean) - True
- typ_uvazku: Double - 0 - 1 - 0.56
- Štítek - Int - Id do tabulky Štítky
# 3. Predmet
- Zkratka - string - Ak8AJ
- Počet týdnů - int - 14
- Počet hodin přednášek - int - 1
- Počet hodin cvičení - int - 2
- Počet hodin seminářů - int - 2
- Jazyk - Id do tabulky Jazyky
- Velikost třídy - Int - 20

# 4. Pracovni štítek
- Název - string - Cvičení předmětu Ak8AJ
- Predmet - string - AK8AJ
- Zamestnanec - int - Id do tabulky Zamestnanec
- Typ stitku - int - Id do tabulky typ stitku
- Počet studentů - int - 10
- Počet hodin - int - 10
- Počet týdnů - int - 10
- Jazyky - Int - Id do tabulky Jazyky

# 5. Váhy pracovních bodů
-- Zkopírováno z moodle
-- DODĚLAT, DOMYSLET
//TODO

- (Doplňující model, který se po spuštění aplikace načte z XML, nebo databáze, někam do GlobalConfig.)

- Hodina přednášky – double – 1,8
- Hodina cvičení – double – 1,2
- Hodina semináře – double – 1,2
- Hodina přednášky anglicky – double – 2,4
- Hodina cvičení anglicky – double – 1,8
- Hodina semináře anglicky – double – 1,8
- Udělení jednoho zápočtu – double – 0,2
- Udělení jednoho klasifikovaného zápočtu – double – 0,3
- Udělení jedné zkoušky – double – 0,4
- Udělení jednoho zápočtu anglicky – double – 0,2
- Udělení jednoho klasifikovaného zápočtu anglicky – double – 0,3
- Udělení jedné zkoušky – anglicky - double – 0,4
