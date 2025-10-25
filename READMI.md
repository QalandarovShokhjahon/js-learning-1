# 🧠 JavaScript Day 1 — Variables & Data Types

Bu darsda men **JavaScript’da o‘zgaruvchilar (variables)** va **ma’lumot turlari (data types)** bilan tanishdim.  
Har bir misolda kodlar orqali ularning ishlash tartibini sinab chiqdim.

---

## 📚 O‘rganganlarim / What I learned

- `var`, `let`, `const` o‘rtasidagi farqlar  
- O‘zgaruvchilarni e’lon qilish va qiymat berish  
- Asosiy ma’lumot turlari:
  - `String` — matn
  - `Number` — raqam
  - `Boolean` — mantiqiy qiymat (`true` / `false`)
  - `Null` va `Undefined`
  - `Object` — obyektlar
  - `Array` — massivlar

---

## 💻 Kod namunasi / Example code

```javascript
// O‘zgaruvchilar yaratish
let ism = "Shokhjahon";
const yosh = 17;
var shahar = "Navoiy";

// Ma’lumot turlarini ko‘rish
console.log(typeof ism);     // string
console.log(typeof yosh);    // number
console.log(typeof shahar);  // string

// Boolean misol
let kattaYosh = yosh > 18;
console.log(kattaYosh); // true

🎯 Maqsad / Goal

JavaScript asoslarini mustahkamlash, o‘zgaruvchilar va ma’lumot turlarini amaliy misollar orqali chuqur tushunish.

💬 Muallif / Author

✍️ Shokhjahon Qalandarov
📅 Dars: 1-kun — O‘zgaruvchilar va ma’lumot turlari
