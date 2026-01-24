# 🌍 Proiect Individual: Smart Travel Planner

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să își planifice o călătorie prin gestionarea destinațiilor, activităților și a bugetului.

Aplicația trebuie realizată folosind **JavaScript** și **un framework modern de frontend**, iar datele pot fi salvate **local sau pe server**, în funcție de soluția aleasă de student.

---

## 🛠️ Tehnologii Permise

Studentul poate alege **un singur framework frontend** dintre următoarele:

- **React** (cu sau fără Next.js)
- **Vue.js**
- **Angular**

📌 Utilizarea unui **backend este opțională**:
- dacă nu se folosește backend → datele se salvează în `localStorage`
- dacă se folosește backend → tehnologia este la alegerea studentului

---

## 👤 Cerințe Funcționale (User Stories)

### 1️⃣ Managementul Călătoriilor

Utilizatorul trebuie să poată:

- adăuga o călătorie nouă cu:
  - destinație
  - perioadă (data de început și data de sfârșit)
  - buget total (număr pozitiv)
- vizualiza toate călătoriile pe pagina principală
- șterge o călătorie existentă
- vedea fiecare călătorie afișată sub formă de **card**

📌 Fiecare călătorie trebuie să aibă un **identificator unic**.

---

### 2️⃣ Navigare și Structură SPA

- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – lista călătoriilor
  - pagina de detaliu – informații despre o călătorie
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**
  - exemplu: `/trip/123`

---

### 3️⃣ Managementul Activităților

În pagina de detaliu a unei călătorii, utilizatorul trebuie să poată:

- adăuga activități, fiecare având:
  - nume
  - cost
  - categorie (select):
    - Cazare
    - Transport
    - Mâncare
    - Vizite
    - Altele
- vizualiza lista activităților
- șterge o activitate

#### 🔒 Validări Obligatorii
- numele activității nu poate fi gol
- costul trebuie să fie un număr pozitiv
- aplicația trebuie să afișeze mesaje de eroare simple

---

### 4️⃣ Monitorizarea Bugetului

Aplicația trebuie să calculeze automat:

- suma totală a activităților
- bugetul rămas

📌 Dacă bugetul este depășit:
- suma totală trebuie evidențiată vizual (ex: culoare roșie)

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
  - clară
  - ușor de utilizat
  - fără erori în consolă

