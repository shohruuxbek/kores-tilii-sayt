# O'quv Markazi Boshqaruv Tizimi

O'quv markazlari uchun to'liq boshqaruv tizimi. Backend (NestJS) va Frontend (React) dan iborat.

## 📋 Imkoniyatlar

- 👨‍🎓 **Talabalar boshqaruvi** - Ro'yxatga olish, ma'lumotlarini saqlash
- 👨‍🏫 **O'qituvchilar boshqaruvi** - O'qituvchilar ro'yxati va ma'lumotlari
- 📚 **Kurslar boshqaruvi** - Kurslar yaratish va taqsimlash
- 💰 **To'lovlar boshqaruvi** - To'lovlarni kuzatish va hisobot
- ✅ **Davomat nazorati** - Talabalar davomatini yuritish
- 🏆 **Reyting tizimi** - O'quvchilarga ball berish va eng yaxshilarni aniqlash
- 📊 **Dashboard** - Umumiy statistika va daromad

## 🚀 Ishga Tushirish

### Backend (NestJS)

```bash
cd backend
npm install
npm run start:dev
```

Backend `http://localhost:3000` da ishlaydi.

### Frontend (React)

```bash
cd frontend
npm install
npm run dev
```

Frontend `http://localhost:5173` da ishlaydi.

## 📁 Loyiha Tuzilishi

```
OQUV MARKAZI 22222/
├── backend/           # NestJS backend
│   ├── src/
│   │   ├── students/     # Talabalar moduli
│   │   ├── teachers/     # O'qituvchilar moduli
│   │   ├── courses/      # Kurslar moduli
│   │   ├── payments/     # To'lovlar moduli
│   │   ├── attendance/   # Davomat moduli
│   │   ├── auth/         # Autentifikatsiya moduli
│   │   └── main.ts       # Asosiy fayl
│   └── package.json
├── frontend/          # React frontend
│   ├── public/        # Static files (rasm, favicon)
│   │   ├── logo.png   # Sidebar uchun logo (50x50px)
│   │   └── emblem.png # Login sahifasi uchun emblem (80x80px)
│   ├── src/
│   │   ├── components/   # Komponentlar
│   │   ├── pages/        # Sahifalar
│   │   ├── api.js        # API so'rovlar
│   │   └── App.jsx       # Asosiy komponent
│   └── package.json
└── README.md
```

### 🖼️ Rasm Qo'shish

**Sidebar Logo:**
- Fayl nomi: `logo.png`
- Joylashuv: `frontend/public/logo.png`
- O'lchami: 50x50 piksel (tavsiya etiladi)

**Login Emblem:**
- Fayl nomi: `emblem.png`  
- Joylashuv: `frontend/public/emblem.png`
- O'lchami: 80x80 piksel (tavsiya etiladi)

Agar rasmlar qo'yilmasa, avtomatik ravishda matn ko'rinadi.

## 🔧 Texnologiyalar

**Backend:**
- NestJS 11
- TypeScript
- Express platform

**Frontend:**
- React 18
- Vite
- React Router DOM
- Axios

## 📝 API Endpoints

### Authentication
- `POST /auth/login` - Login
- `POST /auth/register` - Registration
- `GET /auth/users` - Barcha foydalanuvchilar

### Students
- `GET/POST /students` - Talabalar
- `GET/POST /teachers` - O'qituvchilar
- `GET/POST /courses` - Kurslar
- `GET/POST /payments` - To'lovlar
- `GET/POST /attendance` - Davomat

## 🔐 Demo Accountlar

| Role | Username | Password |
|------|----------|----------|
| 👑 Admin | admin | admin123 |
| 👨‍🏫 Teacher | teacher1 | teacher1 |
| 👨‍🎓 Student | student1 | student123 |

**Eslatma:** O'qituvchi paroli `teacher1` ga o'zgartirildi!

## ✨ Xususiyatlar

- Zamonaviy va qulay interfeys
- Tezkor va ishonchli backend
- Responsive dizayn (mobil qurilmalar uchun ham mos)
- O'zbek tilida interfeys
- Real-time statistika

## 📞 Aloqa

Loyiha ochiq kodli va bepul foydalanish uchun.
