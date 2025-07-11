# 🎓 Teacher Management Interface

A **responsive**, **modern**, and **intuitive** teacher management interface created using **HTML**, **Tailwind CSS**, and designed for integration with **Next.js** and **TypeScript**. This interface can be used to manage teacher details, qualifications, schedules, and availability in a clean and user-friendly layout.

---

## 🚀 Project Overview

This project is a UI mockup of a Teacher Management Dashboard that displays:

- Teacher personal information (name, contact, email, etc.)
- Private and group qualifications with hourly rates
- A weekly availability schedule (Monday to Sunday)
- A sidebar navigation layout and tab system for sub-sections
- Responsive layout for modern browsers

Although the current version is static (HTML + TailwindCSS), it is structured to be easily converted into a full-featured web app using **Next.js** and **TypeScript**.

---

## 🧱 Technologies Used

| Tech        | Description                                      |
|-------------|--------------------------------------------------|
| HTML        | Static structure for layout                      |
| Tailwind CSS| Utility-first CSS framework for styling          |
| Next.js     | *(Recommended)* React-based framework for routing, pages, and performance |
| TypeScript  | *(Recommended)* Adds static typing to JavaScript for safer, scalable development |

---

## 🧩 Folder Structure Explanation

This project (in HTML) can be easily split into React components when ported to Next.js + TypeScript. Below is the conceptual component breakdown:

### 🧠 Code Overview

- **`Header`**: A fixed red bar at the top with the location (`Richmond Hill`) and user icon.
- **`Sidebar`**: A dark sidebar with navigation links (Teachers, Students, Timeline, etc.).
- **`Main Content`**:
  - **Breadcrumb/Title**: Displays the current teacher being viewed.
  - **Details Cards**:
    - `Details`: Teacher's name, role, and birth date.
    - `Email`: Work email address.
    - `Phone`: Contact number.
    - `Address`: Home address.
  - **Qualifications Tables**:
    - `Private Qualifications`: A table listing subjects and rates.
    - `Group Qualifications`: (Empty for now).
  - **Schedule Section**:
    - Tabbed interface (Availability, Schedule, Students, Comments, etc.)
    - Weekly timetable from 7:30 AM to 5 PM showing booked (green) and empty (gray) slots.



1. **Initialize a Next.js Project**

   npx create-next-app@latest teacher-management --typescript
   cd teacher-management
Install Tailwind CSS
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
Configure Tailwind (tailwind.config.js)
content: ["./pages/**/*.{ts,tsx}", "./components/**/*.{ts,tsx}"]
Break HTML into Components
/components
  └── Header.tsx
  └── Sidebar.tsx
  └── TeacherDetails.tsx
  └── QualificationTable.tsx
  └── ScheduleGrid.tsx
/pages
  └── index.tsx
Run Dev Server
npm run dev

📬 Contact
For questions:
GitHub:Shabiya George
Email: shabiyageorge@gmail.com

