# EasyBytes
Hackathon '23
Naziv aplikacije: EASY LIFE
UVOD
Dobrodošli u izvještaj o projektu našeg studentskog hakatona na temu automatizacije doma,
tačnije naš inovativni web aplikaciju osmišljenu kako bi svakodnevni život bio još jednostavniji.
Naš tim je stvorio jedinstveno rješenje za jedan od najčešćih problema u kuhinji - nedostatak 
osnovnih sastojaka u najgorem mogućem trenutku. Naša aplikacija, nazvana "Easy Life", osmišljena je 
kako bi se besprijekorno integrirala s vašim pametnim frižiderom i slala upozorenja kada određeni sastojci nestaju.

Naš cilj je povećati produktivnost i smanjiti vrijeme koje se bespotrebno troši na kupovinu namirnica ili trčanje u market po nedostajuću stavku.
Osim osnovne funkcionalnosti, naša aplikacija nudi i dodatne značajke u Gold i Silver paketima.
Premium paket uključuje mogućnost generiranja recepata na temelju sastojaka koji su vam dostupni, 
što vam omogućuje da brzo i jednostavno pripremite ukusna jela bez bespotrebnog gubljenja vremena na planiranje obroka. 
Također, Gold paket vam omogućuje da kreirate više računa za isti dom, što je korisno za velike obitelji ili kućanstva s cimerima.

Srebrni paket nudi naprednije mogućnosti praćenja zaliha hrane. Uz aplikaciju možete koristiti skenere u vašem smeću i hladnjaku 
kako biste pratili kada se namirnice unose i izlaze, što vam omogućuje da uvijek imate točan pregled vaših zaliha.
U ovom dokumentu detaljno ćemo opisati razvoj i implementaciju naše web aplikacije te pružiti uvid u potencijalne
koristi i primjene automatizacije doma u modernom životu.

IMPLEMENTACIJA
Nakon što smo odlučili izraditi našu web aplikaciju za automatizaciju doma, odlučili smo koristiti WordPress
kao našu platformu za razvoj. WordPress je pružio idealan okvir za izgradnju aplikacije s obzirom na njegove brojne funkcije 
i fleksibilnost. Koristili smo različite WordPress dodatke za razvoj funkcija naše aplikacije, uključujući dodatak za upravljanje y
korisničkim računima i dodatak za upravljanje zalihami hrane. Korištenjem WordPressa, omogućili smo jednostavan proces izrade i 
ažuriranja web aplikacije. Naš tim je redovito surađivao na WordPress platformi kako bismo osigurali sinhronizovan rad te radili 
na rješavanju bilo kojeg problema koji se pojavio. Konačni proizvod je bio intuitivan i funkcionalan web app koji korisnicima nudi 
jednostavan način praćenja njihovih zaliha hrane i primanje upozorenja kada nedostaju ključni sastojci. 

 
INSTALACIJA
Za instalaciju web aplikacije "Easy Life" na vaš sistem, prvo će vam trebati radna instalacija WordPress-a. 
Nakon što ste postavili WordPress, možete preuzeti "Easy Life" dodatak s naše web stranice i instalirati ga pomoću instalera WordPress dodataka.
Nakon instalacije dodatka, možete ga aktivirati s WordPress stranice za dodatke. Aplikacija također zahtijeva pristup vašem pametnom hladnjaku 
da bi pravilno funkcionirala, pa će vam trebati dati dopuštenje za pristup podacima vašeg hladnjaka. Nakon instalacije i aktivacije dodatka, možete pristupiti
aplikaciji "Easy Life" iz WordPress upravljačke ploče, gdje možete konfigurirati postavke i početi koristiti značajke za upravljanje vašim zalihama hrane i 
primanje upozorenja kada vam nedostaju ključni sastojci. Easy Life je web aplikacija koja se ne instalira na vašem računalu, već se može pristupiti putem interneta 
preko vašeg web preglednika.

KORIŠTENJE
Kada prvi put pristupite Easy Life aplikaciji, vidjet ćete Početnu stranicu, na kojoj se nalazi dugme za prijavu u gornjem desnom uglu. 
Nakon što se prijavite, moći ćete pristupiti sljedećim stranicama:
Početna: Uvodna stranica na kojoj imate uvid o sadržaju
Korisnički račun: Ovdje možete urediti svoj korisnički račun, uključujući postavljanje preferencija za primanje obavijesti.
Premium paketi: Ovdje možete vidjeti dostupne premium pakete i izabrati jedan koji odgovara vašim potrebama.
O projektu: Ovdje možete pronaći više informacija o projektu Easy Life i timu koji stoji iza njega.

Senzori koju su planirani za pametne frižidere jesu senzori helija za IoT. https://docs.helium.com/
Helij senzori su vrsta IoT senzora koji koriste Helium mrežu za praćenje i nadzor različitih mjernih vrijednosti,
poput temperature, vlage i lokacije. U kontekstu pametnih hladnjaka, Helij senzori se mogu koristiti za otkrivanje kada sastojci
ponestaju (senzor težine) ili su na izmaku roka trajanja (kontrola unosa i iznosa-senzori iz pametne kante za smeće namjernica iz frižidera). 
Integriranjem tih senzora s aplikacijom "Easy Life", kupci mogu primati stvarne obavijesti kada sastojci ponestaju, 
što im omogućuje da stavku dodaju na svoj popis za kupovinu i uvijek imaju potrebne sastojke pri ruci. To ne samo da štedi vrijeme i smanjuje otpad, 
već i poboljšava cjelokupnu praktičnost korištenja pametnog hladnjaka.
Hvala vam što ste odabrali Easy Life aplikaciju!

Što se tiče skeniranja i povezivanja sa pametnom kantom za smeće kao budući mogući apdejt, novi market u Sarajevu nazvan "Crvena jabuka" posjeduje self checkout, 
dakle ideja je korištenje njihove baze podataka o namirnicama. Pametni frižider bi samim tim prepoznao namirnicu i imao uvid o sadržaju frižidera dok bi kanta detektovala otpad i samim tim nedostatak iste u kućanstvu.

Aplikacija će također u svojoj budućoj primjeni posjedovati dodatni feature koji će poslužiti kao pomoć slijepim i slabovidnim osobama kroz image recognition i zvučno obavještenje o nedostatku namirnice.
DOPRINOS
Ako želite doprinijeti razvoju aplikacije "Easy Life", dobrodošli ste da to učinite! Sve sugestije, 
prijedlozi ili povratne informacije su dobrodošli. Ako primijetite greške u kodu ili imate ideje za nove funkcionalnosti,
 možete ih prijaviti na GitHub repozitoriju aplikacije. Također možete kontaktirati naš tim putem e-maila ili društvenih mreža za podršku. 



Radujemo se vašem doprinosu u poboljšanju EasyLife aplikacije!

