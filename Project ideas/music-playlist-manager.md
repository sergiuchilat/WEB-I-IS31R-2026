# 🎵 Proiect Individual: Music Playlist Manager

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să creeze și să gestioneze playlist-uri muzicale. Aplicația trebuie să ajute utilizatorul să adauge melodii, să organizeze playlist-uri, să urmărească durata totală și să filtreze melodiile după diferite criterii.

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

### 1️⃣ Managementul Playlist-urilor
Utilizatorul trebuie să poată:

- crea un playlist nou cu:
  - **nume playlist**
  - **descriere opțională**
- adăuga melodii într-un playlist cu:
  - **titlu melodie**
  - **artist**
  - **durată**
  - **gen** (ex: Pop, Rock, Jazz, Clasic)
- vizualiza lista completă de playlist-uri și melodii
- șterge un playlist sau melodie
- edita un playlist sau melodie existentă
- vedea fiecare playlist afișat sub formă de **card sau listă**

📌 Fiecare playlist și melodie trebuie să aibă un identificator unic.

---

### 2️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – listă cu toate playlist-urile
  - pagina de detaliu – vizualizare melodii dintr-un playlist
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/playlist/123`

---

### 3️⃣ Organizare și Filtrare
- filtrare melodii după gen sau artist
- sortare melodii după titlu sau durată
- evidențiere vizuală a playlist-urilor populare sau favorite
- calcul automat al **duratei totale** a fiecărui playlist

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
- evidențiere vizuală a playlist-urilor sau melodiilor noi și favorite
