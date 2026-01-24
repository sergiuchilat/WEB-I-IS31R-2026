# 📚 Proiect Individual: Book Library App

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să își gestioneze colecția de cărți. Aplicația trebuie să ajute utilizatorul să adauge, să vizualizeze, să editeze și să filtreze cărțile după diferite criterii, oferind o experiență clară de organizare a bibliotecii personale.

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

### 1️⃣ Managementul Cărților
Utilizatorul trebuie să poată:

- adăuga o carte nouă cu:
  - **titlu**
  - **autor**
  - **an publicare**
  - **categorie** (ex: Ficțiune, Non-ficțiune, Biografie, Știință)
  - **status** (citită / de citit)
- vizualiza lista completă de cărți
- șterge o carte
- edita o carte existentă
- vedea fiecare carte afișată sub formă de **card sau listă**

📌 Fiecare carte trebuie să aibă un identificator unic.

---

### 2️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – listă cu toate cărțile
  - pagina de detaliu – informații complete despre o carte
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/book/123`

---

### 3️⃣ Filtrare și Organizare
- filtrare după categorie sau status (citită / de citit)
- căutare rapidă după titlu sau autor
- sortare după titlu, autor sau an publicare
- evidențiere vizuală a cărților citite

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
- evidențiere vizuală a cărților recente sau favorite
