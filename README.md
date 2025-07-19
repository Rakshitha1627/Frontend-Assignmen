# 🗓️ Recurring Date Picker Component

A reusable React-based recurring date picker component that allows users to select complex recurring schedules similar to productivity tools like TickTick.

---

## 🚀 Features

- ✅ Supports **Daily**, **Weekly**, **Monthly**, and **Yearly** recurrence
- ✅ Custom intervals like every X days/weeks/months/years
- ✅ Select specific weekdays (e.g., Monday, Wednesday)
- ✅ Choose monthly patterns like “The second Tuesday of every month”
- ✅ Start and optional end date selection
- ✅ Mini calendar preview of selected recurring dates
- ✅ Built with **Next.js**, **Tailwind CSS**, and **Zustand**
- ✅ Unit and integration tests with **Vitest** and **React Testing Library**

---

## 🛠️ Tech Stack

- ⚛️ **React / Next.js** – Frontend framework
- 🎨 **Tailwind CSS** – Styling
- 🧠 **Zustand** – State management
- 🧪 **Vitest** – Unit testing
- 📅 **react-day-picker** (optional) – Calendar rendering

---

## 📦 Folder Structure

recurring-date-picker/
│
├── public/
│   └── index.html
│
├── src/
│   ├── assets/                  # Images, SVGs, etc.
│   ├── components/              # UI components (modular + reusable)
│   │   ├── RecurrenceSelector.jsx
│   │   ├── RecurrenceInterval.jsx
│   │   ├── WeeklySelector.jsx
│   │   ├── MonthlyPatternSelector.jsx
│   │   ├── DateRangePicker.jsx
│   │   ├── CalendarPreview.jsx
│   │   ├── SummaryDisplay.jsx
│   │   └── SaveButton.jsx
│   │
│   ├── store/                   # Zustand store
│   │   └── useRecurringStore.js
│   │
│   ├── utils/                   # Utility functions (e.g. summary generator, validation)
│   │   └── summaryUtils.js
│   │
│   ├── hooks/                   # Custom React hooks (if needed)
│   │   └── useDateUtils.js
│   │
│   ├── App.js                   # Main component
│   ├── App.css                  # Global styles (if needed)
│   ├── index.js                 # App entry point
│   └── index.css                # Tailwind CSS or global styles
│
├── tests/                       # All unit/integration tests
│   ├── App.test.js
│   ├── RecurrenceSelector.test.js
│   └── ...
│
├── .gitignore
├── README.md
├── vite.config.js
├── package.json
└── package-lock.json

