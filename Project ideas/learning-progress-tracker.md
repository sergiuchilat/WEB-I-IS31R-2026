# 📈 Proiect Individual: Learning Progress Tracker

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să urmărească progresul învățării pentru diferite cursuri sau skill-uri. Aplicația trebuie să ajute utilizatorul să adauge cursuri, să marcheze progresul și să vizualizeze statisticile personale de învățare.

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

### 1️⃣ Managementul Cursurilor
Utilizatorul trebuie să poată:

- adăuga un curs nou cu:
  - **nume curs**
  - **descriere opțională**
  - **nivel de dificultate** (ex: Începător, Mediu, Avansat)
- vizualiza lista cursurilor
- șterge un curs existent
- edita un curs existent
- marca cursurile ca **în progres** sau **finalizate**

📌 Fiecare curs trebuie să aibă un identificator unic.

---

### 2️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – lista cursurilor
  - pagina de detaliu – detalii și progresul unui curs
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/course/123`

---

### 3️⃣ Monitorizarea Progresului
- afișarea progresului pentru fiecare curs (ex: procent finalizat)
- afișarea progresului total (toate cursurile combinate)
- evidențiere vizuală a cursurilor finalizate sau întârziate

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
- afișare vizuală a progresului (ex: bare de progres, grafice)
