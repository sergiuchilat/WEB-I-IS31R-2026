# 🍲 Proiect Individual: Recipe Manager App

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să creeze, vizualizeze și gestioneze rețete culinare. Aplicația trebuie să ajute utilizatorul să adauge ingrediente, pași de preparare și categorii, să caute și să filtreze rețetele, și să organizeze colecția personală de rețete.

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

### 1️⃣ Managementul Rețetelor
Utilizatorul trebuie să poată:

- adăuga o rețetă nouă cu:
  - **nume rețetă**
  - **ingrediente** (listă de elemente)
  - **pași de preparare** (listă sau text)
  - **categorie** (ex: Desert, Fel Principal, Aperitiv, Salată)
  - **timp de preparare**
- vizualiza lista completă de rețete
- șterge o rețetă
- edita o rețetă existentă
- vedea fiecare rețetă afișată sub formă de **card sau listă**

📌 Fiecare rețetă trebuie să aibă un identificator unic.

---

### 2️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – listă cu toate rețetele
  - pagina de detaliu – informații complete despre o rețetă
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/recipe/123`

---

### 3️⃣ Căutare și Organizare
- filtrare după categorie sau timp de preparare
- căutare rapidă după nume sau ingrediente
- sortare după nume sau popularitate (opțional)

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
- evidențiere vizuală a rețetelor recente sau favorite
