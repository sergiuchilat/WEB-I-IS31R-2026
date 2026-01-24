# 📝 Proiect Individual: Student Task Manager

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să își gestioneze sarcinile și activitățile zilnice sau săptămânale. Aplicația trebuie să ajute la adăugarea, vizualizarea, editarea și ștergerea task-urilor, precum și la monitorizarea progresului acestora.

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

### 1️⃣ Managementul Task-urilor
Utilizatorul trebuie să poată:

- adăuga un task nou cu:
  - **titlu** (text)
  - **descriere** (opțional, text)
  - **deadline** (data limită)
  - **prioritate** (ex: scăzută, medie, ridicată)
- vizualiza toate task-urile pe pagina principală
- șterge un task existent
- marca un task ca **finalizat**
- vedea fiecare task afișat sub formă de **card sau listă**

📌 Fiecare task trebuie să aibă un identificator unic.

---

### 2️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – lista task-urilor
  - pagina de detaliu – informații complete despre un task
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**
  - exemplu: `/task/123`

---

### 3️⃣ Categorii și Organizare
- utilizatorul poate să atribuie un task unei **categorii** (ex: Facultate, Job, Personal)
- filtrare task-uri după:
  - categorie
  - status (activ / finalizat)
  - prioritate
- afișarea task-urilor trebuie să fie clară și ordonată

---

### 4️⃣ Monitorizarea Progresului
- afișarea numărului de task-uri **finalizate vs totale**
- evidențiere vizuală a task-urilor care depășesc deadline-ul (ex: culoare roșie)
- opțional: afișare progres procentual

---

### 5️⃣ Persistența Datelor
Aplicația trebuie să asigure persistența datelor:

- **fără backend:** folosind `localStorage`
- **cu backend:** folosind API și o bază de date la alegere

📌 La refresh, datele trebuie reîncărcate corect.

---

### 6️⃣ Experiența Utilizatorului (UX)
- la încărcarea aplicației:
  - afișează un **loader simplu**
- interfața trebuie să fie:
  - clară și intuitivă
  - ușor de utilizat
  - fără erori în consolă
