# Nextjs 15

# What is Nextjs?

- A react framework for building production-ready full-stack web applications.
- It uses react for building user interfaces.

# Why learning Nextjs?

- It simplifies the process of building production-ready web applications.
- You don't need to install additional packages.
- Provides additional features that enable you to build production-ready
  applications, such as:
  - Routing
    - provides file based routing, you create a file then by default route is generated.
  - API routes
    - enables you to build Frontend react components and Backend APIs in one application, allowing seamless integration.
  - Rendering
    - supports both server-side and client-side rendering, improving performance and better search engine optimization.
  - Data fetching
    - provides build-in async await support in react components, making data fetching efficient.
  - Styling
    - supports CSS modules, Tailwind CSS, to merge CSS preferences.
  - Optimization
    - provides optimization for fonts, images and scripts, enhancing overall user experience.
  - Development and production build system
    - provides optimized development and production system.

N.B Folders within src/app folder are routes by default.

# Installation:

```bash
run npx create-next-app@latest //creating new projects
// Clone or download the repo 
run npm i //installing dependecies
run npm run dev //to start a project
```

# Prerequisite:

- Nodejs (v18+).
- Text Editor (any of your choice).

# Overview

### Home route

```bash
src/app/page.tsx //treated as the home route when visiting localhost:3000.
```

- The localhost:3000 check for the page.tsx in app folder and render the component in the layout.tsx then the details of the component is displayed.

## Single Routes:

### About route

```bash
src/app/about/page.tsx //the about route.
```

### Contact route

```bash
src/app/contact/page.tsx //the contact route.
```

### Profile route

```bash
src/app/profile/page.tsx //the profile route.
```

## Nested Routes:

### Blog routes

```bash
src/app/blog/page.tsx //the blogs route.

src/app/blog/first/page.tsx //the first blog route which is the sub-folder of the main.

src/app/blog/second/page.tsx //the second blog route which is the sub-folder of the main.
```

## Dynamic Routes:

### Product routes

```bash
src/app/products/page.tsx //the products route.

src/app/products/[productId]/page.tsx //the dynamic product route.
```

## Nested Dynamic Routes:

### Reviews routes

```bash
src/app/products/[productId]/reviews/page.tsx //the nested dynamic reviews route.

src/app/products/[productId]/reviews/[reviewId]/page.tsx //the nested dynamic review route.
```
