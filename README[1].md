# Library Management System

A modern library management application built with Next.js, React, TypeScript, and Tailwind CSS using shadcn/ui components.

## Installation

```bash
# Install dependencies
pnpm install

# Add shadcn components (if needed)
pnpm dlx shadcn@latest add button input card
```

## Overview

This application allows users to manage a collection of books with features including:

- **Search**: Filter books by title or author
- **Add**: Add new books with title and author
- **Edit**: Modify existing book information
- **Remove**: Delete books from the collection

## Getting Started

First, run the development server:

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.

## Project Structure

```
.
├── app/
│   ├── favicon.ico
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   ├── ui/
│   │   ├── button.tsx
│   │   ├── card.tsx
│   │   └── input.tsx
│   └── library-button.tsx
├── lib/
│   └── utils.ts
├── public/
├── components.json
├── package.json
├── pnpm-lock.yaml
├── pnpm-workspace.yaml
├── postcss.config.mjs
├── README.md
└── tsconfig.json
```

## Technologies Used

- **Next.js 15+**: React framework
- **React 19+**: UI library
- **TypeScript**: Type safety
- **Tailwind CSS**: Utility-first CSS framework
- **shadcn/ui**: Component library (Button, Card, Input)
- **pnpm**: Package manager
# 24bda70017-3b-AyushBhardwaj
