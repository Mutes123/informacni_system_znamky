# Informační systém známky

## Popis systému
Tento systém slouží ke správě údajů o studentech, jejich předmětech a známkách.  
Cílem je poskytnout jednoduchý nástroj pro evidenci a správu studijních výsledků.

---

## Cíl projektu
- Umožnit správu dat o studentech, předmětech a známkách.  
- Poskytnout přehledné rozhraní pro učitele (administrátory).  
- Volitelně umožnit studentům přístup k jejich vlastním známkám.

---

## Uživatelé systému
- **Administrátor** (učitel) – má plný přístup k datům, může přidávat, upravovat a mazat záznamy.  
- **Student** (volitelně) – má pouze možnost prohlížet své známky, bez možnosti úprav.

---

## Evidovaná data

### Studenti
- ID studenta
- Jméno a příjmení
- Datum narození
- Třída / skupina

### Předměty
- ID předmětu  
- Název předmětu  
- Učitel

### Známky
- ID známky  
- Student (odkaz na konkrétního studenta)  
- Předmět (odkaz na konkrétní předmět)  
- Známka  
- Datum udělení
