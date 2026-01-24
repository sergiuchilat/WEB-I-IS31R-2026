# 🗒️ Proiect Individual: Online Notes App

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să creeze, vizualizeze, editeze și gestioneze notițele personale. Aplicația trebuie să ajute utilizatorul să organizeze informațiile rapid și eficient, cu posibilitatea de a căuta și filtra notițele.

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

### 1️⃣ Managementul Notițelor
Utilizatorul trebuie să poată:

- adăuga o notiță nouă cu:
  - **titlu**
  - **conținut**
  - **categorie opțională** (ex: Personal, Școală, Job)
- vizualiza lista completă de notițe
- șterge o notiță
- edita o notiță existentă
- vedea fiecare notiță afișată sub formă de **card sau listă**

📌 Fiecare notiță trebuie să aibă un identificator unic.

---

### 2️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – listă cu toate notițele
  - pagina de detaliu – vizualizare completă a unei notițe
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/note/123`

---

### 3️⃣ Căutare și Organizare
- utilizatorul poate filtra notițele după categorie
- căutare rapidă după titlu sau conținut
- sortare după data creării sau titlu

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
- evidențiere vizuală a notițelor noi sau modificate recent
