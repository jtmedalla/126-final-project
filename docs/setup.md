# Setup Guide

## 1. Clone the repository

Navigate to the root of the project directory.

## 2. Configure environment variables

Copy the example environment file and update it with your credentials:

```bash
cp .env.example .env.local
```

## 3. Install dependencies
Note: Make sure pnpm is installed first in your system. Visit https://pnpm.io/installation for installation instructions.

Use the following command to install the dependencies into your system:

```bash
pnpm install
```

## 4. Start database

```bash
pnpx supabase start
```
Take note of the links provided to access the supabase configuration.

## 5. Run the development server

```bash
pnpm run dev
```

Visit `http://localhost:3000` to view the app.
