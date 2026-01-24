# 📇 Proiect Individual: Contact Manager

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să gestioneze contactele personale sau profesionale. Aplicația trebuie să ajute utilizatorul să adauge, vizualizeze, editeze și ștergă contacte, precum și să le filtreze și să le caute rapid.

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

### 1️⃣ Managementul Contactelor
Utilizatorul trebuie să poată:

- adăuga un contact nou cu:
  - **nume complet**
  - **telefon**
  - **email**
  - **categorie** (ex: Personal, Profesional, Familie, Prieteni)
- vizualiza toate contactele pe pagina principală
- șterge un contact existent
- edita un contact existent
- vedea fiecare contact afișat sub formă de **card sau listă**

📌 Fiecare contact trebuie să aibă un identificator unic.

---

### 2️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – listă cu toate contactele
  - pagina de detaliu – informații complete despre contact
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/contact/123`

---

### 3️⃣ Categorii și Organizare
- utilizatorul poate filtra contactele după categorie
- căutare rapidă după nume sau email
- sortare alfabetică după nume

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
