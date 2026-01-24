# 🎉 Proiect Individual: Event Planner

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să organizeze și să gestioneze evenimente. Aplicația trebuie să ajute utilizatorul să adauge, vizualizeze, editeze și ștergă evenimente, să le filtreze după dată și categorie și să monitorizeze evenimentele viitoare sau trecute.

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

### 1️⃣ Managementul Evenimentelor
Utilizatorul trebuie să poată:

- adăuga un eveniment nou cu:
  - **nume eveniment**
  - **dată și oră**
  - **locație**
  - **categorie** (ex: Petrecere, Conferință, Workshop, Personal)
  - **descriere opțională**
- vizualiza toate evenimentele pe pagina principală
- șterge un eveniment existent
- edita un eveniment existent
- vedea fiecare eveniment afișat sub formă de **card sau listă**

📌 Fiecare eveniment trebuie să aibă un identificator unic.

---

### 2️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – listă cu toate evenimentele
  - pagina de detaliu – informații complete despre un eveniment
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/event/123`

---

### 3️⃣ Categorii și Organizare
- utilizatorul poate să filtreze evenimentele după categorie
- sortare după dată (evenimente viitoare înainte)
- evidențiere vizuală a evenimentelor trecute

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
