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

📁 src/
│
├── 📂 components/ # UI Components
│ ├── RecurrenceTypeSelector.jsx
│ ├── IntervalInput.jsx
│ ├── WeekdaySelector.jsx
│ ├── MonthlyPatternSelector.jsx
│ ├── DateRangePicker.jsx
│ ├── CalendarPreview.jsx
│ └── tests/ # Test files
│ └── RecurringDatePicker.test.js
│
├── 📂 store/
│ └── useRecurringStore.js # Zustand state management
│
├── 📂 utils/
│ └── recurrenceUtils.js # Logic for date calculations
│
└── App.jsx / index.jsx # Main entry component
