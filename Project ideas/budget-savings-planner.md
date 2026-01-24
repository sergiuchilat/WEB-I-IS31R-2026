# 💵 Proiect Individual: Budget Savings Planner

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să își planifice economiile și să urmărească progresul financiar. Aplicația trebuie să ajute utilizatorul să seteze obiective de economisire, să adauge venituri și cheltuieli și să monitorizeze bugetul disponibil.

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

### 1️⃣ Managementul Bugetului
Utilizatorul trebuie să poată:

- seta un **obiectiv de economisire** cu:
  - nume obiectiv
  - suma țintă
  - termen limită
- adăuga venituri și cheltuieli cu:
  - sumă (număr pozitiv)
  - categorie (ex: Alimentație, Transport, Divertisment, Salarii, Altele)
  - dată
- vizualiza total venituri, total cheltuieli și suma economisită
- șterge sau edita intrări de venit/cheltuială

📌 Fiecare intrare trebuie să aibă un identificator unic.

---

### 2️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – rezumat buget și listă venituri/cheltuieli
  - pagina de detaliu – gestionarea obiectivelor și intrărilor
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/budget/123`

---

### 3️⃣ Monitorizarea Obiectivelor
- calcul automat al procentului economisit pentru fiecare obiectiv
- evidențiere vizuală a obiectivelor atinse sau depășite
- filtrare intrări după categorie sau dată
- afișare grafică opțională (ex: pie chart pentru cheltuieli)

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
- evidențiere vizuală a sumelor negative sau depășiri de buget
