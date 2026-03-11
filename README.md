# Health_Center (Angular + Tailwind)

Modern health-tracking UI built with Angular 17 + Tailwind CSS.

## 🚀 Project Overview

`Health_Center` provides basic health record flows:

- `View Entries` (default route `/view`)
- `Add Entries` (`/add`)
- `Analysis` (`/analysis`)

Implemented with Angular Router and scoped component modules:
- `src/app/view-entries`
- `src/app/add-entries`
- `src/app/analysis`

## 🧩 Tech Stack

- Angular 17.3.x
- Tailwind CSS 3.4.x
- TypeScript 5.4.x
- RxJS 7.x
- Karma + Jasmine for unit tests
- Angular CLI for build tooling

## 🛠️ Prerequisites

- Node.js 18+ or higher
- npm 10+ (or yarn equivalent)
- Angular CLI globally (recommended): `npm install -g @angular/cli`

## ⚙️ Installation

```bash
cd d:\Dhanush\Projects\Health_Center
npm install
```

## ▶️ Development Server

```bash
npm start
```

Open: `http://localhost:4200`

Hot reload is enabled (save file updates automatically).

## 📦 Production Build

```bash
npm run build
```

Dist output: `dist/angulartailwind` (per Angular defaults).

## 🔍 Tests

### Unit tests

```bash
npm test
```

### E2E (not configured by default)

No E2E package is currently installed. Add one and configure in `angular.json` if required.

## 🗂️ Project Structure

```
src/
  app/
    add-entries/
    analysis/
    view-entries/
    app.component.*
    app.routes.ts
  assets/
  styles.css
  main.ts
```

### Routing

Defined in `src/app/app.routes.ts`

- `/view` -> `ViewEntriesComponent`
- `/add` -> `AddEntriesComponent`
- `/analysis` -> `AnalysisComponent`
- default redirect to `/view`

## 🔧 Configuration Notes

- Tailwind is integrated via `postcss` in Angular CLI config (default generated style pipeline).
- Use `src/styles.css` for global Tailwind directives (`@tailwind base`, `@tailwind components`, `@tailwind utilities`).

## ✅ Contribution

1. Fork repository
2. Create feature branch `feature/your-change`
3. `npm install`
4. `npm start`
5. Create PR with a descriptive title and tests

## 📜 License

MIT (or add your preferred license).

## 📬 Contact

For issues, file a GitHub issue or reach out to repository owner.

