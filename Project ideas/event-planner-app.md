# 📅 Proiect Individual: Event Planner App

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să creeze, să gestioneze și să urmărească evenimente personale sau profesionale. Aplicația trebuie să ajute utilizatorul să adauge detalii despre evenimente, să stabilească date și ore, să invite participanți și să monitorizeze statusul fiecărui eveniment.

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

### 1️⃣ Managementul Evenimentelor
Utilizatorul trebuie să poată:

- adăuga un eveniment nou cu:
  - **nume eveniment**
  - **descriere**
  - **data și ora**
  - **locație**
  - **categorie** (ex: Personal, Profesional, Social)
  - **listă participanți** (opțional)
- vizualiza lista completă de evenimente
- șterge un eveniment
- edita un eveniment existent
- vedea fiecare eveniment afișat sub formă de **card sau listă**

📌 Fiecare eveniment trebuie să aibă un identificator unic.

---

### 2️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – listă cu toate evenimentele
  - pagina de detaliu – informații complete despre un eveniment
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/event/123`

---

### 3️⃣ Organizare și Monitorizare
- filtrare după categorie sau dată
- sortare după dată, ora sau nume
- evidențiere vizuală a evenimentelor viitoare sau trecute
- opțional: alertă vizuală sau notificare pentru evenimente apropiate

---

### 4️⃣ Persistența Datelor
Aplicația trebuie să asigure persistența datelor:

- **fără backend:** folosind `localStorage`
- **cu backend:** folosind API și o bază de date la alegere

📌 La refresh, datele trebuie să fie reîncărcate corect.

---

### 5️⃣ Experiența Utilizatorul
