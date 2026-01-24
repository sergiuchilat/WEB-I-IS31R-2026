# 📔 Proiect Individual: Personal Journal App

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să își țină un jurnal personal. Aplicația trebuie să ajute utilizatorul să creeze, vizualizeze, editeze și gestioneze însemnările zilnice sau pe perioade, oferind o experiență intuitivă și sigură pentru datele personale.

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

### 1️⃣ Managementul Jurnalului
Utilizatorul trebuie să poată:

- adăuga o însemnare nouă cu:
  - **titlu**
  - **conținut**
  - **data însemnării** (implicit ziua curentă)
  - **categorie opțională** (ex: Personal, Școală, Job)
- vizualiza lista completă de însemnări
- șterge o însemnare
- edita o însemnare existentă
- vedea fiecare însemnare afișată sub formă de **card sau listă**

📌 Fiecare însemnare trebuie să aibă un identificator unic.

---

### 2️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – listă cu toate însemnările
  - pagina de detaliu – vizualizare completă a unei însemnări
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/entry/123`

---

### 3️⃣ Căutare și Organizare
- filtrare după categorie sau dată
- căutare rapidă după titlu sau cuvinte-cheie din conținut
- sortare după dată sau titlu

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
- evidențiere vizuală a notelor recente sau modificate
