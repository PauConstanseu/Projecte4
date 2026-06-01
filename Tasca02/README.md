# 🚀 Introducció a la tasca: Proves de concepte de còpies de seguretat

En aquesta tasca es posa en pràctica la política de còpies de seguretat dissenyada per al client **Muntatges i Serveis Tècnics SL**, amb l’objectiu de formar el personal tècnic en la seva correcta implementació.

📦 Es treballarà amb dues proves de concepte diferenciades:

### 🖥️ Part 1: Còpies de seguretat en Windows
S’implementarà una estratègia basada en l’esquema 3-2-1 per protegir el perfil d’usuari del director mitjançant l’eina Duplicati, realitzant:
* **Còpies cada hora** en un disc secundari local 💾
* **Còpies diàries** a les 18:00 al núvol (Google Drive ☁️)
* **Simulació de pèrdua i restauració** de dades per verificar el correcte funcionament del sistema 🔄

### 🐧 Part 2: Còpies de seguretat en servidor Linux
Es dissenyarà una guia tècnica utilitzant les eines Duplicity i cron per automatitzar la creació de còpies completes i incrementals del directori `/home`, garantint:
* **Ús d'un disc extern** simulat 📁
* **Còpies encriptades** mitjançant una clau de pas (*passphrase*) 🔐
* **Desmuntatge automàtic** del dispositiu d'emmagatzematge per motius de seguretat 🛡️
* **Restauració i validació** final de les dades de l'entorn ✅
