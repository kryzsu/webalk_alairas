# hallgató nyilvántartó alkalmazás
a hallgatónak a következő adatai vannak
- neve
- neptun kód
- eletkor
- önköltséges (igen/nem)

Webalkalmazás feladat a szokott konvenciók betartásával a hallgató entitás feltöltését, törlését, módosítását, listázását megvalósítani!

Kérünk még egy **fizeto_veteran** kereses végpontot, ami GET metódusra válaszol, 
http paramétere kor értéke egy eletkor. Működése: visszaadja azon hallgatókat, amelyek önköltségesek, és a megadott életkortól idősebbek. pl.: http://localhost:8080/fizeto_veteran?kor=45

1. kommit uzenet legyen “projektAlap”, a spring starter által generált üres projekt. h2 adatbázis, spring data, spring-boot-starter-validation, spring web
2. kommit üzenet “adatbazis”, szükséges entitások, repository, config beallitasok
3. kommit üzenet “web” működő webalkalmazás a szükséges végpontokkal.
4. kommit üzenet “hasznalat” milyen http kérésekkel lehet a funkciókat kipróbálni. pl: PUT http://localhost:8080/hallgato/2 {JSON}
