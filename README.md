# Vue Staff Directory — Beginner Practice

A mock frontend exercise for IT-01 practice, not an official DND assessment.
Allow 30–45 minutes. Data and a working Vue starter are provided; the solution is intentionally unfinished.

## Run

Use Node.js 22.18 or newer.

```sh
npm install
npm run dev
```

Open the local URL printed in the terminal. To check a production build:

```sh
npm run build
```

## Your task

1. Display the supplied employees in the table, showing name and department.
2. Bind the search input using `v-model`.
3. Use a computed property to filter employees by name, ignoring capitalization.
4. Display “No employees found” when the search has no matches.
5. Add basic CSS for spacing, table borders, and readable input and heading styles.

Use `v-for` and a stable `:key` when rendering rows. Keep the existing input label and semantic table markup.
No backend, API calls, storage, routing, or separate components are required.

## Files to work in

- `src/App.vue`: add the Vue logic and table rows.
- `src/style.css`: add your styles.
- `src/data/employees.js`: provided data; no changes needed.

## Manual checks

- On first load, all four employees appear.
- Searching `alex` or `ALEX` shows Alex Smith.
- Searching `lee` shows Jordan Lee.
- Searching `zzzz` displays the empty-state message.
- Clearing the search restores all four employees.
- The input is accessible by keyboard and the layout fits a narrow screen.

## Knowledge questions

1. Git: What does `git pull` do?
2. HTML: What is the purpose of `<th>` in a table?
3. CSS: What is the difference between margin and padding?
4. JavaScript: What does `filter()` do?
5. Vue: Why should you use `:key` with `v-for`?

Assessment focuses on working features, understandable code, and a readable page.
