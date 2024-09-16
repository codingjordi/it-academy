#### Normes per a les entregues de les tasques

A partir d'ara, tots els repositoris de GitHub han de complir les següents normes:

- S’ha de crear **un repositori** de GitHub per **cada entrega**.

- Ha d’estar **lliure d’errors** per permetre la seva execució.

- Ha d’estar **acabat** per poder ser corregit.

- S’ha de fer ús del **fitxer .gitIgnore** per evitar pujar arxius innecessaris a GitHub.

- Els commits han de tenir un **missatge clar** del que s’ha fet.

- **No pujar el node_modules.**

- **No pujar codi comentat.**

- En pujar l’URL del repositori de GitHub al Campus Virtual, posar un comentari amb els **nivells fets** a la tasca, i el **nom de la persona revisora**.

- Especialment en els repositoris de frontend:

- Revisar el responsive en bootstrap (container - row - col)

- Evitar tenir etiquetes style en l’html (styles inline)

- Si hi ha imatges, aquestes han d’ocupar el mínim espai possible: es pot utilitzar: 

**->[Squoosh.app/](https://squoosh.app/)**  
**->[Tinypng.com/](https://tinypng.com/)**  

---

#### Nom del repositori a GitHub

El nom del repositori ha de seguir el següent format:

Nº d’sprint.nº de tasca-títol de l’sprint-Nivell

Exemple: **3.1-Bases de Dades-Nivell1**

---

#### Contingut del repositori

📄**Descripció - Enunciat de l'exercici**

Aquí es detallarà una breu descripció de l'exercici i l'enunciat proporcionat.

💻**Tecnologies Utilitzades**

Llista de tecnologies, llibreries i eines utilitzades en el desenvolupament de l'exercici.

📋**Requisits**

Especificacions dels requisits necessaris per a poder executar el projecte, com ara versions de programari, dependències, etc.

🛠️**Instal·lació**

Passos necessaris per a la instal·lació del projecte en un entorn local.

▶️**Execució**

Instruccions per a l'execució del projecte un cop instal·lat.

🌐**Desplegament**

Instruccions per al desplegament del projecte en un entorn de producció o servidor.

🤝**Contribucions**

Normes i guies per a contribuir al projecte, si escau.

---

**Important**

Aquestes normes ajudaran a mantenir la consistència i qualitat de
 les entregues, facilitant la revisió i manteniment dels projectes.

---

#### Exemple

**3.1-Bases de Dades**

📄 **Descripció - Enunciat de l'exercici**

Aquest projecte consisteix en la creació i gestió d'una base de dades per a un sistema de gestió d'inventari.

💻 **Tecnologies Utilitzades**

- MySQL
- Node.js
- Express.js

📋 **Requisits**

- Node.js v14.17.0
- MySQL v8.0
- NPM v6.14.13

🛠️ **Instal·lació**

1. Clona aquest repositori:
   **-> [git clone](https://github.com/usuari/3.1-Bases-de-Dades.git)**  

2. Accedeix al directori del projecte:
    
   cd 3.1-Bases-de-Dades

3. Instal·la les dependències:
    
   npm install …

▶️ **Execució**

1. Configura la base de dades a config/database.js.
2. Executa el servidor:
    
   npm start

🌐 **Desplegament**

1. Prepara l'entorn de producció.
2. Puja els arxius del projecte al servidor.
3. Configura el servidor per a apuntar a la base de dades de producció.

🤝 **Contribucions**

Les contribucions són benvingudes! Per favor, segueix els següents passos per a contribuir:

1. Fes un fork del repositori
   
   
2. Crea una nova branca
   
   ```
   git checkout -b feature/NovaFuncionalitat
   ```
   
   
   
3. Fes els teus canvis i commiteja'ls:
   
   ```
   git commit -m 'Afegeix Nova Funcionalitat'
   ```
   
   
   
4. Puja els canvis a la teva branca:
    
   
   ```
   git push origin feature/NovaFuncionalitat
   ```
   
   Fes un pull request
