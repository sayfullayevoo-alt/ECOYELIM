# EKO-YELIM — BukhSU INNOCHEM

EKO-YELIM mahsuloti uchun yaratilgan zamonaviy, moslashuvchan va uch tilli veb-sahifa. Loyiha HTML, CSS va JavaScript yordamida bitta `index.html` faylida tayyorlangan.

## Imkoniyatlar

- O‘zbek, ingliz va rus tillarida kontent.
- Sahifa ichidan tilni almashtirish.
- Mahsulot haqida umumiy ma’lumot.
- Mahsulotning ilmiy-texnik tarkibi va qo‘llanish sohasi.
- Ixtiro patenti haqidagi ma’lumot.
- Loyiha rahbari haqida ma’lumot.
- Telefon orqali bog‘lanish tugmasi.
- Kompyuter, planshet va telefon ekranlariga moslashuvchan dizayn.
- Sahifa elementlari uchun yengil ko‘rinish animatsiyalari.
- Alohida kutubxonalar yoki build jarayonisiz ishlaydi.

## Fayllar

```text
project/
├── index.html
└── README.md
```

## Ishga tushirish

### Lokal kompyuterda

1. `index.html` faylini yuklab oling.
2. Faylni ikki marta bosing yoki brauzer orqali oching.
3. Sayt Chrome, Edge, Firefox yoki boshqa zamonaviy brauzerda ochiladi.

### Lokal server orqali (ixtiyoriy)

Agar Python o‘rnatilgan bo‘lsa, loyiha papkasida terminal yoki CMD ochib quyidagini bajaring:

```bash
python -m http.server 8000
```

So‘ng brauzerda quyidagi manzilni oching:

```text
http://localhost:8000
```

## Tilni o‘zgartirish

Sahifaning yuqori o‘ng qismidagi til menyusidan quyidagilardan birini tanlang:

- `UZ` — o‘zbek tili
- `EN` — ingliz tili
- `RU` — rus tili

Tanlangan til brauzerning `localStorage` xotirasida saqlanishi mumkin. Brauzer ushbu xususiyatni cheklasa, sahifa baribir ishlaydi.

## Aloqa ma’lumotlari

- Telefon: **+998 93 968 23 32**
- Tashkilot: **BukhSU INNOCHEM — Buxoro davlat universiteti spin-off korxonasi**
- Mahsulot: **EKO-YELIM**

## Texnik ma’lumot

- HTML5
- CSS3
- Vanilla JavaScript
- Responsive layout
- Hech qanday paket menejeri yoki kompilyatsiya talab qilinmaydi

## Tahrirlash

Matnlarni uch tilda yangilash uchun `index.html` ichidagi `translations` JavaScript obyektini tahrirlang. Dizayn va ranglarni o‘zgartirish uchun fayl boshidagi `<style>` bo‘limidagi CSS o‘zgaruvchilaridan foydalaning.

Telefon raqamini yangilash kerak bo‘lsa, sahifadagi ko‘rsatilgan raqam bilan birga `tel:` havolasini ham yangilang.

## Eslatma

Sayt hozircha statik veb-sahifa hisoblanadi. Unda server tomoni, ma’lumotlar bazasi yoki murojaat yuborish formasi yo‘q. Patent va mahsulotga oid ma’lumotlarni ommaga e’lon qilishdan oldin rasmiy manbalar bilan tekshirish tavsiya etiladi.

---

© BukhSU INNOCHEM · EKO-YELIM
