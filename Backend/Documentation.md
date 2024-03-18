# Project Structure

This project is a NEXT application written in TypeScript. The main source code is located in the `src/` directory.

## `src/` Directory

The `src/` directory contains the main application code. It is organized into several subdirectories and files:

### `actions/`

This directory contains TypeScript files for various actions related to different components of the application. Each file exports functions that define a set of actions related to a specific feature. For example, [`case-action.ts`](src/actions/case-action.ts) contains actions related to the "case" feature of application.

### `app/`

This directory contains the main application logic. It is further divided into two subdirectories:

- `(application)/`: This directory contains the main application pages. For example, [`page.tsx`](src/app/(application)/page.tsx) exports a `Home` function that defines the main application page.

- `(dashboard)/`: This directory contains the dashboard pages. For example, [`dashboard/orders/page.tsx`](src/app/(dashboard)/dashboard/orders/page.tsx) exports an `Orders` function that defines the orders page on the dashboard.

### `components/`

This directory contains React components used in the application. For example, [`footer.tsx`](src/components/footer.tsx) defines a `Footer` component.

### `lib/`

This directory contains utility functions and helper code.

### `middleware.ts`

This file contains middleware functions for server-side logic.

### `schemas/`

This directory contains schemas for data validation.

### `stores/`

This directory contains Zustand stores and similar constructs for state management.

### `styles/`

This directory contains style-related files, CSS, and SCSS.

### `utils/`

This directory contains utility functions and helper code.

Each of these files and directories plays a crucial role in the structure and functionality of the application. For a more detailed explanation, you would need to look into each file and understand its specific role in the application.