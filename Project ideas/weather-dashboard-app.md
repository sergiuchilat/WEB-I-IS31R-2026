# 🌦️ Proiect Individual: Weather Dashboard App

## 🎯 Scopul Proiectului
Scopul acestui proiect este dezvoltarea unei aplicații web de tip **Single Page Application (SPA)** care permite utilizatorului să urmărească prognoza meteo pentru diferite locații. Aplicația trebuie să afișeze informații precum temperatura, starea vremii, umiditatea și viteza vântului, și să permită căutarea rapidă a orașelor dorite.

Aplicația trebuie realizată folosind **JavaScript** și un framework modern de frontend, iar datele pot fi salvate local sau preluate de la API-uri publice de meteo, în funcție de soluția aleasă de student.

---

## 🛠️ Tehnologii Permise
Studentul poate alege un singur framework frontend dintre următoarele:

- **React** (cu sau fără Next.js)  
- **Vue.js**  
- **Angular**  

📌 Utilizarea unui backend este opțională:

- dacă nu se folosește backend → datele salvate în `localStorage` pentru orașele favorite  
- dacă se folosește backend → tehnologia este la alegerea studentului

---

## 👤 Cerințe Funcționale (User Stories)

### 1️⃣ Căutare și Vizualizare Meteo
Utilizatorul trebuie să poată:

- căuta orașe după nume
- vizualiza informații meteo pentru orașul selectat:
  - temperatură curentă
  - starea vremii (senin, noros, ploaie etc.)
  - umiditate
  - viteza vântului
- vizualiza prognoza pe următoarele zile (opțional, 3-5 zile)
- vedea informațiile afișate într-un **format clar și vizual**

---

### 2️⃣ Gestionarea Orașelor Favorite
- adăugarea unui oraș la lista de favorite
- eliminarea unui oraș din lista de favorite
- afișarea rapidă a informațiilor meteo pentru orașele favorite
- evidențiere vizuală a orașelor adăugate recent

📌 Fiecare oraș trebuie să aibă un identificator unic (ex: nume + cod de țară).

---

### 3️⃣ Navigare și Structură SPA
- aplicația trebuie să conțină cel puțin **două pagini**:
  - pagina principală – căutare oraș și listă orașe favorite
  - pagina de detaliu – informații complete despre oraș și prognoză
- navigarea între pagini trebuie realizată folosind **routing-ul framework-ului ales**  
  - exemplu: `/city/12345`

---

### 4️⃣ Persistența Datelor
Aplicația trebuie să asigure persistența datelor:

- **fără backend:** folosind `localStorage` pentru orașele favorite  
- **cu backend:** folosind API și o bază de date la alegere

📌 La refresh, orașele favorite și datele asociate trebuie să fie reîncărcate corect.

---

### 5️⃣ Experiența Utilizatorului (UX)
- la încărcarea aplicației: afișează un **loader simplu**
- interfața trebuie să fie:
  - clară și intuitivă
  - ușor de utilizat
  - fără erori în consolă
- utilizatorul trebuie să primească feedback vizual rapid după căutarea unui oraș
