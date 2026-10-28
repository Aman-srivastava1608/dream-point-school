# Scholar — School Management Frontend Demo

A responsive React, Vite, Tailwind CSS, React Router, Lucide and Recharts school ERP presentation. No backend, database, paid service, or real messaging integration.

## Run

Requires Node.js 20.19+ or 22.12+ and npm.

```sh
npm install
npm run dev
```

Open the localhost URL printed by Vite. Production build: `npm run build`. Preview: `npm run preview`.

## Demo login

- Email: admin@school.com
- Password: Admin@123

## Included

100 seeded students, 10 teachers, eight classes, interactive charts, searchable/paginated directories, CRUD forms with confirmation, CSV exports, attendance, optional browser camera preview, simulated scan and punch history, fee collection and printable receipts, exam scheduling, marks and printable reports, notice board, simulated WhatsApp history, school settings with logo preview, dark mode and mobile navigation.

Secondary sidebar modules use meaningful local demo screens and reusable record forms. They are previews, not complete production workflows. Attendance is the current demo day; historical reporting and real biometric recognition are not implemented. School dashboard baseline totals and notices are illustrative. The login is frontend-only and offers no real security. Never enter sensitive real student data.

Camera requires localhost or HTTPS and permission. The simulated scan works without a camera, and does not identify anyone or upload frames. WhatsApp actions only save a simulation locally. Payment records do not transfer money.

All demo data and login state are stored in this browser's localStorage. To reset, clear the site's local storage in browser developer tools. Data in another browser will be separate.

## Structure

- `src/main.jsx`: reusable components and module screens
- `src/data.js`: deterministic mock data and navigation
- `src/style.css`: Tailwind import and responsive theme

Deploy the generated `dist` directory to any static host with a single-page-app fallback to `index.html`.
