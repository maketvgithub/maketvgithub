# Change Log
Sve značajne promene ovog projekta biće dokumentovane u ovoj datoteci.
 
Format se zasniva na [Keep a Changelog](http://keepachangelog.com/)
i ovaj projekta se pridržava [Semantic Versioning](http://semver.org/).

## [5.0.0-rc.2] - 15.06.2022.

### Added
- Dodat broj telefona korisničke podrške za poruku kad usluga nije dostupna ili kanal nije u okviru paketa
- Dodata je nova opcija u podešavanjima "Zadrži originalni odnos širine i visine videa" koja omogućava korisniku da pri gledanju live stream-a ne dobije razvučenu sliku, već u originalnom formatu.
- Dodata je nova opcija u podešavanjima "Nastavi da slušaš radio u pozadini" koja omogućava korisniku da isključi puštanje radio kanala u pozadini pri svakom prelasku sa strima na početni ekran
- Dodate Google reklame na početnom ekranu

### Changed
- Uklonjen okvir logoa na uvodnom ekranu za upoznavanje sa aplikacijom
- Prilagođeni tekstovi politici kompanije. Obraćanje je na ti, a ne Vi. 
- Izmenjen način puštanja radio kanala. Dodat servis koji će omogućiti plejeru da radi u pozadini dok aplikacije nije aktivna ili dok je telefon zaključan. Takođe, notifikacije će se prikazivati uvek.


## [5.0.0-beta.5] - 31.05.2022.

### Added
- Pri dobavljanju liste kategorija za kanale, podacu su lokalizovani i dobijaju se u jeziku koji je podešen na uređaju

### Changed
- Izmenjen prag za promenu kanala prevlačenje prstom

### Fixed
- Ispravljeno je prikazivanje Google reklame svaki put nakon promene kanala kada je samo ovaj format aktivan, odnosno pre-roll reklame su pauzirane

## [5.0.0-beta.4] - 27.05.2022.

### Changed
- Zamenjena ikonica aplikacije na uvodnom ekranu
- Pozdravna poruka zamenjena za demo korisnika
- Izmenjen način prikazivanja reklama. Ukoliko su u isto vreme aktivne Google i Pre-roll reklame, mi određujemo procentualno koja reklama će češće da se prikazuje. Trenutno je odnos 50:50. Broj promena je isti i za Pre-roll i Google.

### Fixed
- Notifikacija se uklanja i radio kanal prestaje da radi nakon što se korisnik izloguje iz aplikacije
- Kada se uklone svi podsetnici, prikaže se poruka da više nema nijedan podsetnik i edit mode je sakriven, kao i dugme za uklanjanje podsetnika

## [5.0.0-beta.3] - 24.05.2022.

### Added
- Dodat placeholder u video klubu, kada slika nije dostupna
- Dodato objašnjenje u sistemskim podešavanjima aplikacije čemu služi obaveštenje za plejer koje se prikazuje samo u slučaju puštanja radio kanala

### Changed
- Onemogućeno je dodavanje kanala u listu omiljenih kanala za Freemium i Demo korisnike u programskoj šemi
- Više nije vidljiva moja lista Freemium korisnicima. Umesto toga, prikazuju se najgledaniji kanali
- Promenjena putanja za logotipe za belu pozadinu
- Ukoliko je notifikacija ostala u status baru, pri povratku u aplikaciju biće uklonjena u slučaju da je korisnik ranije prinudno zatvorio aplikaciju

### Fixed
- Kod radio kanala linija koja se pojavljuje kao senka koja prekriva sadržaj nije više vidljiva. 
- Kod radio kanala sakrivanje bottom menija se dešava pri skrolovanju liste.
- Vast reklame se više ne prikazuju za sve korisnike.
- Klik na notifikaciju, kada je radio kanal aktivan sada radi i otvara radio kanal koji trenutno ide

## [5.0.0-beta.2] - 21.05.2022.

### Added
- Nakon promene kanala u plejeru i povratak u listu kanala, lista će biti pozicionirana na kanalu koji ste poslednji gledali
- Analitika dodata za praćenje kretanja u aplikaciji (Napomena: Ostalo je na još nekoliko mesta u aplikaciji dodati)

### Changed
- Optimizovane slike u VoD sekciji
- Izmenjen način učitavanja podataka u detaljima Video kluba
- Minimalni broj karaktera potreban za pretraživanje pojmova je 2
- Redizajn templejta za nativne reklame
- Notifikacije se ne prikazuju više pri promeni radio kanala
- Zamenjeni test ključevi za prikazivanje Guglovih reklama

### Fixed
- Rešeno je pucanje aplikacije kada se listaju Radio kanali 

## [5.0.0-beta.1] - 04.05.2022.

### Added
- Placeholder za slot kada slika emisije nije dostupna
- Prelazak iz testnog okruženja u produkcijsko okruženje kako za regularnog korisnika, tako i za demo korisnika (Napomena: Potrebno je konfigurisati VoD sadržaj da se prikazuje u zoni u kojoj je demo korisnik, ali i korisnik koji se besplatno registruje)

### Changed
- Reklame se prikazuju od sada samo FREE i DEMO korisnicima

### Fixed
- Bugfix za crash pri puštanju live strem-a iz EPG Details
- Bugfix za slotove kanala kada trenutna emisija nije dostupna za neki od kanala iz liste omiljenih kanala.


## [5.0.0-alpha.7] - 27.04.2022.

### Added
- Ukoliko je istekla sesija, dodata je redirekcija na login ekran i u programskoj šemi, kao i u detaljima emisije
- Dodati su baneri u listi kanala (Moguće je malo usporenje tu, ali ne nešto značajno)
- Logotipi za belu pozadinu
- Puštanje radio kanala u pozadini, kao i dodavanje plejera u status baru
- Novi ekran za brisanje uređaja ukoliko je dostignut limit za kreiranje novih uređaja.
- Dodate su kategorije kada se uređuje lista "Moji kanali"

### Changed
- Sakrivene su kategorije "Erotski" i "HD"
- Provera korisničkog imena da li je potrebno dodavanje email adrese i prilikom logovanja
- Umesto polja za email, sada se je korisničko ime na ekranu za promenu lozinke
- Sakrivena je opcija za podesavanje vidljivosti kanala

### Fixed
- Ispravljeno je funkcionisanje filtera za kategorije "TV Unazad" i "Omiljeni" u listi kanala

## [5.0.0-alpha.6] - 19.04.2022.
 
### Added
- Novi ekran je dodat za zaboravljenu lozinku (Takođe ukoliko pogrešite lozinku, dobićete poruku koja će vas usmeriti da promenite lozinku)
- Dodat je broj VoD naslova u katalogu (Ovde su uključene i epizode zbirno po svim sezonama po seriji)
- Na mnogim mestima u aplikaciji dodata je redirekcija korisnika na login ukoliko je sesija istekla
- Dodata je lista nepoželjnih kanala (Za sada samo kanal koji smo koristili za internu logiku i koji ne postoji i zbog kojeg je crashovala aplikacija na Demo nalogu, ali i na Freemium/Paid dok se radila pretraga)
- Lokalizacija na nekim mestima gde je nije bilo
 
### Changed
- Uklonjen tekst "Sortirajte" na VoD ekranu
- Sličan VoD sadržaj - izmenjena logika i izmenjeni filteri za dobijanje sličnog sadržaja
 
### Fixed
- Ispravljen bug u detaljima VoD-a
- Rešen je problem sa puštanjem kanala na swipe dok ste na Live stream-u
 
## [5.0.0-alpha.5] - 14.04.2022.
 
### Added
- Demo korisnik dodat na testnom serveru
- Dodata je ikonica aplikacije
- Dodato je prikazivanje detalja emisije i vod iz pretrage
- Lokalizacija na srpski jezik
- Dodavanje grešaka na ekranu za prijavljivanje, registraciju i verifikaciju mejla
 
### Changed
- Lista omiljenih kanala se prikazuje samo za regularnog korisnika, dok za demo korisnika se vidi lista najgledanijih kanala
- Pretraga je unapređena
- Neke opcije su sakrivene u podešavanjima za demo korisnika
- VoD UI
 
### Fixed
- Crash fix za demo ili regularnog korisnika nakon prinudnog zatvaranja aplikacije
- Crash fix pri promeni kategorije kanala na Home ekranu
- Rešen problem sa konstantnim prikazivanjem progresa nakon prelaska sa 
- Dešavalo se da nakon brisanja aplikacije neki podaci ostaju sačuvani na memoriji uređaja
- Ispravljene pojedine greške iz test run-ova
 
