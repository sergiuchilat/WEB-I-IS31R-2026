# ❓ Proiect Individual: Quiz Application

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să răspundă la întrebări de tip quiz și să vizualizeze scorul obținut. Aplicația trebuie să ajute utilizatorul să participe la quiz-uri interactive și să monitorizeze rezultatele.

Aplicația trebuie realizată folosind **JavaScript** și un framework modern de frontend, iar datele pot fi salvate local sau pe server, în funcție de soluția aleasă de student.

---

## 🛠️ Tehnologii Permise
Studentul poate alege un singur framework frontend dintre următoarele:

- **React** (cu sau fără Next.js)  
- **Vue.js**  
- **Angular**  

📌 Utilizarea unui backend este opțională:

- dacă nu se folosește backend → întrebările și rezultatele se pot salva în `localStorage`  
- dacă se folosește backend → tehnologia este la alegerea studentului

---

## 👤 Cerințe Funcționale (User Stories)

### 1️⃣ Crearea și Participarea la Quiz
Utilizatorul trebuie să poată:

- vizualiza întrebările unul câte unul
- selecta un răspuns dintre mai multe variante
- trece la întrebarea următoare după selectarea răspunsului
- vedea scorul final la sfârșitul quiz-ului

📌 Fiecare întrebare trebuie să aibă un identificator unic.

---

### 2️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – listă quiz-uri disponibile
  - pagina de detaliu – quiz-ul selectat
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/quiz/123`

---

### 3️⃣ Managementul Întrebărilor
- utilizatorul poate vedea întrebările și variantele de răspuns
- fiecare întrebare are cel puțin **3 variante de răspuns**
- se evidențiază vizual răspunsul corect după finalizarea quiz-ului (opțional)
- se calculează scorul corect / total

---

### 4️⃣ Persistența Datelor
Aplicația trebuie să asigure persistența datelor:

- **fără backend:** folosind `localStorage` pentru salvarea rezultatelor sau a progresului
- **cu backend:** folosind API și o bază de date la alegere

📌 La refresh, datele trebuie să fie reîncărcate corect.

---

### 5️⃣ Experiența Utilizatorului (UX)
- la încărcarea aplicației: afișează un **loader simplu**
- interfața trebuie să fie:
  - clară și intuitivă
  - ușor de utilizat
  - fără erori în consolă
- feedback vizual pentru răspunsuri corecte/greșite
