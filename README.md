# Rentalcar-frontend
Web app for car rental company
# 🚗 RentalCar Frontend – Pet Project

Це pet-проєкт, створений для практики розробки фронтенд-додатків з використанням **Next.js**, **TypeScript**, **Zustand**, **Axios** та взаємодією з публічним API.

---

## 🔍 Опис проєкту

**RentalCar** — це веб-застосунок для оренди автомобілів. Користувачі можуть:

- переглядати доступні авто в каталозі;
- фільтрувати за брендом, ціною або пробігом;
- переглядати деталі обраного автомобіля;
- додавати авто до "Обраних";
- бронювати авто через форму.

---

## 🔧 Технології

- ✅ [Next.js 13+ App Router](https://nextjs.org/)
- ✅ TypeScript
- ✅ Zustand (глобальний стан)
- ✅ Axios (запити до API)
- ✅ CSS Modules / Tailwind CSS (на вибір)
- ✅ REST API: [https://car-rental-api.goit.global/api-docs/](https://car-rental-api.goit.global/api-docs/)

---

## 📁 Основні сторінки

| Сторінка | Маршрут | Опис |
|---------|----------|------|
| Головна | `/` | Банер + кнопка переходу до каталогу |
| Каталог | `/catalog` | Список авто, фільтри, пагінація |
| Деталі авто | `/catalog/:id` | Інформація про авто + форма бронювання |

## 🚀 Запуск проєкту локально

```bash
git clone https://github.com/dianka297/Rentalcar-frontend.git
cd Rentalcar-frontend
npm install
npm run dev
