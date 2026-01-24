# 📅 Proiect Individual: Daily Habit Tracker

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să urmărească obiceiurile zilnice. Aplicația trebuie să ajute utilizatorul să adauge obiceiuri, să marcheze realizarea lor zilnică și să vizualizeze progresul pe termen lung.

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

### 1️⃣ Managementul Obiceiurilor
Utilizatorul trebuie să poată:

- adăuga un obicei nou cu:
  - **nume obicei**
  - **categorie** (ex: Sănătate, Productivitate, Hobby)
  - **frecvență** (zilnic, săptămânal)
- vizualiza lista completă de obiceiuri
- șterge un obicei
- edita un obicei existent
- marca obiceiul ca realizat în fiecare zi
- vedea fiecare obicei afișat sub formă de **card sau listă**

📌 Fiecare obicei trebuie să aibă un identificator unic.

---

### 2️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – listă cu toate obiceiurile și starea lor
  - pagina de detaliu – vizualizare istoric și progres pe termen lung
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/habit/123`

---

### 3️⃣ Monitorizarea Progresului
- afișarea progresului pentru fiecare obicei (ex: număr zile realizate / total zile)
- evidențiere vizuală a obiceiurilor realizate sau neîndeplinite
- opțional: afișare grafică (ex: calendar sau bar chart)

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
- evidențiere vizuală a progresului zilnic și pe termen lung
