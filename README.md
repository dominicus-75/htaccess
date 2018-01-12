# htaccess

- www. előtaggal érkező kérelmekből eltávolítja az előtagot, hogy az oldalt a kereső motorok ne tekintsék duplikált tartalomnak
- meggátolja a képlopást (hotlink)
- kiszűri a kérelemből az SQL-injektálást
- kiszűri a kérelemből az esetleges javascript utasításokat
- válasz nélkül elutasítja a nem GET vagy POST metósussal, illetve nem HTTP 1.0/1 protokol szerinti kérelmeket
- nagyjából 1800 azonosított robotot tílt
- beállítja, hogy az egyes fájltípusokhoz a büngészőben mennyi lejárati idő tartozzon (cache)
- engedélyezi a válasz (response) gzip tömörítését
- minden kérelmet az index.php-ra irányít át
- gyógyítja a rákot (ja, azt nem).
