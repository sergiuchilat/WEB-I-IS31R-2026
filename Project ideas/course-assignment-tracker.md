# 🎓 Proiect Individual: Course & Assignment Tracker

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite studentului să își organizeze cursurile, temele și deadline-urile. Aplicația trebuie să ajute utilizatorul să țină evidența sarcinilor academice, să vizualizeze ce trebuie să predea în fiecare zi și să monitorizeze progresul pe semestre sau săptămâni.

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
  - **profesor**
  - **ziua și ora cursului**
  - **număr credite** (opțional)
- vizualiza lista completă de cursuri
- șterge sau edita un curs existent
- fiecare curs afișat sub formă de **card sau listă**  

📌 Fiecare curs trebuie să aibă un identificator unic.

---

### 2️⃣ Managementul Temelor / Assignment-urilor
Utilizatorul trebuie să poată:

- adăuga teme/assignment-uri cu:
  - **titlu**
  - **curs asociat**
  - **data de predare**
  - **descriere opțională**
  - **status** (de făcut / în curs / finalizat)
- vizualiza lista completă de teme, cu sortare după dată
- edita sau șterge o temă
- evidențiere vizuală a temelor aproape de deadline

📌 Fiecare temă trebuie să aibă un identificator unic.

---

### 3️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – listă cursuri + teme urgente
  - pagina de detaliu – informații complete despre un curs sau o temă
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/course/123` sau `/assignment/456`

---

### 4️⃣ Funcționalități Extra (Opțional, dar recomandat)
- filtrare teme după curs sau status
- calendar vizual pentru deadline-uri
- alertă vizuală pentru teme restante sau cursuri care se suprapun
- statistică simplă: câte teme sunt finalizate / în curs / restante

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
- evidențiere vizuală a cursurilor și temelor urgente
