# Change Log
All notable changes to this project will be documented in this file.
 
The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [3.0.0-beta1] - 04.08.2021.

### Added
- Nova opcija za podešavanje podsetnika (vreme pre početka emisije kada će se popup prikazati, vreme kada će se automatski popup sakriti nakon prikazivanja)
- Nova opcija u podešavanjima koja omogućava korisniku da uključi u Catchupu automatsko puštanje sledeće emisije nakon završetka trenutne emisije koju je gledao (Ova funkcionalnost radiće i za VOD)
- Menjanje kanala unutar kategorija. Ova opcija se uključuje kroz podešavanja i biće po defaultu isključena.

### Changed
/

### Fixed
- Preskakanje sadržaja na kraj videa u VODu nije radilo ukoliko je prethodno korisnik puštao Catchup.

## [2.0.24] - 05.07.2021.

### Added
- Globalna promenljiva "VOD_PAGINATION" koja će označavati maksimalan broj zapisa na VOD sekciji po jednoj stranici u trenutku učitavanja. Moguće je promeniti ovu vrednost u svakom trenutku na serveru i to će biti vidljivo automatski u aplikaciji.
- Dodata je mogućnost vraćanja na vrh liste na BACK dugme unutar VOD sekcije
- Globalna promenljiva "CHECK_VOD_SERVICE" koja će označavati da li je potrebno da korisnik ima vod servis za prikazivanje opcije VOD u glavnom meniju početne stranice
- Paginacija dodata u VOD sekciji za Filmove i Serije, pa se neće odjednom učitavati 100 ili više naslova, već 50 po stranici, koje je moguće izmeniti (Pogledati VOD_PAGINATION promenljivu)
- Animacija prilikom učitavanja slika u VOD sekciji
 
### Changed
- Povratak iz VOD Plejera ne vodi više na stranicu gde su kanali, već na početnu stranicu Video kluba
- Statistika unapređena za biranje kontenta

### Fixed
- Sekcija "Najgledanije" više ne učitava duplikate
- Ispravke grešaka iz izveštaja Firebase Crash Analitike
- Bugfix za učitavanje novih vod naslova na sekcijama "Filmovi" i "Serije"
- Bugfix za prikazivanje slicnog sadrzaja u detaljima Video kluba
