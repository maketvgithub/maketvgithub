# Change Log
Sve značajne promene ovog projekta biće dokumentovane u ovoj datoteci.
 
Format se zasniva na [Keep a Changelog](http://keepachangelog.com/)
i ovaj projekta se pridržava [Semantic Versioning](http://semver.org/).

## [server-3.0.1-SNAPSHOT] - 19.05.2022.

### Changed
- Dodavanje kanala u favorite je moguće i za kanale na koje korisnik nije pretplaćen. Ova izmena je bila neophodna zbog konfiguracije sa vast kanalima i nemogućnosti da freemium korisnici dodaju kanale u listu favorita

### Fixed
- Bug sa prikazivanjem pozicije odgledanog vod sadržaja ispravljen
- Default base url za CRM api ispravljen

## [server-3.0.0-SNAPSHOT] - 04.05.2022.
 
### Added
- Privatni ključevi dodati na serverskoj strani radi utvrđivanja klijenta
- Različite verzije funkcionalnosti za određene rute REST API-ija
- CRM username i password se učitavaju sada iz baze i nije potrebno više slati ih uz svaki zahtev za dobijanje tokena
- Dodata nova ruta za REST API koja će imati za cilj da označi neki kanal da li je sakriven ili ne (Neophodne su izmene i na klijentskoj strani)
- Prilikom prijavljivanja, dodeljuje se uloga korisnika u zavisnosti od naloga (DEMO; FREE; ORION). Razlika između FREE i ORION korisnika je ta što FREE korisnik nema CATCHUP uslugu. (Ovo će promeniti način na koji se razlikuje korisnik koji se besplatno registrovao od onog korisnika koji je platio. Do sada smo to razlikovali na osnovu imiginarnog kanala "Joker" koji smo sakrivali)

### Changed
- Poboljšanja u vezi sa dodavanjem novog korisničkog naloga (Neophodne su izmene i na klijentskoj strani)
- Poboljšanja u vezi sa keširanjem podataka iz Video kluba
 
### Fixed
- Ispravljen bug sa prikazivanjem naslova u sekciji "Najgledanije" Video kluba
 
