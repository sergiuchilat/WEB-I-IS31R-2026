# 🌏 Proiect Individual: Travel Wishlist App

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să creeze și să gestioneze o listă de destinații de călătorie pe care dorește să le viziteze. Aplicația trebuie să ajute utilizatorul să adauge locuri, să organizeze lista după priorități și să urmărească ce destinații a vizitat.

Aplicația trebuie realizată folosind **JavaScript** și un framework modern de frontend, iar datele pot fi salvate local sau pe server, în funcție de soluția aleasă de student.

---

## 🛠️ Tehnologii Permise
Studentul poate alege un singur framework frontend dintre următoarele:

- **React** (cu sau fără Next.js)  
- **Vue.js**  
- **Angular**  

📌 Utilizarea unui backend este opțională:

- dacă nu se folosește backend → datele se salvează în `localStorage`  
- dacă se folosește backend → tehnologia este la alegerea studentului

---

## 👤 Cerințe Funcționale (User Stories)

### 1️⃣ Managementul Destinațiilor
Utilizatorul trebuie să poată:

- adăuga o destinație nouă cu:
  - **nume destinație**
  - **țară / oraș**
  - **categorie** (ex: Aventură, Relaxare, Cultural, Natură)
  - **prioritate** (ex: Scăzută, Medie, Ridicată)
  - **notițe opționale**
- vizualiza lista completă de destinații
- șterge o destinație
- edita o destinație existentă
- marca o destinație ca **vizitată**
- vedea fiecare destinație afișată sub formă de **card sau listă**

📌 Fiecare destinație trebuie să aibă un identificator unic.

---

### 2️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – listă cu toate destinațiile
  - pagina de detaliu – informații complete despre o destinație
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/destination/123`

---

### 3️⃣ Filtrare și Organizare
- filtrare după categorie sau status (vizitat / de vizitat)
- sortare după prioritate sau nume
- evidențiere vizuală a destinațiilor deja vizitate

---

### 4️⃣ Persistența Datelor
Aplicația trebuie să asigure persistența datelor:

- **fără backend:** folosind `localStorage`
- **cu backend:** folosind API și o bază de date la alegere

📌 La refresh, datele trebuie să fie reîncărcate corect.

---

### 5️⃣ Experiența Utilizatorului (UX)
- la încărcarea aplicației: afișează un **loader simplu**
- interfața trebuie să fie:
  - clară și intuitivă
  - ușor de utilizat
  - fără erori în consolă
- evidențiere vizuală a destinațiilor vizitate și a celor prioritare
