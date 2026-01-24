# 📝 Proiect Individual: Exam Revision Planner

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care ajută studentul să își planifice și să urmărească sesiunile de pregătire pentru examene. Aplicația trebuie să permită crearea unui plan de studiu, organizarea subiectelor pe zile, setarea priorităților și monitorizarea progresului.

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

### 1️⃣ Managementul Subiectelor și Materiilor
Utilizatorul trebuie să poată:

- adăuga materii sau subiecte de examen cu:
  - **nume materie**
  - **descriere opțională**
  - **nivel de dificultate** (ex: Ușor, Mediu, Greu)
- vizualiza lista completă de materii
- șterge sau edita o materie/subiect
- fiecare materie afișată sub formă de **card sau listă**

📌 Fiecare materie trebuie să aibă un identificator unic.

---

### 2️⃣ Planificarea Sesiunilor de Studiu
- adăugarea de sesiuni de revizie cu:
  - **materie/subiect asociat**
  - **data și ora**
  - **durata estimată**
  - **status** (neînceput / în curs / finalizat)
- vizualizarea sesiuni planificate într-un **calendar simplu sau listă**
- editarea sau ștergerea unei sesiuni
- evidențiere vizuală a sesiunilor apropiate sau depășite

📌 Fiecare sesiune trebuie să aibă un identificator unic.

---

### 3️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – listă materii + sesiuni urgente
  - pagina de detaliu – detalii complete despre o sesiune sau materie
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/subject/123` sau `/session/456`

---

### 4️⃣ Funcționalități Extra (Opțional, dar recomandat)
- filtrare sesiuni după materie sau status
- vizualizare progres: câte sesiuni sunt finalizate / în curs / restante
- reminder vizual pentru sesiuni planificate pentru ziua curentă
- evidențiere vizuală a materiilor prioritare

---

### 5️⃣ Persistența Datelor
Aplicația trebuie să asigure persistența datelor:

- **fără backend:** folosind `localStorage`
- **cu backend:** folosind API și o bază de date la alegere

📌 La refresh, datele trebuie să fie reîncărcate corect.

---

### 6️⃣ Experiența Utilizatorului (UX)
- la încărcarea aplicației: afișează un **loader simplu**
- interfața trebuie să fie:
  - clară și intuitivă
  - ușor de utilizat
  - fără erori în consolă
- evidențiere vizuală a sesiunilor urgente și a materiilor prioritare
