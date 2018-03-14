Repozytorium z przedmiotu NoSQL.

Dane: [Baltimore 911 Calls](https://www.kaggle.com/sohier/baltimore-911-calls)

Opis danych: This dataset records the time, location, priority, and reason for calls to 911 in the city of Baltimore.

Ilość dokumentów w bazie: 2.799.914


TODO:
- [x] Konwersja danych CSV to JSON
- [x] Instalaja mongoDB
- [x] Import danych do mongoDB
- [ ] Praca z replica set na localhost
- [ ] Praca z replica set na 3 komputerach
- [ ] Napisanie skryptu do importów i liczeniu czasu
- [ ] Przetestowanie skryptu


Konwersja danych CSV to JSON ([csvtojson](https://www.npmjs.com/package/csvtojson)):
Instalacja:
```
npm i -g csvtojson
```

Użycie:
```
npm i -g csvtojson
```
csvtojson source.csv > converted.json
```
