# Copies de seguretat

## Introducció

La seguretat de la informació és un aspecte fonamental per a qualsevol empresa, especialment quan es tracta de dades crítiques que afecten l’operativa diària. Les còpies de seguretat són una mesura essencial per prevenir la pèrdua de dades i garantir la continuïtat del negoci davant possibles incidències com errors humans, fallades tècniques o ciberatacs. En aquesta tasca, analitzarem el cas pràctic de l’empresa “Muntatges i Serveis Tècnics SL” per definir quines dades s’han de protegir, amb quina periodicitat i mitjançant quins mitjans, tenint en compte els requisits de recuperació establerts. L’objectiu és dissenyar un pla de còpies que asseguri la disponibilitat i integritat de la informació, complint amb la regla 3-2-1 i adaptant-se a les necessitats reals de l’organització.

---

## Fase 1

### **1. Què copiar? (Priorització): Quines són les dades més crítiques del servidor? Cal fer còpia dels 10 equips clients? Justifica-ho.**

**Crític:** Bases de dades (Comptabilitat/Clients) -> ús diari, canvi constant.

**Important:** Documents de projectes.

**Mitjà:** Carpetes personals.

**Equips clients:** No còpia completa; només carpeta Documents setmanal (informes temporals).

---

### **2. Periodicitat i Tipus de Còpia: Proposa un calendari bàsic per a la setmana (Diari/Setmanal/Mensual) i quin tipus de còpia aplicaràs (Completa, Diferencial, Incremental) per a les dades crítiques.**

**Bases de dades:** Incremental cada 4 h; completa setmanal i mensual.

**Documents i carpetes:** Incremental diari; diferencial setmanal; completa mensual.

---

### **3. Mitjans i Ubicació: Quin tipus de mitjà de còpia utilitzaries (Discs durs externs, NAS, Cloud, Cintes)? On s'hauria de guardar físicament la còpia més recent (Regla 3-2-1).**

**Mitjans:** NAS intern + Cloud + disc dur extern.

**Ubicació:** Última còpia al NAS (restauració ràpida).

**Regla:** 3 còpies, 2 tipus de mitjans, 1 fora de l’empresa.
