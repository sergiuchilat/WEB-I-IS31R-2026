# 📝 Proiect Individual: Simple Blog Platform

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să creeze și să gestioneze postări de tip blog. Aplicația trebuie să ajute utilizatorul să adauge, vizualizeze, editeze și ștergă postări și să organizeze conținutul pentru o experiență clară de citire.

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

### 1️⃣ Managementul Postărilor
Utilizatorul trebuie să poată:

- adăuga o postare nouă cu:
  - **titlu**
  - **conținut**
  - **categorie** (opțional)
  - **dată de creare**
- vizualiza toate postările pe pagina principală
- șterge o postare existentă
- edita o postare existentă
- vedea fiecare postare afișată sub formă de **card sau listă**
  
📌 Fiecare postare trebuie să aibă un identificator unic.

---

### 2️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – listă cu toate postările
  - pagina de detaliu – conținut complet al postării
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/post/123`

---

### 3️⃣ Categorii și Organizare
- utilizatorul poate filtra postările după categorie
- sortare postări după dată (cele mai recente primele)
- căutare postări după titlu sau cuvinte-cheie din conținut

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
