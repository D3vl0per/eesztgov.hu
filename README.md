# A weboldal nem működik, mivel nem tetszett a fed-nek a domain. Sokáig élt legalább. 
## eesztgov.hu | Nem hivatalos digitális igazolvány ellenőrző oldal
Low-effort, backend nélküli ellenörző weboldal az digitális vakcinaigazoláshoz  

Főbb funkciók:
- Az oldal betöltése után nem kell internet
- Minden a böngészőben történik
- Legtöbb esetben működik is a QR kód olvasó
- A legtöbb eszközön működik

### Hogyan működik?
A QR kód beolvasása után feldolgozza a kapott üzenetet és ellenőrzi a publikus kulccsal, hogy a digitális aláírás érvényes-e.  
  
### Működik a sima plasztik kártyával is?
Nem  
  
### Mi az az RFC7519??
JSON Web Token avagy JWT
  
### Milyen JWT-t használ az EESZT validáló alkalmazása?
RS256-ot  
  
### Honnan van a publikus kulcs?
Ez egy nagyon jó kérdés! :-)  
  
### Miért ilyen kidolgozatlan a weboldal?
Mert nem akartam ezzel sok időt foglalkozni, illetve nem vagyok LV 100-as UI mágus. Lehet amúgy, hogy a suliban jobban kellett volna figyelnem, amikor ezt tanították XD. 
  
## Források
- https://github.com/mebjas/html5-qrcode
- https://github.com/kjur/jsrsasign
- https://play.google.com/store/apps/details?id=hu.gov.eeszt.mgw.covidpassportcontrol

## Önvédelem
Semmilyen adatot nem kezelek/kezel a rendszer, minden adat lokálisan van feldolgozva a böngészőben.  
A kód publikus, bárki számára elérhető, tanulmányozható, másolható, szerkezthető, stb...  
Bármi nemű hasonlóság amely az eesztgov.hu és az Elektronikus Egészségügyi Szolgáltatási Tér között merülhet fel pusztán a véletlen műve.
Kérlek ne bátsatok, tényleg jóhiszeműen csináltam ezt a weboldalt! :-)  
  
