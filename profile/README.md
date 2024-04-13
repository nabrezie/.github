# Register Kultúrnych Objektov

[Backend](https://github.com/nabrezie/backend)
[Forntend Public](https://github.com/nabrezie/verejny-register)

## Riešenie
Scrapperi a Crawlleri zťahujú dáta z obchodného registru a štatistyckého úradu
Fistat api ztiahne dáta z Finstat API
Filter prefiltruje dáta a zaklade AI analyzéru pridá tagy podľa description
Parser rozparusuje Json do  Databázi
Rest Apiny predávajú riešenie pre Verjnú a Neverejnú časť

## Diagrami a Rozpis Riešenia
### Django Server
![Server](https://github.com/nabrezie/.github/blob/main/profile/Server.png)

### Rozpis Celeho Projektu
![Projekt](https://github.com/nabrezie/.github/blob/main/profile/Full%20System.png)


### Kontaineri
![Kontaineri](https://github.com/nabrezie/.github/blob/main/profile/Containers.png)

## Plán do 30 týždňov
### Počet ludí:
- Backend developer(Skúsenosť s dockerom, kuberneties a cloudovími servismi)
- Backend developer(Skúsenosť s backend framework(Django, ExpressJS, Tokio, Laraver etc...)
- Frotned developer(Javasript, Html, Css idealne nejaký framewokr ako napr. Vue, Next, Angular...)
- Data Engineer(skúsenosť s LLM alebo Dataminingom)

### Plán Pre Backend:
| Týždeň| Backend 1 | Backend 2 | Frotend | Data Engineer |
|-------|--------------------------------------|----------| ---------- | ----------
| 1.    | Implentacia servera                  | Dockeru a VM    |
| 2.    | Komunikaciu s databazou| Data        | Rozdelenie Kontainerov 
| 3.    | Response Reques Haddling z forntedu  | Data     |
| 4.    | Zapisovanie do databazi              |
| 5.    |        |
| 6.    |     |
| 7.    | Rest Api pre verejnú časť            |
| 8.    | Test Rest Api pre verejnú časť       |
| 9.    | Rest Api pre neverejnu časť   
| 10.   | Test Rest Api pre neverejnu časť 
| 11.   |
| 12.   |
| 13.   |
| 14.   |
| 15.   |
| 16.   |
| 17.   |
| 18.   |
| 19.   |
| 20.   |
| 21.   |
| 22.   |
| 23.   |
| 24.   |
| 25.   |
| 26.   |
| 27.   |
| 28.   |
| 29.   |
| 30.   |
