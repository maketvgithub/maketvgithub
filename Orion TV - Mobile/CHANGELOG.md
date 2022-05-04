# Change Log
Sve značajne promene ovog projekta biće dokumentovane u ovoj datoteci.
 
Format se zasniva na [Keep a Changelog](http://keepachangelog.com/)
i ovaj projekta se pridržava [Semantic Versioning](http://semver.org/).

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
 
