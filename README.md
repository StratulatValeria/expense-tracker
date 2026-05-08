![Banner](./public/banner.png)

**Expense Tracker** — современное веб-приложение для управления личными финансами.  
Позволяет отслеживать доходы и расходы, анализировать баланс и управлять транзакциями в удобном и адаптивном интерфейсе.

> Проект создан как **production-ready pet-project** с архитектурой, близкой к реальным коммерческим приложениям.

---

## 🚀 Demo

🔗 **Live:** https://expense-tracker-sigma-tan.vercel.app  
🔗 **Repository:** https://github.com/Vonels/expense-tracker

---

## ✨ Features

- 🔐 Авторизация и защищённые маршруты
- ➕ Добавление / редактирование / удаление транзакций
- 📊 Отображение баланса и истории операций
- 🔍 Фильтрация и поиск
- 📱 Адаптивный дизайн (mobile-first)
- ⚡ Быстрая работа за счёт Next.js App Router

---

## 🧱 Tech Stack

- **Next.js 16 (App Router)**
- **TypeScript**
- **Zustand** — глобальное состояние
- **React Query (TanStack Query)** — работа с API
- **Formik + Yup** — формы и валидация
- **CSS Modules**
- **Axios**
- **ESLint + Prettier**
---

**Ключевые идеи архитектуры:**

- `components/` — плоская структура компонентов  
- `lib/` — работа с API  
- `store/` — Zustand-сторы  
- `types/` — централизованные TypeScript типы  
- `(auth)` и `(private)` layout'ы для роутинга

---

## ⚙️ Installation & Setup

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/OksanaVakuliak/09-auth.git
    cd 09-auth
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    ```

3.  **Environment Variables:** Create a `.env.local` file in the root directory:

    ```env
    NEXT_PUBLIC_API_URL=http://localhost:3000
    ```

4.  **Run the development server:**

    ```bash
    npm run dev
    ```

    Open [http://localhost:3000](http://localhost:3000) with your browser to see
    the result.


---

## 📜 Available Scripts

- Command	Description
- npm run dev	Development mode
- npm run build	Production build
- npm run start	Start production
- npm run lint	ESLint check

---

## 🧩 Future Improvements

- 📈 Графики статистики (Recharts / Chart.js)
- 💱 Мультивалютность
- 🏷 Категории расходов
- 📦 PWA поддержка
- 🌙 Dark mode

## ⭐ Если проект был полезен — поставь звезду репозиторию!
Expense Tracker — Система управління персональними фінансами
Expense Tracker — це сучасний вебдодаток для контролю особистих фінансів. Він дозволяє відстежувати доходи та витрати, аналізувати баланс і керувати транзакціями через зручний та адаптивний інтерфейс.

Проєкт розроблений як production-ready pet-project із архітектурою, максимально наближеною до реальних комерційних додатків.

🚀 Demo
🔗 Live: https://expense-tracker-sigma-tan.vercel.app
🔗 Repository: https://github.com/StratulatValeria/expense-tracker

✨ Особливості (Features)
🔐 Авторизація та захищені маршрути: Реалізовано безпечний доступ до приватних даних користувача.

➕ Повний цикл керування транзакціями: Додавання, редагування та видалення записів про витрати/доходи.

📊 Аналітика: Відображення актуального балансу та детальної історії операцій.

🔍 Гнучкість: Пошук та фільтрація транзакцій для швидкого аналізу.

📱 Mobile-first дизайн: Інтерфейс повністю адаптований під мобільні пристрої.

⚡ Продуктивність: Швидка робота завдяки Next.js App Router.

🧱 Технологічний стек
Next.js 15 (App Router)

TypeScript — для надійної типізації

Zustand — управління глобальним станом

React Query (TanStack Query) — робота з серверним API

Formik + Yup — валідація форм

CSS Modules — ізольовані стилі

Axios — HTTP-запити

⚙️ Встановлення та налаштування
Клонувати репозиторій:

Bash
git clone https://github.com/StratulatValeria/expense-tracker.git
cd expense-tracker
Встановити залежності:

Bash
npm install
Налаштувати оточення: Створіть файл .env.local у кореневій директорії:
NEXT_PUBLIC_API_URL=http://localhost:3000

Запустити сервер розробки:

Bash
npm run dev
