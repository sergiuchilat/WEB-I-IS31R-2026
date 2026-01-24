# 🏋️‍♂️ Proiect Individual: Fitness Workout Planner

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să planifice și să urmărească antrenamentele fizice. Aplicația trebuie să ajute utilizatorul să adauge exerciții, să calculeze durata totală a antrenamentului și să monitorizeze progresul săptămânal.

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

### 1️⃣ Managementul Antrenamentelor
Utilizatorul trebuie să poată:

- adăuga un antrenament nou cu:
  - **nume antrenament**
  - **lista de exerciții** (ex: genuflexiuni, flotări, alergare)
  - **durata fiecărui exercițiu**
  - **categorie** (ex: Forță, Cardio, Flexibilitate)
- vizualiza lista de antrenamente
- șterge un antrenament existent
- edita un antrenament existent
- vedea fiecare antrenament afișat sub formă de **card sau listă**

📌 Fiecare antrenament trebuie să aibă un identificator unic.

---

### 2️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – listă cu toate antrenamentele
  - pagina de detaliu – detalii complete despre antrenament
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/workout/123`

---

### 3️⃣ Calcul și Organizare
- calcul automat al **duratei totale a antrenamentului** (sumă exerciții)
- filtrare antrenamente după categorie
- sortare după durată sau nume

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
- evidențiere vizuală a antrenamentelor finalizate
