# 🎬 Proiect Individual: Movie Watchlist

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să gestioneze lista de filme pe care dorește să le urmărească. Aplicația trebuie să ajute utilizatorul să adauge filme, să le marcheze ca vizionate, să le organizeze pe categorii și să filtreze lista după diverse criterii.

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

### 1️⃣ Managementul Filmelor
Utilizatorul trebuie să poată:

- adăuga un film nou cu:
  - **titlu**
  - **gen** (ex: Acțiune, Dramă, Comedie, SF, Documentar)
  - **rating opțional**
  - **status** (de vizionat / vizionat)
- vizualiza lista completă de filme
- șterge un film din listă
- edita detaliile unui film
- vedea fiecare film afișat sub formă de **card sau listă**

📌 Fiecare film trebuie să aibă un identificator unic.

---

### 2️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – listă cu toate filmele
  - pagina de detaliu – informații complete despre film
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/movie/123`

---

### 3️⃣ Categorii și Organizare
- utilizatorul poate filtra filmele după:
  - gen
  - status (de vizionat / vizionat)
- sortare după titlu sau rating
- evidențiere vizuală a filmelor deja vizionate

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
- afișare vizuală a statusului fiecărui film
